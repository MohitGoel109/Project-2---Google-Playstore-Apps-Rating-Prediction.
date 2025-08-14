# Project-2---Google-Playstore-Apps-Rating-Prediction.
This project focuses on predicting the ratings of Android applications listed on the Google Play Store based on various app attributes. The aim is to provide insights into the factors influencing app ratings and to build a predictive model that can estimate an app’s rating before its launch.

Dataset Features

The dataset contains detailed app information, including:

App Name & Category – Type of application (e.g., Tools, Games, Business).

Rating – Target variable (1.0 to 5.0).

Reviews – Number of user reviews.

Size – App size in MB.

Installs – Total downloads.

Type – Free or Paid app.

Price – App cost.

Content Rating – Age restriction level.

Genres – Specific app genres.

Last Updated – App update date.

Current Version & Android Version – Compatibility and release info.

Workflow

Data Cleaning – Handling missing ratings, removing duplicates, and formatting numerical fields like Installs and Price.

Feature Engineering – Encoding categorical variables, transforming textual data, and extracting numeric values from size and install counts.

Exploratory Data Analysis (EDA) – Visualizing relationships between features and ratings using histograms, scatter plots, and correlation matrices.

Model Training – Implementing regression models such as Linear Regression, Decision Tree, Random Forest, and Gradient Boosting.

Model Evaluation – Using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score to assess performance.

Technologies Used

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Environment: Google Colab

Insights

Analysis reveals that factors such as the number of installs, reviews, app category, and type significantly influence app ratings. Free apps with frequent updates and higher engagement tend to receive better ratings.

Applications

Helping developers optimize app features before release.

Assisting marketers in targeting high-rating potential categories.

Providing investors and product teams with insights into rating trends.

This project demonstrates a complete end-to-end machine learning pipeline — from raw data preprocessing to deploying a rating prediction model — offering valuable business and development insights for app creators.
