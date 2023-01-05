# A Fault Detection Model with Imbalanced Data using Machine Learning and Deep Learning

This is my 2022-1nd Semeter Interdisciplinary Project.

### **📁 Resources** 
> - [Paper](./FaultDetection_Paper.pdf)

## Topic and Purpose of Research
In the recent years, as the amount of data increases, there has been a growing interest in the use of machine learning and deep learning in manufacturing industry and it is called smart manufacturing. One way in which machine learning and deep learning can be used in smart manufacturing is to **detect faults in the production process and take corrective action in real-time**. This can help to avoid costly production downtime and defects.

However, It is often difficult and expensive to collect data on defective products. The reason is that normal product data and defective product data must be obtained through experiments, and there are overwhelmingly many normal product data. So the data is often **unbalanced**, with a large number of positive examples and a small number of negative examples.

![Imbalanced](https://user-images.githubusercontent.com/93263147/210720387-94c18b36-89bb-47e4-8796-d5547410fd1e.png)


So in this research, we study how to apply machine learning and deep learning technique in real manufacturing data, especially for classification problem with imbalanced dataset. 

## Method
In this work, various method to oversample the minority class to detect defected product is proposed. Considering the imbalanced data, several machine learning and deep learning methods are selected and combined to enhance the performance of the fault detection model. 

**☑️ Model**
1. Random Forest
2. Deep Neural Networks(DNNs)
3. Deep Neural Networks with Weighted Loss Functions
2. Generative Adversarial Network(GANs)

**☑️ Oversampling Method**
1. Minority Over-sampling Technique(SMOTE)
2. Adaptive Synthetic Sampling Approach(ADASYN)


## Research Results
**💡 Performance comparison of methods**
![comparison](https://user-images.githubusercontent.com/93263147/210721369-3e9418f2-c0d7-41f5-ae8b-3a5cb5be94ab.png)

**💡 ROC curve of each model**
![ROC](https://user-images.githubusercontent.com/93263147/210721479-39b9bc6d-7ae1-4937-aca7-195fdcefcf48.png)

**AUC score of each model**
![AUC](https://user-images.githubusercontent.com/93263147/210721691-32ae569c-28a0-4084-9302-e2f193a22caa.png)

