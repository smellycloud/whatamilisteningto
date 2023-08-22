# whatamilisteningto
Music genre and theme classification using mel-spectrograms, convolutional neural networks and transfer learning

# Dataset source
Bogdanov, D., Won M., Tovstogan P., Porter A., & Serra X. (2019). The MTG-Jamendo Dataset for Automatic Music Tagging. Machine Learning for Music Discovery Workshop, International Conference on Machine Learning (ICML 2019).

# Track count
| Dataset    | Train  | Test   | Validation | Total  |
|------------|--------|--------|------------|--------|
| Mood/Theme | 11,114 | 3,699  | 3,673      | 18,486 |
| Genre      | 33,169 | 11,047 | 10,999     | 55,215 |


# Genre Classification Metrics
| Model Architecture  | Epochs | Top-4 accuracy | ROC-AUC  | PR-AUC   | F-Score  |
|---------------------|--------|----------------|----------|----------|----------|
| VGG19               | 11     | 0.590024       | 0.886725 | 0.247987 | 0.108169 |
| EfficientNetV2-B0   | 10     | 0.568208       | 0.893232 | 0.216523 | 0.067312 |
| Xception            | 6      | 0.604870       | 0.874622 | 0.274456 | 0.145906 |
| DenseNet-201 | 9      | 0.626052       | 0.902065 | 0.288641 | 0.119026 |

# Mood/Theme Classification Metrics
| Model Architecture  | Epochs | Top-4 accuracy | ROC-AUC  | PR-AUC   | F-Score  |
|---------------------|--------|----------------|----------|----------|----------|
| VGG19               | 10     | 0.407948       | 0.815694 | 0.133618 | 0.100799 |
| EfficientNetV2-B0   | 100    | 0.273317       | 0.770294 | 0.060965 | 0.015179 |
| Xception            | 5      | 0.396593       | 0.783322 | 0.131362 | 0.119081 |
| DenseNet-201 | 10     | 0.425520       | 0.806734 | 0.147263 | 0.116122 |


# Genre Predictions
![preds_g1](https://github.com/smellycloud/whatamilisteningto/assets/52908667/72c3a97e-2108-4d0d-b86b-1a2a8dfb81a3)
![preds_g2](https://github.com/smellycloud/whatamilisteningto/assets/52908667/a515c444-fc93-430a-aefc-b129652c6938)
![preds_g3](https://github.com/smellycloud/whatamilisteningto/assets/52908667/ce3b9ba7-74e8-4ea8-bbb8-2721b688a0bf)
![preds_g4](https://github.com/smellycloud/whatamilisteningto/assets/52908667/98f8cc90-6305-460e-aac7-9120dc9967ec)

# Mood/Theme Predictions
![preds_m1](https://github.com/smellycloud/whatamilisteningto/assets/52908667/dd1e0713-3ff7-44e9-b1c7-6cd34ba8e3ef)
![preds_m6](https://github.com/smellycloud/whatamilisteningto/assets/52908667/e2036ef0-4468-47da-8501-d845818da379)
![preds_m2](https://github.com/smellycloud/whatamilisteningto/assets/52908667/324f8de9-45ce-437d-b359-c89e810fd449)
![preds_m3](https://github.com/smellycloud/whatamilisteningto/assets/52908667/50766015-8262-4de1-b300-f37b84ba0f32)


