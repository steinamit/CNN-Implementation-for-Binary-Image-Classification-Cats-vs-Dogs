# Image Classification with a CNN (Course Lab)

Binary classification of cats vs dogs, comparing a CNN trained from scratch with data augmentation and transfer learning.

**Context:** deep learning course lab. The notebook is based on code provided in the course, adapted from chapter 8 of *Deep Learning with Python* by François Chollet.

## Data
A subset of Kaggle's Dogs vs Cats: 2,000 training, 1,000 validation and 2,000 test images, resized to 180×180.

## Experiments and test accuracy
| Model | Test accuracy |
|---|---|
| CNN from scratch | 72.0% |
| CNN with data augmentation and dropout | 84.9% |
| VGG16 feature extraction with augmentation | 97.8% |
| VGG16 fine-tuned | 97.8% |

The steps added to the provided code: unpacking the archive in Colab and sorting the images into class folders.

**Tools:** Python · TensorFlow / Keras · matplotlib · Google Colab
