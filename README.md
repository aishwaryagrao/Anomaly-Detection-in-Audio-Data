# Anomaly-Detection-in-Audio-Data
Aim to compare algorithms and find anomalies in the audio dataset of a person

Dataset used: Voice recordings of Nelson Mandela. Each file is in WAV format(.wav extension), having 1 second of duration and 32KB Size(Memory): https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset/data
Feature extraction: Spectrogram, Mel Spectrogram and MFCC(Mel-frequency cepstral coefficients).
Algorithms used: Training One-Class SVM (Support Vector Machine) and Isolation Forest using Mel Spectrogram.
Test data: Voice recordings of the same person, noise and voice recordings of different people.
