# Human-activity-recognition

 # Description
 These days Smartphones have become an integral part of our life. We cannot assume our life without a mobile phone. Since, the advent of Smartphones, a revolution has been created in the mobile communication industry. Smartphones are not just restricted for calling these days. Infact, they are more often used for entertainment purpose.

Smartphone manufacturing companies load Smartphones with various sensors to enhance the user experinece. Two of the such sensors are Accelerometer and Gyroscope. Accelerometer measures acceleration while Gyroscope measures angular velocity.

Here, we will try to use the data provided by accelerometer and gyroscope of Smartphone to classify the activity which a Smartphone user is performing.

# Business Problem
Work-flow is as follows:

Domain experts from the field of Signal Processing collects the data from Accelerometer and Gyroscope of Smartphone. They break up the data in the time window of 2.56 seconds with 50% overlapping i.e., 128 reading

They engineered 561 features from each time window of 2.56 seconds.

By using either human engineered 561 feature data or raw features of 128 reading, our goal is to predict one of the six activities that a Smartphone user is performing at that 2.56 Seconds time window.

# Problem Statement
By using either human engineered 561 feature data or raw features of 128 reading, our goal is to predict one of the six activities that a Smartphone user is performing at that 2.56 Seconds time window.

# Data Source
Data is downloaded from following source: https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones
