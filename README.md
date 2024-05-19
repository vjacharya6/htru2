# HTRU_2 Radio Telescope Data Analysis

The dataset `HTRU_2.csv` contains radio telescope data from the High Time Resolution Universe Survey (South). This dataset is used to train and test various classifiers to distinguish between pulsar signals and noise.

## Predictors

The dataset includes the following 8 predictors:

1. **Mean of the Integrated Signal Profile**
2. **Standard Deviation (SD) of the Integrated Signal Profile**
3. **Kurtosis of the Integrated Signal Profile**
4. **Skewness of the Integrated Signal Profile**
5. **Mean of the Dispersion Measure vs Signal-to-Noise Curve**
6. **Standard Deviation (SD) of the Dispersion Measure vs Signal-to-Noise Curve**
7. **Kurtosis of the Dispersion Measure vs Signal-to-Noise Curve**
8. **Skewness of the Dispersion Measure vs Signal-to-Noise Curve**

**Dispersion Measure**: The dispersion in the signal as it passes through the interstellar medium, related to the electron column density.

These are the identifying characteristics of Pulsars, see Lyon et al.,arXiv:1603.05166.

## Label

The label in the dataset is binary:
- **1**: Represents pulsar signals as annotated by human experts.
- **0**: Represents noise due to radio frequency interference.

## Analysis

The Jupyter notebook `htru2.ipynb` trains and tests a few garden-variety classifiers on this data to distinguish between pulsar signals and noise.

