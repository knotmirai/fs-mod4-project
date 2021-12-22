# Module 4 Final Project

# Pneumonia Image Classification with Deep Learning

## The Project

Chest x-ray image analysis is the common and basis diagnosis method in medical field. In order to assess different pathologies, the imaging exam has been used for long time. An automation analysis can minimize the workloads, improve efficiency and reduce the potential of human errors. Thus, this project the CNN model will be built in order to classify chest x-ray images.

## The Dataset

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia 

## Working File

* <b>student.ipynb</b>

## Result File

* presentation.pdf 

## Summary

The current model can classify and distinguish Pneumonia patients and normal people very well. Both the accuracy of training and testing data is very high. When we deal with medical diagnosis, a false positive (i.e. prediciting illness when the patient is healthy) is less critical than a false negative (predicting healthiness when the patient is sick). The number of false negatives obtained with the model presented here is extremely low. Therefore, the machine developed here as a reliable ancillary tool for Pneumonia detection.

## Future Plan

* Add more training data to ensure the accuracy.
* Use Grid Search for better optimization.
* Be able to categorize Pneumonia types.
* Be able to classify other diseases from X-ray images.
