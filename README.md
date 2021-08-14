# Multi-class-text-classification-with-LSTM
This notbook describes a case study of multi-class text classfication on Consumer Complaint Database using LSTM (Long Short Term Memory) Deep learning model

**About Data**

1) Consumer Complaint Database: This dataset is provided publically by Consumer Financial Protection Bureau (CFPB). The Consumer Complaint Database is a collection of complaints about consumer financial products and services that CFPB sends to companies for response regularly. Those complaints are published after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first.

2) Original data (zip ~349 MB, extracted ~ 1.33 GB) is available in .csv at https://catalog.data.gov/dataset/consumer-complaint-database

**Brief About type of Features ( text + categorical feature + numerical feature)**
1) Data has text (the complaint narration) along with some categorical variables like location, city, mode of communication etc. The complaint narration feature is the main feature for us.

2) To learn how to use numerical features with LSTM, we will create our own numerical feature.

3) So final data will have text, categorical and numerical features, which makes it a very intersting and challenging problem.

**Task:**
In the task, given set of features (text-complaint, cateogrical features, numerical feature), we want to build a model to predict the category of the complaint.


**Architecture of the Model**
1) This is a multi-input model.
2) pre-trained glove vectors (100d) are used for the text features.

![image](https://user-images.githubusercontent.com/61385211/129458058-6bf620d2-2fd9-4af2-9007-b862aaf54452.png)

