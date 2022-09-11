# Smoking-Detection-ML-Model

## Short description
This is the python code used to create machine learning model finding cigarete smoking action on the pictures.

To see full documentation of the project follow [this link](https://github.com/KubKill/Smoking-Detection-ML-Model/blob/main/Dokumentacja%20projektu.pdf) or open "Dokumnetacja projektu.pdf" file.

## Technologies
* Pytchon
* Torch
* Detecto
* Numpy
* MatplotLib
* Os

## Launch
Load model downloaded from [this link](https://drive.google.com/file/d/1--31GLuDR-xtec9i5TACfCRRg9kyP-3e/view?usp=sharing)
The model is too big to be uploaded to the GitHub.

## Training process

### Data preparation
* I found big set [link](https://www.kaggle.com/datasets/vitaminc/cigarette-smoker-detection) (Like 2k) of photos of smoking peoples on the Kaggle.
* Filtered the one showing peple having lit cigarets in hand, close to mouth, with some smoke. More ore less 100 pictures.
* Labeld fragments of the pictures with laelimg library.

### Training
* I used Detecto pretrained model.
* Augmented dataset.


## Result
* My best model has 80% accuracy on test set.
Works ok on the pictures with rather big person holding cigaret close to mouth. Has problem labaling when smoking people are smaller on the picture (further away).

**No smoking**

![image](https://user-images.githubusercontent.com/66681683/189544431-6f4465b9-9844-4a7f-ac98-268a6bf1a427.png)


**Smoking**

![image](https://user-images.githubusercontent.com/66681683/189544441-5bb4bd07-41c4-4da7-8a1e-a3fe30e4ac80.png)
