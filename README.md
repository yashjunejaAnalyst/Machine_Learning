# Machine_Learning
INN GROUP OF HOTELS

**Project Title:**

Predictive Modeling of Hotel Booking Cancellations Using Machine Learning.

**Context:**

A significant number of hotel bookings are called off due to cancellations or no-shows. The typical reasons for cancellations include change of plans, scheduling conflicts etc. This is often made easier by the option to do so free of charge or preferably at a low cost which is beneficial to hotel guests but it is a less desirable and possibly revenue-diminishing factor for hotels to deal with. Such losses are particularly high on last-minute cancellations.

The new technologies involving online booking channels have dramatically changed customers’ booking possibilities and behavior. This adds a further dimension to the challenge of how hotels handle cancellations, which are no longer limited to traditional booking and guest characteristics.

The cancellation of bookings impact a hotel on various fronts:
1. Loss of resources (revenue) when the hotel cannot resell the room.
2. Additional costs of distribution channels by increasing commissions or paying for publicity to help sell these rooms.
3. Lowering prices last minute, so the hotel can resell a room, resulting in reducing the profit margin.
4. Human resources to make arrangements for the guests.

**Objective:**

To develop a machine learning model for INN Group of Hotels that accurately predicts hotel booking cancellations. The goal is to reduce financial losses, improve operational planning, and assist in creating strategic policies related to booking management, cancellation fees, and customer engagement.

**Approach:**

**Data Understanding & Preprocessing-**

Loaded and explored the dataset containing booking details.

Verified that there were no missing values.

Converted categorical variables into appropriate numerical formats using encoding.

Checked for multicollinearity using Variance Inflation Factor (VIF) and removed insignificant features.

**Exploratory Data Analysis (EDA)-**

Analyzed booking trends across months, market segments, and meal plans.

Investigated the impact of features like lead time, special requests, and repeated guests on cancellations.

Visualized key patterns using bar plots, histograms, and heatmaps.

**Model Building-**

Implemented Logistic Regression and Decision Tree Classifier.

Evaluated models using Confusion Matrix, Recall, Precision, Accuracy and ROC-AUC scores.

Applied pruning techniques to Decision Tree to reduce overfitting and enhance generalization.

**Feature Importance-**

Identified key predictors of cancellations: lead time, average room price, number of special requests, and booking channel (online).

**Model Selection-**

Selected pre-pruned Decision Tree as the final model due to its interpretability and balance between recall and precision.

**Outcome:**

Achieved a reliable prediction model with good performance on both training and test sets.

Identified actionable insights:

Bookings made >151 days in advance with no special requests are most likely to cancel.

Special requests and shorter lead times reduce cancellation probability.

Online bookings have a higher cancellation rate.
