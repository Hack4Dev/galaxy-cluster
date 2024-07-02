# Classification of galaxies.

#### Status: in progress

## Description
   
Welcome to the Galaxy Hackathon project! This project includes the following tutorials:

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
After completing the tutorials, teams must utilize supervised learning to classify four types of galaxy objects. Collaborate to develop a pipeline that surpasses the one presented here. Support your choices with available literature or by experimenting and optimizing with different methods to find the best approach. Please note, avoid optimizing your methods on the testing set, as this constitutes data leakage. Instead, create a validation set from the training set and use the validation set to optimize your methods. A 20:80 split should be sufficient.

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
