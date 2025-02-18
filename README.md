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

- **Gender**: The gender of the passengers (Female, Male)
- **Customer Type**: The type of customer (Loyal Customer, Disloyal Customer)
- **Age**: The actual age of the passengers
- **Type of Travel**: The purpose of the flight (Personal Travel, Business Travel)
- **Class**: The class of travel on the airplane (Business, Economy, Economy Plus)
- **Flight Distance**: The distance of the flight
- **Inflight Wifi Service**: Satisfaction level with the inflight wifi service (0: Not applicable; 1-5)
- **Departure/Arrival Time Convenient**: Satisfaction level with the convenience of departure/arrival time
- **Ease of Online Booking**: Satisfaction level with the ease of online booking
- **Gate Location**: Satisfaction level with the gate location
- **Food and Drink**: Satisfaction level with food and drink
- **Online Boarding**: Satisfaction level with online boarding
- **Seat Comfort**: Satisfaction level with seat comfort
- **Inflight Entertainment**: Satisfaction level with inflight entertainment
- **On-board Service**: Satisfaction level with onboard service
- **Leg Room Service**: Satisfaction level with legroom service
- **Baggage Handling**: Satisfaction level with baggage handling
- **Check-in Service**: Satisfaction level with check-in service
- **Inflight Service**: Satisfaction level with inflight service
- **Cleanliness**: Satisfaction level with cleanliness
- **Departure Delay in Minutes**: Departure delay in minutes
- **Arrival Delay in Minutes**: Arrival delay in minutes
- **Satisfaction**: Airline satisfaction level (Satisfied, Neutral, or Dissatisfied)

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

