# DS3000 Final Project
Final project for DS3000 (Foundations of Data Science) taken at Northeastern University

## Authors:
* Amy Tang: https://github.com/tang-amy
* Tom Cairns: https://github.com/tomcairns1
* Gabriel Deacon: https://github.com/gdeacon99
* Benjamin Kosiborod (myself): https://github.com/bendavp

## Summary: 
Oil spills affect the health of shore birds, yet it may be difficult for researchers to determine the proper physiological markers to look for when determining whether a given shorebird was affected. We attempted to solve this knowledge gap by constructing a model to help predict whether a shorebird was impacted by an oil spill. To do this, we took data from a Deepwater Horizon Oil Spill study that measured various physiological markers in captured shorebirds that were marked as either "Reference" birds (not affected by an oil spill), or "Impacted". We fed this data to a supervised machine learning classification algorithm and tuned the algorithm to be able to predict with a reasonable amount of accuracy whether a given shorebird was affected by an oil spill. We cleaned up and explored our data, which we then used to construct our model and evaluate its performance with some of our data, and tested the model with the rest of the data (i.e. any data we didn't use to train the model). Our hypotheses turned out to be somewhat supported by the data, but we discovered that this varies depending on which species is the focus. The most accurate ML classification algorithm turned out to be a Decision Tree algorithm, which is able to predict with roughly 92% accuracy whether a given shore bird was affected by an oil spill.

## Contents:
* the dataset (CSV/PDF files) used 
* code for cleaning the data, testing supervised machine learning algorithms
* powerpoint, summarizing key points of project goals and outcomes
* mp4 video of powerpoint presentation: https://youtu.be/hKkDZRvRYa0
