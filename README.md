# Cats vs Dogs: From Scratch to Transfer Learning

> How far a small CNN gets on its own, and how much data augmentation and a pretrained VGG16 add.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white) ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?logo=googlecolab&logoColor=white)

## Highlights

- Four models compared on the same 2,000 / 1,000 / 2,000 image split.
- Test accuracy from 72.0% (from scratch) to 97.8% (VGG16).

## Results

| Model | Test accuracy |
|---|---|
| CNN from scratch | 72.0% |
| + data augmentation and dropout | 84.9% |
| VGG16 feature extraction with augmentation | 97.8% |
| VGG16 fine-tuned | 97.8% |

## Credits

Course lab. The code was provided by the course and is adapted from chapter 8 of *Deep Learning with Python* by François Chollet. My additions were unpacking Kaggle's Dogs vs Cats data in Colab and sorting the images into class folders.
