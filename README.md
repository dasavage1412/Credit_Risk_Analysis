# Credit_Risk_Analysis
# Overview 
The purose of the project was to determine the factors that may or may not increase the risk of a loan. Using a combination of machine learning models I attemeted to determine if credit risk could be predicted. The data set comprised of credit card data from LendingClub.

# Results
* Naive Random Oversampling

![image](https://user-images.githubusercontent.com/77762219/125158020-12c5f400-e123-11eb-8cb4-63871127a021.png)

This model had a high degree of accuracy

* Smote Oversampling 

![image](https://user-images.githubusercontent.com/77762219/125158031-1e191f80-e123-11eb-990b-ce75b00829ae.png)

The results were simular to the Random Oversmapling

* Under sampling

![image](https://user-images.githubusercontent.com/77762219/125158037-25402d80-e123-11eb-84b8-663306ab8458.png)

Very balanced results with 64% accuracy and 65% sensitivity

* Combination of Over and under

![image](https://user-images.githubusercontent.com/77762219/125158039-2bcea500-e123-11eb-9358-01737d4d80fd.png)

This test seems to be the least balanced

* Balanced Random Forest

![image](https://user-images.githubusercontent.com/77762219/125158057-44d75600-e123-11eb-897a-5d9abcb55812.png)

Very high accuracy and F1 scores

* Easy Ensemble

![image](https://user-images.githubusercontent.com/77762219/125158063-4d2f9100-e123-11eb-8c43-759c652b7253.png)

95% accuracy and a super high F1 score

# Summary
Given the goals of the project we should move forward with the Easy Ensemble modling. It gave us the highest degree of accuarcy.
