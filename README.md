# Speech-Emotion-Recognition
This repository if for Speech Emotion Recognition on [Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio) dataset using Pytorch. The dataset is available on the Kaggle page.
This repository contains three jupyter notebooks.
* creating_labels.ipynb
* create_MFCC_dictionary.ipynb
* MAIN.ipynb

The first two notebooks are for preprocessing of the RAVDESS dataset. The notebook titled 'MAIN' is for creating the model and training.

# Observations

## Results after training for 50 epochs:
* Maximum training accuracy = 93.67 %
* Maximum validation accuracy = 70.42 %
* Maximum validation f1 accuracy = 73.67 %
## Graphs:
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/Loss_graph.JPG)
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/accuracy_graph.JPG)
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/f1_accuracy_graph.JPG)
## Confusion matrices with maximum f1 accuracy:
### Validation confusion matrix
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/val_confusion_matrix.JPG)
### Training confusion matrix
![alt text](https://github.com/Azithral/Speech-Emotion-Recognition/blob/master/Images/train_confusion_matrix.JPG)
# Requirements




# Citation:
*  "The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)" by Livingstone & Russo is licensed under CC BY-NA-SC 4.0

