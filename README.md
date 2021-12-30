# A causality example with AirBnB data

The notebook of this repository contains an example based on the listings information from [Inside AirBnB](http://insideairbnb.com/get-the-data.html) webpage.

This example was presented in the talk given for [Singularity Tech Day 2021](https://singularitytechday.com/)

In this notebook a first part consists of analysing the data from all the listings in Madrid city area and from there try to deduce the reasons behind why a listing get high value ratings.
For this example I have used the [DoWhy](https://github.com/Microsoft/dowhy) from Microsoft Research.


## Environment Installation

For the installation you have two options:

1. Through `pip`
```bash
	$ pip install -r requirements.txt
```
2. Or through `conda`
```bash
	$ conda env create -f environment.yml
	$ conda activate causality
```
