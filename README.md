# Facial-Expressions-Detection

## Overview
In this project, we used different approaches to solve the problem using classification and detection. We defined two problems in this work, classification task and detection (with bounding box) task. Our aim in this work is to produce good precision results in both tasks. Also, having good IOU (intersection over area) and mAP (mean Average Precision) for the detection task. In this work, a
publicly available dataset was used. The dataset is from Kaggle, and contains 7 classes: angry, disgust, fear, happy, neutral, sad, and surprise.

## Approach
After extensive reviewing for the literature, it was
decided to investigate 3 different approaches to tackle
this problem. First approach is basically combining
computer vision flavor with machine learning
classifier. Therefore, it contains feature generation
and image processing. Second approach is involved
with neural networks, namely CNN as it has always
yielded prosperous results in computer vision
problems. Third approach was experimenting with
the state-of-the-art YOLO for object detection and
localization.
