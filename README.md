# Early-Detection-of-Chronic-Kidney-Diseases-future-complications-
<br>
Chronic Kidney Disease (CKD) is a long term condition where the kidneys don‟t work as well as they should. It involves a gradual loss of kidney function. Kidneys are one of the most important organs in the human body. The main job of kidney is to cleanse the blood of toxins and transform the waste into urine.
CKD impairs the ability of the kidneys to properly filter the blood. Due to this, the extra fluid and blood waste build up in the body and may result in various health issues like heart diseases and strokes. The more frequent causes of CKD in adults include diabetes and high blood pressure. Heart Disease, obesity, a family history of CKD, genetic renal problems, prior kidney injury, and advanced age are additional risk factors. Advanced Chronic Kidney Disease can cause dangerous levels of toxic fluids, electrolytes and wastes in the body. As a result, once the symptoms become more visible, the condition of the disease has already advanced and thus worsened.
Along with the basic dysfunction of the kidney, CKD can also cause several complications of its own such as Anemia, Pancreatic Cancer as well as diabetic foot (Since most of the patients who have CKD are diagnosed with diabetes).
Anemia is one of the most common complications for CKD. Anemia is simply a condition where the person has low hemoglobin levels in his/ her body. Due to which, the body parts get very less amount of blood for them to function properly. Since a person suffering through CKD can‟t get his/ her blood purified, wastes start building inside the body. Anemia is less common in the early stages of kidney diseases but grows as the condition is left untreated. Thus, Anemia is mostly common with the people who have been diagnosed with advanced CKD. It is estimated that more than 37 million American Adults might have CKD with more than 1 out of every 7 people has anemia.
The last complication which we aimed at predicting was the diabetic foot. Since it has been observed that most of CKD patients have already been diagnosed with Diabetes, a diabetic foot is pretty common development as the CKD advances. About 19-34% of patients suffering from Diabetes suffer from a Diabetic Foot.
We thus propose a model which would help in early detection of the CKD using Machine Learning models using authentic datasets. We also aim at detecting the complications which are associated with CKD.
This could be done with the help of machine learning algorithms such as Artificial Neural Networks (ANNs), Random Forests, K-Nearest Neighbors (KNNs) as well as Convolutional Neural Networks (CNNs) which were specifically used to make predictions on the image based datasets.
<br>
<br>
METHODOLOGY
<br>
<br>
• Step 1: The first step to any machine learning project is understanding the problem statement and realize what we are trying to predict or analyses. In our project we have realized that we need to predict the presence of Chronic Kidney Diseases (CKD).
<br>
• Step 2: The second step is to collect and gather the data which would be required. This step is also common known as data acquisition. The data can be obtained through several open source websites and laboratories which voluntarily provide authentic datasets. An example of such a website is Kaggle which has a huge community and datasets for machine learning enthusiasts.
<br>
• Step 3: The data obtained now needs to be thoroughly inspected. This is a very important step since the data we gather is often raw and needs an immense cleaning. The entire procedure of cleaning the data consists of removing any null values by either completely removing them from the data set or by filling those with an average on the entire column, whatever suits the situation. The dataset can often also be skewed and thus would require us to use techniques such as SMOTE which has been explained in the above sections of this report. We may also need to understand if the dataset has any features or columns which do not affect the target column (Column we are attempting to predict). We can then remove all the columns which pose no correlation with the target column and thus make our model more efficient and effective. Since the Machine Learning algorithms only recognize integers or float based values in the dataset, all the features having string values would need to be converted into the compatible formats of integers or floats. This would be done with the help of hot-encoding technique which can be done using the pandas library. We also need to use the Min Max Scaler in order to Scale the dataset in the range of 0-1 so as to make sure all the columns are treated accordingly and not only on their numerical values.
<br>
• Step 4: Once the data has been thoroughly cleaned, it is ready for model training. However, before we proceed with the model training, we would have to split the dataset into train and test subsets. The basic thumb rule to split the dataset is that 75% of the dataset goes for training while the remaining 25% would be used for testing. These parameters can be altered according to our liking and the dataset and can also impact the overall accuracies which would be obtained once the model would be trained.
<br>
• Step 5: Now that the dataset has been split, we can proceed with the algorithm selection which is then followed by building the model architecture.
<br>
•Step 6: Once the model has been trained it can be validated using the test subsets of the dataset, and predictions can be made on the X_test array. These predictions would then be compared to the y_test component which would help us to derive to the overall accuracy.
<br>
• Step 7: We use classification reports to understand the overall accuracies and other parameters such as f1 score, precision and recall.
<br>
• Step 8: Save the trained model or debug.
<br>
<br>
CONCLUSION
<br>
<br>
The main goal for this project was to develop predictive models which would be able to predict the likeliness of a person to suffer from Chronic Kidney Diseases (CKD) before it worsens. After successfully developing a cluster of 3 predictive models, we can now predict the likeliness of a person to suffer from CKD before it becomes deadly.
Along with these 3 models which focused on only predicting the likeliness of presence of CKD causing inhibitors, we also developed 2 more predictive models which aimed at detecting the chances of developing serious complications such as Anemia and Diabetic Foot which are all very common and deadly for a person suffering from CKD.
All the models which were developed had a really good accuracy scores and can thus be used even on the unseen data in the real world.
In the next section of the report, we have shown how the models work on unseen data and by taking input from the user.
The table 8.1 shows the final accuracies that were obtained for all the models.
