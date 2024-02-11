# Identifying Entities in Healthcare Data Assignment
Syntactic Processing - Assignment - Identifying Entities in Healthcare Data Assignment



## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)
* [Contact](#contact)


## General Information

‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

 

So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

eg:
“The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”


The following steps are performed:

- Process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
- Define the features to build the CRF model.
- Apply these features in each sentence of the train and the test dataset to get the feature values.
- Define the target variable and then build the CRF model.
- Perform the evaluation using a test data set.
- Create a dictionary in which diseases are keys and treatments are values.

## Technologies Used

- Python 3.9.13
- pandas 2.0.3
- scikit-learn 0.24.1
- sklearn-crfsuite 0.3.6
- spacy 3.7.2
- numpy 1.26.1


## Conclusion

The treatment for the disease 'hereditary retinoblastoma' is 'radiotherapy'.


## Contact

Created by [@omkar457] - feel free to contact us!
