# fastai experiments
> I'm currently taking the ongoing (yet to be released) version of the fastai course and also reading the fastai [book](https://github.com/fastai/fastbook) alongside. This repository contains experiments and personal projects that I would be working on as I go through the course. 

## Projects

* [COVID-19 Mask Types](#covid-19)
* [Under the hood - MNIST full](#under-the-hood)
* [Basic Learner Implementation](#basic-learner)


## 3. <a name="covid-19"></a>[Basic Learner Implementation](learner.ipynb)

Implements a Learner from scratch based on the training loop in chapter 4 of the fastai book.


## 2. <a name="under-the-hood"></a>[Under the hood: MNIST full](mnist_full_chapter_4.ipynb)

This notebook reproduces chapter 4 of the fastai book on the full MNIST dataset.


## 1. <a name="basic-learner"></a>[COVID-19 Mask Types](masks.ipynb)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/asiedubrempong/fastai-experiments/master?filepath=masks.ipynb)

We are all caught up in the middle of a global pandemic. The novel corona virus is affecting 199 countries and territories around the [world](https://www.worldometers.info/coronavirus/#countries). Many are being encouraged to wear masks as it prevents you from spreading the virus if you're infected and also reduces the chances of contracting the virus. 

I built an image classifier to identify the different types of masks that are being used namely: N95 respirators and surgical masks. There is an increase in the use of home made masks but I wasn't able to curate a dataset of these masks.
