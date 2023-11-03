# TermDepositPredictiveModel
Bank Marketing Dataset Analysis: A Python-based predictive modeling project utilizing a publicly available bank marketing dataset. Explore customer attributes and campaign outcomes to predict term deposit subscriptions. Implements machine learning algorithms for analysis and modeling

# Bank Marketing Dataset Analysis and Predictive Modeling
This repository contains a Python-based project focusing on Exploratory Data Analysis (EDA) and predictive modeling using the Bank Marketing Dataset. The dataset pertains to a Portuguese banking institution's direct marketing campaigns and aims to predict customer subscription to a term deposit.

Dataset Description
The dataset includes information collected during marketing campaigns via phone calls. It covers attributes such as client demographics, contact details, and previous campaign outcomes. The target variable is whether the client subscribed to a term deposit.

Number of Instances: 45,211 for bank-full.csv (4,521 for bank.csv)
Number of Attributes: 16 input attributes and 1 output attribute
Attribute Information: [Refer to Moro et al., 2011] for detailed information on attributes
Analysis Performed
Exploratory Data Analysis (EDA)
The project begins with a comprehensive EDA, examining the distributions, correlations, and patterns within the dataset. Visualizations and statistical analysis are used to gain insights into customer behavior and campaign outcomes.

Handling Imbalanced Data
As the dataset is imbalanced, techniques such as oversampling, undersampling, or the use of algorithms that handle class imbalance are applied to ensure the models' accuracy and reliability.

Predictive Modeling
Two machine learning algorithms are employed for predictive modeling:

Random Forest Classifier
Decision Tree Classifier
Both models are trained, optimized, and evaluated to predict customer subscription to a term deposit.

Repository Structure
notebooks/: Contains Jupyter notebooks detailing the EDA, model building, and evaluation.
data/: Holds the dataset files (bank-full.csv and bank.csv).

The project uses Python and the following libraries:

Pandas
NumPy
Matplotlib
Scikit-learn
Usage
To replicate the analysis:

Clone this repository.
Access the notebooks/ directory and open the Jupyter notebooks in a compatible environment.
Follow the step-by-step guidance within the notebooks to perform EDA and build predictive models.
Acknowledgments
This project utilizes the Bank Marketing Dataset made publicly available by S. Moro, R. Laureano, and P. Cortez. For detailed information, refer to [Moro et al., 2011].
