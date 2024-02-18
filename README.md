Title: Predicting Falcon 9 First Stage Landing Success

Project Description:

This project aims to develop a machine learning model to predict the success of the Falcon 9 first stage landing, leveraging data from SpaceX launches. This information can be crucial for:

Cost Estimation: Accurately determining the launch cost, considering reusability advantages of SpaceX vs. competitors.
Competitive Bidding: Enabling other companies to assess their financial viability when bidding against SpaceX.
SpaceX Optimization: Providing SpaceX with insights for improving landing success rates and potential cost reductions.
Motivation:

Reduced Launch Costs: Predicting landing success helps estimate total launch costs, offering a significant competitive edge for SpaceX and valuable insights for potential competitors.
Space Exploration Enhancement: Improved landing technology fosters more sustainable and cost-effective space exploration.

Dataset: SpaceX launch dataset.

Data source: For this particular project I have used an API provided by the IBM Coursera Team.
Features: We took a subset of the API data which included the columns namely, 'rocket', 'payloads', 'launchpad', 'cores', 'flight_number', 'date_utc'. These columns were then used to get the features from the SpaceX API.
Data cleaning and preprocessing steps: Handling blank values, Standadization of the features, One Hot Encoding, etc were used in this process.

Methodology:

Machine learning models: Four models were used namely, Logistic Regression, SVC, Decision Tree Classifier and K Neighbors Classifier and the best performing model was selected among them.
Evaluation metrics:We used the metric - accuracy_score.
Model training and hyperparameter tuning: We did the tuning of hyperparameters using GridSearchCV for all the models.

Model performance: The best performing model in this case was Decision Tree Classifier which had an accuracy score of 0.83.
