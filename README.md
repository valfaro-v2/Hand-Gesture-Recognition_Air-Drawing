# Hand Gesture Recognition & Air Drawing

## Overview:
In this notebook we explore hand gesture (open/closed) recognition using computer vision along with a naive technique as well as two different machine learning techniques. We develop a system capable of recognizing hand gestures in real-time that is complemented with an "air drawing" functionality to draw in a board when the triggering gesture (closed hand) is recognized.

Additionally, a nice functionality to generate labeled data for training on the fly is included.


## Contents:
1. [Hand gesture detection & Air Drawing: naive technique](#naive)
2. ML models for gesture recognition: 
    1. [Hand gesture detection: clustering approach](#cluster) Unsupervised Learning with Clustering to detect whether hand is closed/open.
    2. [Hand gesture detection: multilayer NN approach](#neuron) Supervised Learning by training a neural network (ANN) model to classify whether hand is closed/open. Also building a functionality to generate labeled data for training on the fly.
