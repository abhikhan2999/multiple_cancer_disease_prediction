# **Multi Class Disease Detection Using CNN**

 
 ### Prepared By : Dr Abhi Khan
 ### Dated : 25 Apr 2024
 ### Contact : abhikhan2999@gmail.com


 ## About the Dataset
  * The Dataset contains 10 different types disease images collected from Kaggle
  * The Dataset is further categorized into normal malignant and benign Images
  * The Labels are made and the data is prepared for the CNN Model
  
## Data Normalization and Preprocessing 
  * The data is normalized, scaled and batched for the Model Training 
  
## The CNN Model 
  * Sequential CNN Model is created 
  * 32 Batch Size are selected
  * Training of the Model is saved
  * The Model is trained for 10 Epochs 
  * Dropout Layer is added for better performance and avoid the overfitting 
  * Early stopping is applied for timely stopping of the model once acheives the results
  * The Model is evaluated on the Accuracy metric, classification report and confusion metric 

# **Results** 

### We have **acheived and accuracy score of 83%** Which can be increased by data augmentation or data increasing or increasing the epochs as well as checking different learning Rates.
