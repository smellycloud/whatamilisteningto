# whatamilisteningto
Music genre and theme classification using convolutional neural networks and transfer learning
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

![preds_g1](https://github.com/smellycloud/whatamilisteningto/assets/52908667/20bed742-0f17-47f4-b2bd-3ea2c83b255f)
![preds_g2](https://github.com/smellycloud/whatamilisteningto/assets/52908667/72805477-0861-4c8c-b1ec-1496a12bb153)
![preds_g3](https://github.com/smellycloud/whatamilisteningto/assets/52908667/23a4041d-ff0b-491e-be58-62d87575755a)
![preds_g4](https://github.com/smellycloud/whatamilisteningto/assets/52908667/c4dc7050-ab7f-48b9-ba6e-9e985130c7da)



# Mood/Theme Predictions

![preds_m1](https://github.com/smellycloud/whatamilisteningto/assets/52908667/756126f6-becc-4bcf-ac19-01851fa4551f)
![preds_m6](https://github.com/smellycloud/whatamilisteningto/assets/52908667/194c7bf0-771e-4d01-bc57-1840842fff52)
![preds_m2](https://github.com/smellycloud/whatamilisteningto/assets/52908667/2d482742-591b-4e72-b01c-2cc503d0fcbf)
![preds_m5](https://github.com/smellycloud/whatamilisteningto/assets/52908667/76f95294-f1b0-4edd-b91d-e6e21e8242e1)

