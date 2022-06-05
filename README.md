# Text-to-Face DCGAN

**Disclaimer**:
Please notice that the final goal has not been reached yet.
A technical feasibility could be proven, but a model could not be trained due to an insufficient amount of available data.

## Kudos to Tensorflow
Big kudos to Tensorflow for the great documentation on their Deep Convolutional Generative Adversarial Network build for the MNIST dataset which was used as a foundation to build the following Text-to-Face DCGAN.

https://www.tensorflow.org/tutorials/generative/dcgan

*Please notice that the tutorial might have changed slightly compared to the version I used.
This is the exact version I reference to: https://github.com/tensorflow/docs/blob/8ce6c722fc054445ff4ffc5b8b605a3271e10dc7/site/en/tutorials/generative/dcgan.ipynb*

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

## Steps
0. Check out Tensorflow's tutorial about their DCGAN for MNIST

## Contributors
- Tom Naumann
- Fabian Herhold
- Elvisa Foric