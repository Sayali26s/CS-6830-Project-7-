# CS-6830-Project-7-
Logistic Regression & Support Vector Machines
Code | Presentation						           By- Sayali Sali \
Introduction
Our analysis aims to explore and analyze datasets containing mushroom attributes to predict whether a mushroom is edible or poisonous. Understanding the characteristics that distinguish edible mushrooms from poisonous ones is crucial for various stakeholders, including mushroom hunters, consumers, and health professionals.

Project Mushroom
Dataset
We begin our analysis by examining a dataset containing attributes of different mushrooms, including features like cap shape, cap surface, cap color, odor, gill attachment, gill spacing, gill size, gill color, stalk shape, stalk root, stalk surface above ring, stalk surface below ring, stalk color above ring, stalk color below ring, veil color, ring number, ring type, spore print color, population, and habitat. The target variable is the class of mushroom, which can be either edible or poisonous. The dataset has been cleaned and preprocessed, including handling missing values by imputing mode values and encoding categorical variables.


Mushrooms displaying numerous and abundant population and purple or green cap color mushrooms are edible, though the data points are few. Mushrooms with purple, orange, yellow, and buff spore print colors are edible, except for green spore print mushrooms, which are typically poisonous. Odor serves as a significant indicator of mushroom class, except for mushrooms with no smell. Mushrooms with no rings are generally poisonous, and those with two rings are mostly edible. 
Analysis Techniques and Results:
We explored logistic regression and Support Vector Machines (SVMs) as potential techniques for predicting mushroom edibility. Both techniques are well-suited for binary classification tasks and are commonly used in predictive modeling applications.
Analysis 1: Logistic Regression
We encode categorical features: ring type, spore print color, population, stalk color above ring, odor, and cap-color using one-hot encoding and applied logistic regression to predict mushroom classes. The precision, recall, and F-score for edible mushrooms were 0.991, 1.0 and 0.995, respectively, while for poisonous mushrooms, they were 1.0 ,0.989 and 0.994 respectively. These results indicate high predictive accuracy for both classes.
Analysis 2: SVM Linear
We employed a linear SVM classifier to classify mushrooms based on their attributes. The precision, recall, and F-score for edible mushrooms were 0.994, 1.0, and 0.997, respectively, and for poisonous mushrooms, they were 1.0, 0.993, and 0.997, respectively. The linear SVM achieved higher accuracy than logistic regression.
Analysis 3: SVM Polynomial
We applied SVM with polynomial kernel (degree=2) to the dataset. The precision, recall, and F-score for edible mushrooms were 0.996, 1.0, and 0.998, respectively, and for poisonous, they were 1.0, 0.996, and 0.998, respectively. The polynomial SVM demonstrated superior performance compared to linear SVM and logistic regression. The RBF SVM achieved comparable results to the polynomial SVM.
We utilized Support Vector Machines to visualize decision boundaries for a mushroom dataset. We encoded categorical features, such as odor and spore print color, and trained an SVM model with a polynomial kernel of degree 2. The resulting decision boundary effectively separates the mushroom classes (edible and poisonous) based on these two features.





