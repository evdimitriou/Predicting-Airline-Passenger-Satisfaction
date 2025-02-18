# **Predicting Customer Satisfaction**

This report focuses on analyzing airline passenger satisfaction using data mining techniques. It utilizes a dataset from a corporate survey involving 129,880 customers, examining various factors such as gender, age, travel type, and service satisfaction levels. The report discusses data preprocessing, feature selection, and the application of predictive models, specifically Gaussian Naive Bayes and Logistic Regression. It evaluates model performance through accuracy and ROC-AUC scores, concluding that both models perform well, with Logistic Regression slightly outperforming Gaussian Naive Bayes in predicting customer satisfaction.

## Table of Contents
- [Data Contents](#data-contents)
- [Data Understanding](#data-understanding)
- [Data Mining and Prediction Design](#data-mining-and-prediction-design)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion](#conclusion)


## Data Contents

The dataset consists of two files: `train.csv` and `test.csv`, which contain demographic and satisfaction-related information from 129,880 airline passengers. Key features include:

| Feature                           | Description                                                               |
|-----------------------------------|---------------------------------------------------------------------------|
| **Gender**                        | Passenger gender (Female, Male)                                           |
| **Customer Type**                 | Type of customer (Loyal, Disloyal)                                        |
| **Age**                           | Passenger age                                                             |
| **Type of Travel**                | Flight purpose (Personal, Business)                                       |
| **Class**                         | Travel class (Business, Economy, Economy Plus)                            |
| **Flight Distance**               | Distance of the flight                                                    |
| **Inflight Wifi Service**         | Wifi satisfaction (0: Not applicable; 1-5)                                |
| **Departure/Arrival Time**        | Convenience of departure/arrival time satisfaction                        |
| **Ease of Online Booking**        | Online booking satisfaction                                               |
| **Gate Location**                 | Gate location satisfaction                                                |
| **Food and Drink**                | Food and drink satisfaction                                               |
| **Online Boarding**               | Online boarding satisfaction                                              |
| **Seat Comfort**                  | Seat comfort satisfaction                                                 |
| **Inflight Entertainment**        | Entertainment satisfaction                                                |
| **On-board Service**              | Onboard service satisfaction                                              |
| **Leg Room Service**              | Legroom service satisfaction                                              |
| **Baggage Handling**              | Baggage handling satisfaction                                             |
| **Check-in Service**              | Check-in service satisfaction                                             |
| **Inflight Service**              | Inflight service satisfaction                                             |
| **Cleanliness**                   | Cleanliness satisfaction                                                  |
| **Departure Delay in Minutes**    | Minutes of departure delay                                                |
| **Arrival Delay in Minutes**      | Minutes of arrival delay                                                  |
| **Satisfaction**                  | Overall satisfaction (Satisfied, Neutral, Dissatisfied)                   |


## Data Understanding
The data is processed using Python libraries such as Pandas and NumPy. Initial steps include:
- Exploratory Data Analysis (EDA)
- Data cleaning and transformation
- Handling missing values

## Data Mining and Prediction Design
The project employs data mining techniques to uncover relationships between features and customer satisfaction. The following methodologies are utilized:
1. Correlation Analysis
2. Data Visualization
3. Principal Component Analysis (PCA)

## Models Used
Two predictive models are implemented:
1. **Gaussian Naive Bayes (GNB)**
2. **Logistic Regression**

Both models are trained on the processed training dataset and evaluated on the test dataset.

## Evaluation Metrics
The performance of the models is assessed using:
- Accuracy Score
- ROC-AUC Score
- Classification Report
- Confusion Matrix
- ROC-AUC Curve

## Conclusion
The Logistic Regression model slightly outperforms the Gaussian Naive Bayes model in predicting customer satisfaction. Key features influencing satisfaction include the type of travel and customer loyalty status.

## Getting Started
To run this project, ensure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Clone the repository and run the Jupyter Notebook to explore the analysis and predictions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

