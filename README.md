# DESIGN AND ANALYSIS OF AN EDUCATIONAL RECOMMENDER  SYSTEM TO ENHANCE STUDENTS LEARNING OUTCOMES

## Description:
This GitHub repository hosts the codebase for the "Design and Development of an Effective Technique for Predicting the Performance of Students in the Higher Education System." The project leverages the Oulad dataset and employs an ensemble learning approach, specifically the BalancedRandomForestClassifier, to enhance the accuracy of student performance prediction.

## Key Features:

- Dataset: The `Oulad dataset` is utilized, offering a rich source of information for training and evaluating the performance prediction model.
- Ensemble Model: The core predictive model is built on the BalancedRandomForestClassifier, a powerful ensemble learning technique known for its ability to handle imbalanced datasets effectively.
- Balancing Technique: The `Synthetic Minority Over-sampling Technique (SMOTE)` is employed to address class imbalance, ensuring fair representation of diverse student performance levels.
- Toolset: The project is developed using Python, with prominent libraries such as scikit-learn, Pandas, and NumPy for data manipulation, preprocessing, and model building.
= Model Comparison: Various models, including `Artificial Neural Networks (ANN)`, were experimented with during the development phase. The `BalancedRandomForestClassifier` emerged as the top-performing model, surpassing others in predictive accuracy.

### Tools Used:

-- Python
-- scikit-learn
-- Pandas
-- NumPy

## Methodology:

Data Preprocessing: Comprehensive data cleaning and preprocessing to ensure the dataset's suitability for model training.
Model Development: Employed various models, including ANN, and fine-tuned parameters to optimize predictive performance.
Ensemble Learning: Implemented the `BalancedRandomForestClassifier` to harness the power of ensemble learning for robust performance prediction.
Class Imbalance Mitigation: Utilized `SMOTE` to address imbalances in the dataset, enhancing the model's ability to generalize across diverse student performance categories.
