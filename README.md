# Text-to-Face DCGAN

**Project Status**<br>
Please notice that the ultimate goal has not been reached yet.<br>
The notebooks are well suited as a foundation for further research, but a model with a proper performance couldn't be trained among others due to an insufficient amount of data.

## Objective
The ultimate goal is to generate a high-quality image of a human face based on defined facial characteristics.

## Steps
0. Check out Tensorflow's tutorial about their DCGAN for MNIST
1. Control the generated MNIST image (28x28x1) by feeding an additional text input feature (see Notebook 1)
2. Generate random human faces (64x64x1) (see Notebook 2)
3. Control the generated human face (64x64x1) with additional facial characteristic inputs (see Notebook 3)

## Dependency Management
We are using Poetry to manage all required dependencies to ensure a smooth execution of all available code.

Make sure to have Poetry installed locally on your machine!

```
pip install poetry==1.2.0b1
```

In case you have Poetry already installed, execute the following command to create your virtual environment.

```
poetry install
```

Done. You are ready to execute the notebooks.

## Acknowledgments
Big kudos to Tensorflow for the great documentation on their Deep Convolutional Generative Adversarial Network build for the MNIST dataset which was used as a foundation to build the following Text-to-Face DCGAN.

https://www.tensorflow.org/tutorials/generative/dcgan

*Please notice that the tutorial might have changed slightly compared to the version I used.
This is the exact version I reference to: https://github.com/tensorflow/docs/blob/8ce6c722fc054445ff4ffc5b8b605a3271e10dc7/site/en/tutorials/generative/dcgan.ipynb*

## Publications / Reading Material / Inspirations

### Papers
- AnyFace: Free-style Text-to-Face Synthesis and Manipulation (2022) [[Paper](https://arxiv.org/abs/2203.15334)]
- Text-to-Face Generation with StyleGAN2 (2022) [[Paper](https://arxiv.org/abs/2205.12512)]
- Text2Human: Text-Driven Controllable Human Image Generation (2022) [[Paper](https://arxiv.org/abs/2205.15996)]
- StyleT2F: Generating Human Faces from Textual Description Using StyleGAN2 (2022) [[Paper](https://arxiv.org/abs/2204.07924)]
- TediGAN: Text-Guided Diverse Face Image Generation and Manipulation (2021) [[Paper](https://arxiv.org/abs/2012.03308)]
- FTGAN: A Fully-trained Generative Adversarial Networks for Text to Face Generation (2019) [[Paper](https://arxiv.org/abs/1904.05729)]
- AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks (2017) [[Paper](https://arxiv.org/abs/1711.10485)]
- StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks (2017) [[Paper](https://arxiv.org/abs/1710.10916)]
- Generative Adversarial Text to Image Synthesis (2016) [[Paper](https://arxiv.org/abs/1605.05396)]

### Code Repositories
- https://github.com/hanzhanggit/StackGAN
- https://github.com/hanzhanggit/StackGAN-v2
- https://github.com/MINGUKKANG/DCGAN-tensorflow
- https://github.com/taoxugit/AttnGAN
- https://github.com/zsdonghao/text-to-image
- https://github.com/IIGROUP/TediGAN
- https://github.com/sanku-lib/text-to-image

### Others
- https://medium.com/@mrgarg.rajat/implementing-stackgan-using-keras-a0a1b381125e
- https://thispersondoesnotexist.com/

## Contributors
- Tom Naumann
- Fabian Herhold
- Elvisa Foric
