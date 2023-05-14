# DATA_606 - Capstone Project
- Author : Sowjanya Deva
- Semester : Spring 2023
- Campus ID : vz50899
- Project Title : Flight delay prediction
# Project Title : Flight Delay Prediction
# Introduction
Flight delays cause inconvenience to passengers, impact airline operations, and result in financial losses. 
The objective is to build a machine learning model that can accurately predict the probability of flight delays based on various factors such as historical flight data, weather conditions, airport congestion, and airline-specific information.
By predicting delays in advance, airlines can proactively manage their resources, minimize disruptions, and improve customer satisfaction.
By predicting delays in advance, airlines can proactively manage their resources, minimize disruptions, and improve customer satisfaction.
# Motivation
Flight Delay has negative impact on business reputation and demand of airlines as well. Business Problem Overview
Develop a  business model to predict flight delays. Reduce further economic loss for airlines.Lessen inconvenience occurred to passengers.
# Moto
- The objective of flight delay prediction is to develop a reliable and accurate model that can forecast the likelihood and duration of flight delays.
- The model aims to utilize historical flight data, weather information, airport conditions, and other relevant factors to make predictions.
- The prediction model should consider various variables such as departure/arrival time, airline, aircraft type, route, and external factors like weather conditions.
- The goal is to provide timely and actionable information to airlines, passengers, and airport authorities to mitigate the impact of delays and improve overall travel experience.
# Data 
 - Dataset reference: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7
 - Ihave used 4 datasets for my analysis 
 - Airport dataset,carrier dataset,Air plane dataset and 2006 flight data 
 - Data cleaning and handeling is done on each dataseta and merged them accordingly 
 # Data cleaning
 - Checking for NULL values and droping the columns which are not useful for our analysis 
 - Removing redunet values 
 - Merging the cleaned data sets 
 # Exploratory Data Analysis
 <img width="1010" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/ba12125d-9cbb-4c4f-bee4-ea075ba181e9">
- The above EDA is to show routies per carrier 
- <img width="1010" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/ebf48f2f-2084-4a0f-914a-47a7d92b37a0">
- The above EDA is to check the average  Arrival delay per week
- <img width="1016" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/30068076-bdee-489d-a099-816103663db6">
- The above EDA is to check the Average Departure Delay 
- <img width="1016" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/4cdba794-7b6d-4941-b3e6-5740ee9730a0">
- <img width="1016" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/124c1250-0ea5-48f6-99fb-7e26618a0a72">
- The above shows Total flights per carrier 
- <img width="1016" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/fb63b755-f0b1-4e89-822a-bd8e6424efd6">
- Total Delays by carrier 
# Questions
- When is the best day of the week to fly to minimise delays?
- <img width="1016" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/f234544a-0a3b-4a6d-9d71-1c7124bb46eb">
- From the above analysis Saturday is the best day to fly
- <img width="1016" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/7f9ab8c3-2675-4fea-b845-087a3dffff30">
- The dashed line that you see on the plot corresponds to the average delay on arrival of the top 30 destinations. It is interesting to see how Atlanta, having such a high the number of landings, has a very low average delay with just over 10 minutes, whereas Newark, a not so popular destination, has such a high minute average delay. San Francisco is another destination that stands out with a high average delay as well as Orlando and New York
- Is there a better day to travel?
- <img width="1016" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/44c9c6a7-7d29-45f6-b97d-a23d09950ba4">
- It seesms like Last day of the month and middle of the month are the best days to travel 
# Prediction Modeling
- I have used three classification models 
- Decision Tree
- Random Forest
- RadientBoostingClassifier
 # Decision Tree
 - A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes.
 - The accuracy of this model is as follows
 - Prediction: 0.99938
- Accuracy: 0.99938
- Precision: 1.00000
- Recall: 0.99938
# Random Forest 
-Random forest is a commonly-used machine learning algorithm trademarked by Leo Breiman and Adele Cutler, which combines the output of multiple decision trees to reach a single result. Its ease of use and flexibility have fueled its adoption, as it handles both classification and regression problems.
- The accuracy of this model is as follows
- Prediction: 0.99548
- Accuracy: 0.99548
- AUC score: 0.99011
- Precision: 1.00000
- Recall: 0.99548
# RadientBoostingClassifier
- Gradient boosting is a machine learning technique used in regression and classification tasks, among others. It gives a prediction model in the form of an ensemble of weak prediction models, which are typically decision trees.
- The accuracy of this model is as follows
- Prediction: 0.96528
- Accuracy: 0.96528
- AUC score: 0.93156
- Precision: 0.96381
- Recall: 0.96528
# Comparison of Models
<img width="1016" alt="image" src="https://github.com/SowjanyaDeva/Sowjanya_Deva_Data_606/assets/103344156/4802017d-6f69-4af7-8766-93dde7ec7d46">
- For my analysis Decision Tree gives best Accuracy 
# Conclusion 
- Flight delay prediction is a valuable tool for airlines, passengers, and airports to minimize disruptions and enhance operational efficiency.
- Accurate predictions can help airlines optimize their resources, reduce costs, and improve customer satisfaction.
- Passengers can benefit from the ability to plan their journeys better, make alternate arrangements, or be informed about potential delays in advance.
- Further advancements in data analytics, machine learning, and real-time data integration can enhance the accuracy and reliability of flight delay prediction models.
- By leveraging predictive models and technologies, the aviation industry can work towards minimizing the occurrence and impact of flight delays, ultimately leading to smoother travel experiences for all stakeholders.






