# Forecasting species distribution modeling, based on climate projections
Creating species distribution models based upon climate prediction.


Thank you @jcoliver for most of the [code](https://github.com/jcoliver/biodiversity-sdm-lesson) in this repository.

![Phidippus johnsoni](data/johnsoni.jpg). 

Wikimedia Commons


## Introduction

Today we're going to generate both current species distribution models, and predicted species distribution models based on predicted climate. We're doing both mainly so we can readily see the differences between the two, and so we can use updated map code with ggplot.

In the interest of time, we're going to rely pretty heavily upon code created by Jeff Oliver from the University of Arizona. While we won't dig into the guts of the code, those interested should follow the path of the code execution, and look at `src/setup.R`, `src/sdm-functions.R`, `run-sdm-single.R`, and `run-future-sdm-single`.

## Instructions

1. Go to RNR 496B/DSCI 245 workspace on rstudio.cloud, and start the assignment "forecasting".

2. Open `src/sample.R` and follow the steps to create a species distribution model for *Phidippus johnsoni*. We'll do this together as a class.

3. When finished, open `src/yourTurn.R`, and follow the same process to generate a species distribution model for your milkweed species.


## Using this in your group's repository

With some care, you should be able to use this code in your group's repository. Here are the general steps:

1. First, a group member must download the four .zip files [here](https://drive.google.com/drive/folders/10vBMcHCC_0GGW_VG3AZL4sRh19sf82eU?usp=sharing). Then, upload them directly into your main repository. Rstudio.cloud will automatically unzip them, and put them in the correct directory path (data/cmip5/2_5m).

2. Make sure you add the following to your .gitignore file: `data/cmip5/*`

3. Your group's lead programmer could make copies of `setup.R`, `sdm-functions.R`, and `run-future-sdm-single.R`, and put them in your main repository's `src` directory.

4. In your `main.R` file, retrace the steps made in `yourTurn.R`. You may need to make sure all paths are correct, and keep an eye on the console for any errors when running the code.

5. If you run into problems, post a question on Slack, or come to office hours!




