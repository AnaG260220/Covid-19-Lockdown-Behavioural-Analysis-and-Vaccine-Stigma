# Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma

COVID-19, The global pandemic affects different people in different ways. Most infected people will develop mild to moderate illness and recover without hospitalization. 

As part of this case study, we collected data regarding people's status of vaccination and their behaviour towards the situation. To analyse this, we made use of Logistic Regression, Decision Tree, Random Forest, K-Neighbors algorithm to create an ensemble algorithm from using a combination of these models and have achieved a 58% combined accuracy in predicting the vaccination status of different people provided the parameters. We also judge whether the risk of contracting covid by a person is high depending on their social behavior with 97% accuracy.

### Questions visualized:
●	Represent people from different age groups who have answered this survey.
●	Analyze which age group has the least number of vaccinations done.
●	State the count of respondents having medical insurance?
●	Is medical insurance related to contracting COVID?
●	What is the major motive to get vaccinated?
●	Does the cost of a vaccine prevent people from taking it?
●	Is there a false information trend created due to excessive fear of COVID which leads to people not knowing basic facts like the incubation period of covid is 2-14days?
●	Compare the vaccination status for males and females
●	Are vaccinated people taking the precaution of wearing masks in public places?
●	How is vaccination impacting the usage of public transportation?
●	What is the perceived threat level inside the house?  

### For Analysis #1: Predicting a person’s vaccination status from:
Dependent variable:
Vaccination Status

Independent variables:
Gender                                                                 
Age Group                                                               
Religion                                                                
Living                                                                  
Education                                                               
Employment Status                                                       
Which of the following best describes your current working industry?    
Medical Insurance                                                       
COVID                                                                   
Deaths seen                                                             
Reasons                                                                 
High Vaccine cost                                                       
False News                                                              
Incubation period

### Analysis 2# Predicting the risk of a person contracting covid from their social behaviour
Independent Variables
Likeliness of Wearing a Mask in public after vaccination
Likeliness of Wearing a Mask in a work setting outside the home
Likeliness of Wearing a Mask while using public transportation
Likeliness of Wearing a Mask while going for a walk in your neighborhood
Likeliness of Wearing a Mask while shopping inside a store
Likeliness of Wearing a Mask Inside a friend’s house
Vaccination Status

Dependent Variable
Risk of Contracting COVID

### Sample of dataset
data.csv
 
vaccine.csv
 
### Algorithms Used:
1] Logistic regression
Logistic regression is a supervised classification algorithm that only takes discrete values as input. The model it creates is regression-based and predicts if the probability of a given data belongs to 1 or 0. These values can be referred to as any of the categories used to classify data.
2] Decision Tree
Decision Trees are a type of Supervised Machine Learning (that is what the input is and what the corresponding output is in the training data) where the data is continuously split according to a certain parameter.
3] Random Forest
Random forest, or random decision forest, is a supervised machine learning algorithm that relies on ensemble learning for classification and regression. It is a flexible, straightforward algorithm that produces excellent results most of the time (even without hyper-parameter tuning). It is also one of the most used algorithms.
4] K neighbors:
The k-nearest neighbours (KNN) algorithm is a supervised machine learning algorithm.
KNN assumes that similar things exist in close proximity. In data science, it implies that similar data points are close to each other. KNN uses similarity to calculate the distance between points on a graph.
5] Ensemble Method:
In statistics and machine learning, ensemble methods use multiple learning algorithms to obtain better predictive performance than could be obtained from any of the constituent learning algorithms alone.

IMPLEMENTATION:

![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/77450404-c2f8-4122-9ab1-8f5a2c3cdb8c)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/7c7c3fc6-c138-46c2-af52-e3562536ac42)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/91aa57a0-372c-4a9e-9a7b-01302717d01b)


### Data cleaning (Finding out null values)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/28e0dae0-a47a-47a8-8ed7-7a332b459d2e)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/07580622-5e97-4aa4-bff4-562482173048)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/4ecc1030-0fed-4807-8965-a0c5f1a800fc)

### Data pre-processing (Systematic treatment of null values)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/f666391c-0bda-4149-ae39-b1b9456bd9ad)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/0f046fe5-0885-4ba7-a4c4-2a3e8c158a34)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/60817682-49f6-40f5-931c-88d5d986c68d)

### Data Visualization and Analysis
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/9aaf72aa-e3ac-4671-9e9c-fc8f3d4fec21)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/e531f5fe-03ae-4079-bc3f-31b945d01887)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/8b7edbbb-b05b-4964-91ab-693ac1285eac)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/7972299b-132e-4b09-b60e-e8d6acc5991d)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/2c164dd8-acad-4300-bc40-49f0af3b2206)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/54ab490b-12a6-4161-a9b6-48c08883ce65)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/9a7a2568-575f-47a5-9677-f6e5ce8b0ccc)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/5c306bcc-c37e-4ce3-8598-da1add7f5597)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/bd759d11-98a1-4e5f-afa8-e03c21b2c4af)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/17f0c335-bc27-4b67-9f95-f98aefedf524)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/fe301ebf-9998-4993-b8b6-db3f4c4f35bf)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/2d008537-9c1c-46d8-982d-936478d9f3e8)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/5cec5b85-9103-4e1c-8238-8b4c8a7e934d)

## Algorithms:

## 1. Decision Tree
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/f251a931-b670-4a03-94dd-e1b5d05d3d15)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/18fa8e82-7c50-4ee9-a816-e09e648ed392)

## 2. KNeighbours

![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/42ae1c12-2134-4a18-8b25-91636a13e199)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/5135904e-b6ec-4ccd-a722-b8b4feed4412)

## 3. Logistic Regression
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/d1cf7054-b1cb-426a-8e2d-d44b78029830)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/cd2f2ad1-7ea1-4db1-86e3-b4accb0c3b10)

## 4. Random Forest
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/5133d19d-a98d-451b-8504-2fa2798e18c2)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/a9bccc0b-2687-47d9-b37d-a4543d211011)

### Homogenous Ensemble Method

![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/c8417db8-357f-459d-a936-a4392ed034c7)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/90a742d9-65de-4ebd-90c7-5e2698a0e776)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/4ba96eaa-ee0e-41eb-949d-db780d8b08d1)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/7374d803-9edb-462b-8dc7-08715c306353)
 
### Conclusion:
We can safely predict with 64% accuracy the vaccination status of people with Logistic Regression and a combined 58% with the ensemble method.

### Impact of vaccination on social behaviour
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/74e31ed5-393c-4d75-9fd7-64d24cb771a4)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/6269733c-e124-426f-a8af-fcd2e4f3911a)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/d1511fcd-bbdd-42ae-b025-92804882d5f8)
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/32dbc484-13a1-4ac5-bded-a2604afd8bad)

### Logistic Regression
![image](https://github.com/AnaG260220/Covid-19-Lockdown-Behavioural-Analysis-and-Vaccine-Stigma/assets/61514957/d76c59f1-af88-4aef-8bae-ff397d158e2f)

### Conclusion:
Using logistic regression, we can predict the possibility of a person contracting Covid -19 on the basis of their social behavior with an accuracy of 97.77%



