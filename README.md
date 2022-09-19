# Sing Language Classification

Final Project Deep Learning Course

A link to the datasets on Kaggle: https://www.kaggle.com/datasets/datamunge/sign-language-mnist


The American Sign Language letter database of hand gestures represent a multi-class problem with 24 classes of letters (excluding J and Z which require motion)
Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions).
The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255.
Steps to follow:

run the models: KNN model, SVM mode, RANDOM_FOREST model, CNN model

The techniques I used and the success rates:

| Models | KNN Model | SVM Model | RANDOM FOREST Model | CNN Model |
| ------ | --------- | --------- |-------------------- |---------- |
|  score |   0.810   |   0.702   |        0.814        |   0.971   |

