# Enhancing-Bankruptcy-Prediction
This study focuses on developing a predictive model using financial ratios and metrics to assess the likelihood of firm bankruptcy. It aims to leverage classification algorithms to predict a firm's collapse, enhancing decision-making processes for stakeholders and financial analysts.

## Business Problem
The primary business problem addressed by this study is the challenge of predicting firm bankruptcy accurately due to the imbalance in class distribution within the dataset. Firms that are close to bankruptcy are underrepresented, which can lead to a model biased towards predicting non-bankruptcy. This skews predictive performance and potentially leads to costly misclassifications.

## Methodology
The methodology encompasses several key components to build and refine the predictive model:
* Data Sampling: The study uses an oversampling technique to balance the class distribution, replicating instances of the minority class (bankruptcy cases) to improve model sensitivity towards predicting defaults.
* Variable Importance and Skewness Analysis: Key financial variables are analyzed for their predictive importance and skewness to enhance model accuracy. This involves identifying and prioritizing variables that significantly impact the target outcome.
* Data Preprocessing: Includes managing outliers through Median Absolute Deviation (MAD) and transforming variables (logarithmic and square transformations) to address skewness and enhance model stability and performance.
* Model Development: Various models like Gradient Boosting and High-Performance Neural Networks are employed to predict bankruptcy. These models are compared based on their Area Under the Receiver Operating Characteristic Curve (AUC) to select the best performer.
* Enhancing Model Accuracy: The study explores creating interaction terms and additional transformations to capture complex relationships and improve predictive accuracy.
* 
## Results and Conclusion
The project successfully develops a model with enhanced predictive accuracy for firm bankruptcy using advanced data mining techniques. Key outcomes include:
* Improved Class Balance: Oversampling effectively addressed the initial class imbalance, improving the sensitivity of the model to bankruptcy cases.
* Variable Optimization: By focusing on the most impactful variables and managing skewness, the model’s predictive accuracy was significantly boosted.
* Model Performance: Among the tested models, those incorporating sophisticated preprocessing and feature engineering demonstrated higher AUC values, indicating better predictive performance.
* Superior Model Selection: Among the models tested (Gradient Boosting, HP Neural, and Logistic Regression), Gradient Boosting was observed to have the lowest misclassification rate or Average Squared Error. Furthermore, this model achieved an impressive AUC score of 0.935, highlighting its robustness and accuracy in predicting firm bankruptcy.
