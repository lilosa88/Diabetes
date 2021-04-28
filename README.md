# Case study of the rate of diabetes

# Objective

This has been collected using direct questionnaires from the patients of Sylhet Diabetes Hospital in Sylhet, Bangladesh and approved by a doctor. This dataset contains the sign and symptpom data of newly diabetic or would be diabetic patient. This dataset is obtained from [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.). The objective is to build a predictive model that predicts if a pacient is prone to be diabetic or not using the dataset. 

# Code and Resources Used

- **Phyton Version:** 3.0
- **Packages:** pandas, numpy, sklearn, seaborn, matplotlib

# Data description

For each passenger(i.e. each Passenger Id) the following information is given:

- **Age:** the age of each pacient.
- **Gender:** Male or Female.
- **Polyuria:** It is excessive or an abnormally large production or passage of urine1. The options are Yes or No.
- **Polydipsia:** It is excessive thirst or excess drinking. The options are Yes or No.
- **Sudden weight loss:** The options are Yes or No.
- **Weakness:** The options are Yes or No.
- **Polyphagia:** It is an abnormally strong sensation of hunger or desire to eat often leading to or accompanied by overeating. The options are Yes or No.
- **Genital thrush:** It is a common condition caused by a type of yeast called Candida. The options are Yes or No.
- **Visual blurring:** The options are Yes or No.
- **Itching:** The options are Yes or No.
- **Irritability:** The options are Yes or No.
- **Delayed healing:** The options are Yes or No.
- **Partial paresis:** The options are Yes or No.
- **Muscle stiffness:** The options are Yes or No.
- **Alopecia:** The options are Yes or No.
- **Obesity:** The options are Yes or No.
- **Class:** If the diabetes is positive or negative

# Data exploration
In order to understand what influence the diabetes rate we took a look at the relation that each feature has on it.

1. How does the age influence the survival rate

