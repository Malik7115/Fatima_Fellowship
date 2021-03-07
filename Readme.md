# General Information

**Subitted by**: Muhammad Ibrahim Malik
**Coding Challenge Chosen**: Deep Learning Vision

## Disclaimer

1. It is requested that the reviewer pardon the inadequacies regarding good code practices and writing efficient code.

2. I still consider myself a student of DL and a beginner in the domain, there is much for me to learn in terms of both theory and practice.

## The Code

The notebook is provided with the results. If the reviewer wishes to run the cells line by line, please follow the instructioctions below:

1. Download dataset from the following link: [google drive link](https://drive.google.com/drive/folders/1acbFUcMHQ4SeRzF0wxL-og562GFXYUUW?usp=sharing)
2. In the second cell change the path of the dataset (the variable called **dataset**) to where the dataset is downloaded
3. Run all the cells

## The Dataset

1. The dataset used is obtained from the software AirSim. It was used for another project.

2. This dataset was chosen because it has very less variation above the horizon, so intuitively it was considered that this would provide not much difficulty in training the network.

## Results

1. with only 1 iteration the network gives an accuracy of ~98%
2. with this high of an accuracy there were *No* images that were wrongly classified in the test dataset.

## Improvements

1. Since there is very less variation in the images, the network will not generalize. To get a better generalization that would cater for variations in the dataset, ***we could manually provide random distortions/variations for images, for example: changing brightness, affine transformations, etc***.