# model-validation

This repository provides a template workflow and stating point for evaluating the performance of deployed models for achieving their target task.

## Overview

A set of notebooks, scripts, and tools to standardise evaluation of predictive models.

This repository will endeavour to be general purpose and support any regression or classification task. However, it has been developed specifically focused on computer vision model deployments.

## Important Questions to Ask

- How big is the dataset?
- How similar is the training dataset to the real-world use case?
- How costly is a true positive, false positive, true negative, false negative?
- Does the above differ between classes?
- Is prediction speed an important variable to consider?
