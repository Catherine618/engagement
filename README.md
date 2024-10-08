# engagement
Engagement Prediction
updated by 20241008

# Dataset
- EngageNet: Do I Have Your Attention: A Large Scale Engagement Prediction Dataset and Baselines [[paper]](https://arxiv.org/pdf/2302.00431)
- DAiSEE: Towards User Engagement Recognition in the Wild(2015)[[paper]](https://arxiv.org/pdf/1609.01885)
- HBCU:The Faces of Engagement: Automatic Recognition of Student Engagement from Facial Expressions(2014)[[paper]](https://inc.ucsd.edu/mplab/46/media/EngagementRecognitionFinal.pdf)
- EngageWild: Prediction and Localization of Student Engagement in the Wild(1997)[[paper]](https://arxiv.org/pdf/1804.00858

# Surveys


# Methods
[1] Bag of States: A Non-sequential Approach to Video-based Engagement Measurement(arxiv’2023）[[paper]](https://arxiv.org/pdf/2301.06730)
<!-- 
Keyword summary：
video-based, non-sequential，two-stage Method, video segments = bags of behavioral and emotional states, apply K-means to generate codewords with K-means++ for cluster center initialization

Text description:
Ali Abedi et al proposed a two-stage method named Bag-of-States (BoS), which analyzes only the occurrence of Behavioral and affective states. 
Video is firstly divided into equal-length segments, then totally 49 behavioral and affective features were extracted from each segment, including those related to emotions, blink rate, gaze direction, head and wrist positions and poses. After that, the K-means algorithm was used to cluster the feature vectors to create a codebook where the cluster centers served as codewords and each video segment was mapped to a codeword, with the video sample represented by a histogram of codewords.
-->

# Results

## IIITB Online SE Dataset
| Methods | Accuracy | Precision | Recall | F1 | Params | 
| ---- | ---- |---- |---- |---- |---- |
| BoS [1] | 0.93 | 0.93 |0.91|0.95|

## DAiSEE Dataset
| Methods | Accuracy | Precision | Recall | F1 | Params | 
| ---- | ---- |---- |---- |---- |---- |
| BoS [1] | 66.58 | - |-|-|



