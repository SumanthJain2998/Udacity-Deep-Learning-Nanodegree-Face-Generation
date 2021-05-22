# Project Overview
In this project, we'll define and train a DCGAN on a dataset of faces. Our goal is to get a generator network to generate new images of faces that look as realistic as possible!
The project will be broken down into a series of tasks from ___loading in data to defining and training adversarial networks.___ At the end of the notebook, we'll be able to visualize the results of our trained Generator to see how it performs; our generated samples should look like fairly realistic faces with small amounts of noise.
## Dataset
We'll be using the  [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train our adversarial networks.
This dataset is more complex than the number datasets (like MNIST or SVHN) so we should define deeper networks and train them for a longer time to get good results. It is suggested to utilize a GPU for training.
## Pro-processed data
Since the project's main focus is on building the GANs, pre-processed data is available for us. Each of the CelebA images has been cropped to remove parts of the image that don't include a face, then resized down to 64x64x3 NumPy images.  
if you are working locally, you can download this data by [clicking here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)
## link to the original repo:
https://github.com/udacity/deep-learning
## link to the course:
https://www.udacity.com/course/deep-learning-nanodegree--nd101
