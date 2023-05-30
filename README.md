# Quantitative analysis in neutron images
<a href="https://github.com/ImagingELearning/QuantifyingNeutronImages" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" height="48px" alt="Open repository"/>
</a>

## Attenuation coeffiicent from step wedge measurements
A tutorial to study water uptake in porous media using neutron imaging.
Objectives:
- Determine the attenuation coefficient for water.

<a href="https://colab.research.google.com/github/ImagingELearning/QuantifyingNeutronImages/blob/main/tutorials/01_AttenationCoefficient/01_Analysis_AttenuationCoefficient.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Time series analysis - studying capillary rise
- Analysing a neutron radiography time series.

<a href="https://colab.research.google.com/github/ImagingELearning/QuantifyingNeutronImages/blob/main/tutorials/02_RadiographyTimeSeries/02_Analysis_CapillaryRise.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Preparation to use the notebook on you local computer
This tutorial is implemented as a jupyter notebook that can be run locally on your own computer or using google colab. The notebook doesn't require any exotic python modules and should work on an Anaconda installation the possible additions of tqdm and tifffile.

```conda install tqdm tifffile```

All dependencies are summarized in the [```environment.yml```](https://github.com/ImagingLectures/WaterInSand/blob/main/environment.yml).

Once this is done, your are ready to go. Just start a jupyter session and navigate to the tutorial notebooks located in the folders under ```tutorials```.
