# A Comparison between LSTM and RNN for Speech Classification Using TensorFlow
This study is adapted from a TensorFlow [tutorial](https://www.tensorflow.org/tutorials/audio/simple_audio), with modifications made to suit the goal of this project. 
## Introduction
The study aims to compare LSTM and RNN models for speech classification using TensorFlow on a dataset of eight short commands.

## Methodology
The methodology used in this study involves training LSTM and RNN neural networks to classify audio files containing eight basic commands using TensorFlow. \
The performance of the models is evaluated using the classification_report() function from sklearn.metric. \
Python is the development environment, and TensorFlow is the main library used. \
Other libraries such as matplotlib, numpy, and seaborn are also used to support the study. 

## Result and analysis
This study compared the accuracy, precision, recall, and F1-score of LSTM and RNN models trained on STFT and MFCC features, and found that LSTM models outperformed RNN models in all metrics.
### Feature extraction comparison
This study observed that STFT features produced more dynamic and depthful spectrograms than MFCC features, and that STFT was more suitable for LSTM models while MFCC was more well-rounded for both models.
### Best and worst performing models
The best performing model was the LSTM model trained on STFT features, with accuracy score of 0.9099, precision of 0.9112, recall of 0.9099 and F1-score of 0.9100. \
The worst performing model was the RNN model trained on STFT features, with accuracy score of 0.1130, precision of 0.1537, recall of 0.1130 and F1-score of 0.0577.

## Conclusion
LSTM and RNN models were created and trained with the mini_speech_commands audio dataset to perform simple speech command classification task using TensorFlow. \
In general, LSTM models perform better as compared to RNN models for the simple speech command classification. \
The best performing model at classifying the simple speech commands is the LSTM model trained on STFT extracted features, with accuracy score of 0.9099, precision of 0.9112, recall of 0.9099 and F1-score of 0.9100. \
Meanwhile, the worst performing model is the RNN model trained on STFT extracted features with accuracy score of 0.1130, precision of 0.1537, recall of 0.1130 and F1-score of 0.0577.
