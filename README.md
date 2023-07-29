# TCS-iON-Internship-Project

Objective

To build a classification model that classifies the side effects of a particular drug by Age, Race and Gender.

Introduction

Machine learning (ML) is an innovative approach with extensive applications in classification, prediction and forecasting. Machine learning techniques are being used widely in areas such as medicine, engineering, education, manufacturing and production, forecast, traffic management, robotics etc. 
Machine learning has already shown its potential in pharma and medicine - finding ways to effectively collect and use lots of different types of data for better analysis, prevention, and treatment.

Drugs, an important way to treat various diseases, inevitably produce side effects bringing great risks to human bodies and pharmaceutical companies. How to predict the side effects of drugs is a perennial challenge in drug research. 

For this project, a dataset of WebMD sourced from Kaggle has been used. As this dataset lacked ‘Name’ and ‘Race’ features, the Name column was generated using Faker Python Module and Race column using Numpy and then concatenated with it. The master dataset featured 14 columns and 362806 rows.

The dataset used for classification include reviews, conditions etc. of different users of the drugs. These can be analysed to find side effects of drugs with the help of machine learning algorithms. Here, the machine is trained with data using various algorithms. After training, the machine predicts the output against unseen inputs. Supervised machine learning classifiers are used in building the model and fitting the data into the model. 

Conclusion


Created a dataset with 14 columns and 362806 rows. Performed various pre-processing steps and obtained a clean dataset for exploratory data analysis and modelling. Various visualizations were done on the dataset and selected a particular drug Lisinopril. 
By race, Whites topped in the usage of this drug with a higher female ratio. People in the age groups 55 to 64, 45 to 54 and 65 to 74 accounted for maximum usage of Lisinopril. Most users found Lisinopril as highly effective, especially females. Side effects of the drug proved race neutral. Genderwise, side effects proved extreme in females.
The best classification model was obtained by Linear Support Vector Machine (SVM). On performance evaluation, maximum accuracy of 62.82% has been achieved.

I chose to select the next best model, viz. Polynomial SVM for this task, as the feature importance analysis showed a decent importance for the desired features such as Age, Race and Gender.

