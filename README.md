# CS5265-Foundations-of-Machine-Learning

# Capital Bikeshare Membership Prediction and Rider Preference

## Background
Bikeshare programs in large cities offer a cost-effective and environmentally friendly mode of transportation for citizens and tourists. The bike docks that are integral to these programs can collect several data points about each ride. Research has been conducted by the [Department of Transportation](https://data.bts.gov/stories/s/Summary-of-Docked-Bikeshare-Trips-by-System-and-Ot/7fgy-2zkf/) on the total usage of bikeshare programs and the membership numbers of the program, but extensive research into the differences between casual and member riders has not been conducted. I want to use the data provided by the bikeshare program in Washington, D.C., Capital Bikeshare, to build a model that can predict, based on the characteristics of a ride, whether that ride was made by a member (a rider with an annual subscription) or a non-member.

## Project Description
This project seeks to learn more about the behaviors of bikeshare users by creating a membership prediction model for Capital Bikeshare (CaBi). The analysis is conducted on user trip data from [August 2023 rides](https://s3.amazonaws.com/capitalbikeshare-data/index.html) provided by Capital Bikeshare. I anticipate that the results of the model will highlight key differences in ridership behaviors such as time of ride, bike type, and duration of ride that could help CaBi better serve its customers and maximize profitability.

For the above project desctiption, I would recommend including a short sentance or summary of how you would clean the dataset, if needed.

## Performance Metrics

Accuracy - Can the model correctly predict whether a ride was taken by a member or a casual rider? This will involve training against a dataset and comparing the model's determination against the data from Capital Bikeshare. Results will be recorded into a confusion matrix and classification accuracy will calculated using the function below.

| Actual | Predicted |
|---|---|
| Positive | True Positive (TP) | False Positive (FP) |
| Negative | False Negative (FN) | True Negative (TN) |

$$ Accuracy =\frac{TruePositive+TrueNegative}{𝑇rue𝑃ositive+𝐹alse𝑃ositive+𝐹alse𝑁egative+𝑇rue𝑁egative} $$

Characteristics - Which characteristics of a ride are more important for members? Using the model, is it possible to identify attributes of a ride that are more common among members? Knowledge of these attributes could help CaBi change its pricing model to provide the best service for its customers while also maximizing revenue.

Using machine learning this project will seek to find a more optimum pricing structure to increase CaBi. Additionally, my project will seek to find where CaBi should invest in infrastructure to maximize their most profitable stations and provide better service to their clients.
