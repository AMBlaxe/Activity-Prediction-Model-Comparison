# Activity Prediction Model Comparison

This project aims to compare the performance of various machine learning models in predicting human activities based on data collected from multiple sensors. The dataset used for this project is the MHEALTH (Mobile HEALTH) dataset.

## Dataset

The dataset comprises body motion and vital signs recordings for ten volunteers of diverse profiles while performing several physical activities. Sensors were placed on the subject's chest, right wrist, and left ankle to measure the motion experienced by different body parts, such as acceleration, rate of turn, and magnetic field orientation. The chest sensor also provides 2-lead ECG measurements.

[Dataset Link](https://www.kaggle.com/datasets/gaurav2022/mobile-health)

### Dataset Summary

- **Activities**: 12
- **Sensor devices**: 3
- **Subjects**: 10

### Activity Set

The activities include:
- Standing still (1 min)
- Sitting and relaxing (1 min)
- Lying down (1 min)
- Walking (1 min)
- Climbing stairs (1 min)
- Waist bends forward (20x)
- Frontal elevation of arms (20x)
- Knees bending (crouching) (20x)
- Cycling (1 min)
- Jogging (1 min)
- Running (1 min)
- Jump front & back (20x)

## Code

The code for this project is provided in the accompanying Jupyter Notebook file. It includes steps to load the dataset, preprocess the data, and train multiple machine learning models to compare their performance.

## Conclusion

This project demonstrates the application of various machine learning models to predict human activities using the MHEALTH dataset. The performance of each model is evaluated based on accuracy, precision, recall, F1 score, and confusion matrix.

Feel free to explore the dataset and experiment with the code to further improve the models or to try new techniques.
