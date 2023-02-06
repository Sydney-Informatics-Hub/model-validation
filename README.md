# model-validation

This repository provides a template workflow and stating point for evaluating the performance of deployed models for achieving their target task.

## Overview

Tools for validating model performance.

This repository will endeavour to be general purpose and support any regression or classification task. However, it has been developed specifically focused on computer vision model deployments.

### [deepchecks](https://docs.deepchecks.com/en/stable/user-guide/tabular/auto_quickstarts/plot_quickstart_in_5_minutes.html?utm_source=github.com&utm_medium=referral&utm_campaign=readme&utm_content=try_it_out)

A Python utility for assesing data and model quality.




## Important Questions to Ask

- How big is the dataset?
- How similar is the training dataset to the real-world use case?
- How costly is a true positive, false positive, true negative, false negative?
- Does the above differ between classes?
- Is prediction speed an important variable to consider?
