# Project-2
**SVM Model**
*Exploring the potetial of the SVM model*
  - Implemented and evaluated a Support Vector Machine (SVM) model, achieving near-perfect performance.
  - The confusion matrix showed only about 10 false positives out of 176,000 observations, with no false negatives.
  - Achieved a classification report with scores of 1 across all metrics, indicating exceptional model accuracy.
  - Extracted and analyzed feature importances using the model's coefficients, identifying 'URLSimilarityIndex', 'IsHTTPS', and 'LetterRatioInURL' as top influential factors.
  - Created a visual representation of feature importances to highlight the differential impact of various features on the model's predictions.
  - Observed the computational demands of using SVM on large datasets, particularly during the optimization of model parameters, which poses a significant challenge.
  - Concluded that while SVM models can classify complex data with high accuracy, the computational efficiency is a crucial factor to consider when choosing machine learning algorithms.
**Logistic Regression with Cost-Sensitive Learning**


**Random Forest Model- Marshall**
Dataset Overview
The dataset utilized for this project can be found at the UCI Machine Learning Repository under the Phishing URL Dataset (https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset). It comprises various features extracted from URLs, categorizing them into phishing and legitimate classes based on multiple characteristics.

Key Achievements

Random Forest Model: Utilized the Random Forest algorithm for its effectiveness in handling high-dimensional data and its ability to model complex interactions between features. The model was fine-tuned to optimize performance.

Feature Importance Analysis: Performed an analysis of feature importance that highlighted the most significant features in phishing URL detection. This insight aids in understanding the key characteristics of phishing URLs.

Model Deployment: The final model could be deployed as a prototype for real-time phishing detection, offering potential integration into cybersecurity systems for enhanced protection against phishing attacks.

Future Work
Exploring more sophisticated algorithms and ensemble methods to further improve the model's accuracy and reduce false positives.
Implementing real-time phishing detection in web browsers or email clients as an extension or plugin.
Continuous updating of the model with new data to adapt to evolving phishing tactics.

    data from https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset obtained, alraedy cleaned and ready for processing