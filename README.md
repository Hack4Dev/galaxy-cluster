# Classification/clustering of galaxies using supervised and unsupervised learning.

#### Status: in progress

## Description
   
Welcome to the Galaxy Clustering hackathon project! This project includes the following tutorials:

- *Tutorial 1* : Data Preprocessing
- *Tutorial 2* : Automatic Feature Extraction/Engineering
- *Tutorial 3* : Manual Feature Extraction/Engineering
- *Tutorial 4* : Data Visualisation
- *Tutorial 5* : Galaxy classification/clustering

## Data

The [GalaxyMNIST](https://github.com/mwalmsley/galaxy_mnist) dataset is used for these tutorials. It contains 10,000 images of galaxies (either 3x64x64 or 3x224x224), labelled by Galaxy Zoo volunteers as belonging to one of four morphology classes:

0. smooth and round
1. smooth and cigar-shaped
2. edge-on-disk
3. unbarred spiral


## Hackathon Task
After completing the tutorials, find a new dataset to try out the tools and methods mentioned in the tutorials. You can explore data in any subject area, as long as it's image data. The data doesn't have to be labelled, as we already taught you how to do unsupervised learning (clustering). The only constraint is that the dataset should contain less than 10,000 images, so that the pipeline will run in a reasonable amount of time. Please approach an instructor if you need some advice.

## Prerequisites

All the libraries/dependencies necessary to run the tutorials are listed in the [requirements.txt](https://github.com/Hack4Dev/galaxy_CV/blob/main/requirements.txt) file.


### Installation


```bash
pip install -r requirements.txt
```

### Would you like to clone this repository? Feel free!

```bash
git clone https://github.com/Hack4Dev/galaxy_CV.git
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

E. Fielding, C. N. Nyirenda and M. Vaccari, "The Classification of Optical Galaxy Morphology Using Unsupervised Learning Techniques," 2022 International Conference on Electrical, Computer and Energy Technologies (ICECET), 2022, pp. 1-6, doi: [10.1109/ICECET55527.2022.9872611](https://doi.org/10.1109/ICECET55527.2022.9872611).

### Data used

Walmsley, Mike, et al. "Galaxy Zoo DECaLS: Detailed visual morphology measurements from volunteers and deep learning for 314 000 galaxies." Monthly Notices of the Royal Astronomical Society 509.3 (2022): 3966-3988, doi:[10.48550/arXiv.2102.08414](https://doi.org/10.48550/arXiv.2102.08414), [code](https://doi.org/10.5281/zenodo.6483176
).
