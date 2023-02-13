# Final PROPOSAL
## What is your issue of interest (provide sufficient background information)?

Analysing and predicting Airline-delay for airlines for projecting whether a given flight will be delayed when given information about scheduled departure for the purpose of this project, it will just be used to write a story about flight delay experience across the listed airports.

## Why is this issue important to you and/or to others?

This issue is important for me as iam a victim of flight delays and understanding the Airlines-Delay dataset and developing a multiclass classifier to classify and predict future delays is really important in todays world.

## What questions do you have in mind and would like to answer?
Updated from draft proposal
- When is the best day of the week to fly to minimise delays?
- Most Popular Destination with Average Arrival Delays?
- Is there a better day to travel?
- Total Minutes Delayed by Airline?

## Where do you get the data to analyze and help answer your questions?

The Airlines-Delay  contains details of each flight which are both delayed and cancelled . The data consists of flight informations, airport details, Flight specifications etc.
The data source is mentioned below:
- https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7
- Size    : 687.28MB
- Rows    : 7.4M
- Columns : 36


## What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect to analyze?

- Airoplane delay is the unit of analysis(target) in this project. I will be analyzing roughly around 30 units for this project which are mentioned below.

## What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?

Cloumn name                  Data Type

- Year                          int64
- Month                         int64
- DayofMonth                    int64
- DayOfWeek                     int64
- DepTime                     float64
- CRSDepTime                    int64
- ArrTime                     float64
- CRSArrTime                    int64
- UniqueCarrier                object
- FlightNum                     int64
- TailNum                      object
- ActualElapsedTime           float64
- CRSElapsedTime              float64
- AirTime                     float64
- ArrDelay                    float64
- DepDelay                    float64
- Origin                       object
- Dest                         object
- Distance                      int64
- TaxiIn                        int64
- TaxiOut                       int64
- Cancelled                     int64
- CancellationCode             object
- Diverted                      int64
- CarrierDelay                  int64
- WeatherDelay                  int64
- NASDelay                      int64
- SecurityDelay                 int64
- LateAircraftDelay             int64
- Code                         object
- Carrier                      object
- delay                       float64
- dep_hour_standard           float64
- Date                 datetime64[ns]
- dep_hour_int                  int32
- Date_bin             datetime64[ns]


## What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?
- Handling missing values.
- checking for outliers.

Selecting the right model is a big challenge in machine learning. Since my problem comes under predicting the input variables, I am interested in using the below algorithms to achieve good performance.
- Decision tree
- Random forest
- Gradient Boosting Classifier

## How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?

- Based on the type of machine learning problem, classification, clustering and regression, various statistics and visualizations are generated including accuracy, confusion matrix, receiver operating characteristic (ROC) curve, cluster distortion, and means squared error (MSE). I would like to implement the avove stated model and based on the accuracy, recall and performance i would pick the best model that suits the data.

## What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?

- I would use the model that identifies the less frequently occuring classes more accurately compared to the complex algorithms. More over an algorithm with the best performing accuracy is also important.









