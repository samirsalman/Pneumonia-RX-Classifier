# Pneumonia-RX-Classifier
Pneumonia RX Classifier is a CNN model created with TensorFlow in order to distinguish type of pneumonia from RX image. 

Colab Work is aviable at: 

```https://colab.research.google.com/drive/1qAAclorvsUkmgDXpHhUG267Ibh3UkblL?usp=sharing```.

## Dataset
The dataset used in this project is Chest X-Ray Images (Pneumonia), aviable at: 

```https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia```.

It contains 5,863 images of RX.

Dataset is splitted in three parts:
- Training
- Validation
- Test

In this project I used only training and validation parts. 

The classification labels are:

- **NORMAL** : RX without pneumonia
- **PNEUMONIA_BACTERIA**: RX with Bacteria Pneumonia
- **PNEUMONIA_VIRUS**: RX with Virus Pneumonia

<img src="https://i.imgur.com/jZqpV51.png"/>


## CNN Model

For my purpose I used a CNN model with the following architecture:

<img src="https://github.com/samirsalman/Pneumonia-RX-Classifier/blob/main/arch.PNG"/>


## Test Results

The results with batch size = 8 are the following.

model  | accuracy 
--|--
RX Pneumonia Detector v1.0  | **65,87%** 


## Future Work

- Improve model performances
- Measure with precision, recall and f1 measure
- Data Augmentation


## Author

Samir Salman



