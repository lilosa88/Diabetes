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

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2011.29.05.png" width="360" height="280">
 </p>


   - For old people (Age > 60 years old) : The rate of survival is 0.6947
   
  |   Sex   | Survival Rate |
  | ------- |:-------------:|
  |  female |     0.965517  |
  |   male  |     0.575758  |  


   - For young people (Age <= 20 years old) : There was only one pacient with this age, then we don't have enough statistics to make this analysis.

2. How does the sex influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.00.41.png" width="360" height="280">
 </p>
 
3. How does Polyuria influence the diabetes

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.03.29.png" width="360" height="280">
 </p>
 
 4. How does Polydipsia influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.04.16.png" width="360" height="280">
 </p>
 
 5. How does Sudden weight loss influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.46.35.png" width="360" height="280">
 </p>
 
6. How does Weakness influence the diabetes

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.47.00.png" width="360" height="280">
 </p>
 
7. How does Polyphagia influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.47.19.png" width="360" height="280">
 </p>
 
8. How does Genital thrush influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.47.43.png" width="360" height="280">
 </p>
 
9. How does Visual blurring influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.48.07.png" width="360" height="280">
 </p>
 
10. How does Itching influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.48.28.png" width="360" height="280">
 </p>
 
11. How does Irritability influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2013.06.57.png" width="360" height="280">
 </p>
 
12. How does Delayed healing influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.47.43.png" width="360" height="280">
 </p>
 
9. How does Visual blurring influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.48.07.png" width="360" height="280">
 </p>
 
10. How does Itching influence the survival rate

<p align="center">
  <img src="https://github.com/lilosa88/Diabetes/blob/main/images/Captura%20de%20Pantalla%202021-04-28%20a%20la(s)%2012.48.28.png" width="360" height="280">
 </p>
 

