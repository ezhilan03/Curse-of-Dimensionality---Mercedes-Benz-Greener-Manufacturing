# Curse-of-Dimensionality---Mercedes-Benz-Greener-Manufacturing

Project Description
Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for significant automotive innovations, including the passenger safety cell with crumple zone, the airbag, and intelligent assistance systems. Daimler’s Mercedes-Benz cars are leaders in the premium car industry with a huge selection of features and options, allowing customers to customize their Mercedes-Benz to their preferences.

To ensure the safety and reliability of each unique car configuration before they hit the road, Daimler’s engineers have developed a robust testing system. Optimizing the speed of this testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach. The challenge was to reduce the time cars spend on the test bench, thus speeding up testing and reducing carbon dioxide emissions.

Dataset
The dataset provided for this competition contains different permutations of Mercedes-Benz car features.

The project achieved the following results:

Improvement in Prediction Accuracy: 35%
Average R-Squared (R²) Score: 0.7 across all models
Final Model Performance:
Mean Squared Error (MSE): 0.14
Mean Absolute Error (MAE): 0.24
These results indicate a significant enhancement in prediction accuracy and efficiency of the testing process, contributing to more eco-friendly car manufacturing practices.

Technologies Used
Programming Languages: Python
Libraries: NumPy, Pandas, Matplotlib, Seaborn, Plotly, Scikit-learn
Modeling Approach
Data Preprocessing:

Load and clean the dataset.
Handle missing values and encode categorical features.
Feature Engineering:

Create new features based on domain knowledge.
Perform feature selection to reduce dimensionality.
Model Building:

Train multiple machine learning models including Random Forest, XGBoost, Lasso Regression, SVM, and Gradient Boosting.
Perform hyperparameter tuning using grid search and cross-validation.
Model Optimization:

Implement a stacking ensemble technique with Random Forest as the meta-learner.
Evaluate the final model on the test dataset.
Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

Citation
@misc{mercedes-benz-greener-manufacturing,
    author = {Alexander Novy, CH1Mercedes, Christian Drescher, Christian Pfaundler, KOESIM, Will Cukierski},
    title = {Mercedes-Benz Greener Manufacturing},
    publisher = {Kaggle},
    year = {2017},
    url = {https://kaggle.com/competitions/mercedes-benz-greener-manufacturing}
}
