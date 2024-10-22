# engagement
Engagement Prediction
updated by 20241015

# Dataset
- EngageNet: Do I Have Your Attention: A Large Scale Engagement Prediction Dataset and Baselines [[paper]](https://arxiv.org/pdf/2302.00431)
- DAiSEE: Towards User Engagement Recognition in the Wild(2015)[[paper]](https://arxiv.org/pdf/1609.01885)
- HBCU:The Faces of Engagement: Automatic Recognition of Student Engagement from Facial Expressions(2014)[[paper]](https://inc.ucsd.edu/mplab/46/media/EngagementRecognitionFinal.pdf)
- EngageWild: Prediction and Localization of Student Engagement in the Wild(1997)[[paper]](https://arxiv.org/pdf/1804.00858

# Surveys


# Methods
[1] Bag of States: A Non-sequential Approach to Video-based Engagement Measurement(arxiv’2023）[[paper]](https://arxiv.org/pdf/2301.06730)

[2] Predicting Student Engagement Using Sequential Ensemble Model(IEEE Transactions on Learning Technologies'2023)[[paper]](https://ieeexplore.ieee.org/abstract/document/10360221)

[3] Three-dimensional DenseNet self-attention neural network for automatic detection of student’s engagement(Applied Intelligence'2022)[[paper]](https://link.springer.com/content/pdf/10.1007/s10489-022-03200-4.pdf)

[4] Leveraging part-and-sensitive attention network and transformer for learner engagement detection [[paper]](https://www.sciencedirect.com/science/article/pii/S1110016824006835)

| Methods | Feature-based Method| End-to-end Method|
| ---- | ---- | ---- | 
| BoS [1] | ◯ |  X | 
| Four-step approach [2] | ◯ |  X |
| DenseAttNet[3] | X | ◯ | 
| DTransformer[4] | X | ◯ |


| Methods | Sequential Feature | Spatial Feature | Head Pose| Eye Gaze | Body | Facial Features|
| ---- | ---- | ---- | ---- |---- | ---- |---- |
| BoS [1] | X |  X | ◯ | ◯ | ◯ |◯|
| Four-step approach [2] | ◯ |X |  ◯ | ◯ | X |◯|
| DenseAttNet[3] | ◯ | X | X | X | X |◯|
| DTransformer[4] |◯| ◯ | - | - |-|


# Results

## IIITB Online SE Dataset
| Methods | Accuracy | Precision | Recall | F1 | Params | 
| ---- | ---- |---- |---- |---- |---- |
| BoS [1] | 0.93 | 0.93 |0.91|0.95|

## DAiSEE Dataset
| Methods | Accuracy | Precision | Recall | F1 | Params | MSE|
| ---- | ---- |---- |---- |---- |---- |---- |
| BoS [1] | 66.58 | - |-|-|-|
|Four-step approach[2]| -|-|-|-|-|0.0386|
|DenseAttNet[3]| 62.15|-|-|0.60|-|0.0347|
|DTransformer[4]| 64|-|-|-|-|-|



## EmotiW-EP Dataset
| Methods | Accuracy | Precision | Recall | F1 | Params | MSE|
| ---- | ---- |---- |---- |---- |---- |---- |
|Four-step approach[2]| -|-|-|-|-|0.0610|
|DenseAttNet[3]| -|-|-|-|-|0.0877|
|DTransformer[4]| -|-|-|-|-|0.0729|




