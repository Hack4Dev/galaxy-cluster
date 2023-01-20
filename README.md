# Classification/clustering of galaxies using supervised and un unsupervised learning.

#### Status: in progress

## Descriptions
   
Welcome to the project on galaxy clustering! From the tutorials you will learn the following:

- *Tutorial 1* : Data Preprocessing
- *Tutorial 2* : Automatic Feature Extraction/Engineering
- *Tutorial 3* : Manual Feature Extraction/Engineering
- *Tutorial 4* : Data Visualisation
- *Tutorial 5* : Galaxy classification/clustering

## Data

The data used is [GalaxyMNIST](https://github.com/mwalmsley/galaxy_mnist) which contains 10,000 images of galaxies (either 3x64x64 or 3x224x224), labelled by Galaxy Zoo volunteers as belonging to one of four morphology classes, where the classes are:

0. smooth and round
1. smooth and cigar-shaped
2. edge-on-disk
3. unbarred spiral


## Hackathon Task
After finishing the tutorials, try to get a totally new data set and try some of the tools we learned from the past few tutorials. You can explore data in any subject area, as long as it's image data. The data doesn't have to be labelled, as we already taught you how to do unsupervised learning (clustering). It also has to have fewer than 10,000 images for the pipeline to run in a reasonable amount of time. Please approach an instructor if you need some advice.

## Prerequisites

All the libraries/dependencies necessary to run the tutorials are listed in the [requirements.txt](https://github.com/Hack4Dev/galaxy_CV/blob/main/requirements.txt) file.


### Installation


```bash
> pip install -r requirements.txt
```

### Would you like to clone this repository? Feel free!

```bash
> git clone https://github.com/Hack4Dev/galaxy_CV.git
```

Then make sure you have the right Python libraries for the tutorials. 


### New to Github?

The easiest way to get all of the lecture and tutorial material is to clone this repository. To do this you need git installed on your laptop. If you're working on Linux you can install git using apt-get (you might need to use sudo):

```
apt install git
```

You can then clone the repository by typing:

```
git clone https://github.com/Hack4Dev/galaxy_CV.git
```

To update your clone if changes are made, use:

```
cd galaxy_CV/
git pull
```

----

### Original research work:

E. Fielding, C. N. Nyirenda and M. Vaccari, "The Classification of Optical Galaxy Morphology Using Unsupervised Learning Techniques," 2022 International Conference on Electrical, Computer and Energy Technologies (ICECET), 2022, pp. 1-6, doi: 10.1109/ICECET55527.2022.9872611.