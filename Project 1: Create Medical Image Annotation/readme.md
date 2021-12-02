## Introduction to task
The aim fof this task is to build a product that helps doctors quickly identify potential cases of pneumonia in children. As a product manager, a labeled dataset is built (to be used by ML to build a classification system in future) that distinguishes between healthy and pneumonia x-ray images 

The classification system should be able to:
* Can help flag serious cases
* Quickly identify healthy cases
* And, generally, act as a diagnostic aid for doctors

The main task is to create a data labeling job using Appen's platform. 

## Data

Udacity provided a data file xray_image_data.csv; a modified version of Kaggle chest x-ray dataset, with most labels removed (of over 100 images in this dataset, only 16 of them are labeled). Every piece of data is a chest x-ray image. The images are slightly different in size and taken under slightly different exposure times. The provided labels are known pneumonia/healthy cases, note any visual patterns, and create accurate test questions.

### Potential annotators that indicate pneumonia
There are a few different visual symptoms that indicate pneumonia. The most important areas to have annotators pay attention to are the lungs and the diaphragm.

* A normal, healthy image will depict clear lungs without any areas of abnormal cloudiness/opacity; there may be structured, web-like vasculature in the lungs but otherwise that area should be clear. In healthy images, you are also more likely to see a diaphragm shadow.
* A pneumonia image may include a few things: areas of cloudiness/opacity in several concentrated areas or one large area. You may also see a general pattern of opacity that obscures the structure of the lungs, heart and diaphragm.

## Project files
1. An HTML Instructions_Preview.html file that includes your instructions, examples, and some sample test questions (as can be seen when you save a job and Preview the result.
2. A pdf Proposal file, which is a writeup that details your design considerations and strategies for quality assurance.

## Steps

1. Create job using appropriate template: Since this is a annotation task, I have used <Strong>Image Categorization</strong>
