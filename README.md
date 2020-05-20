# Explaining Black Box Credit Risk Models
Extracting explainability from black box machine learning algorithms used to predict defaults 

### Project File Summary
- <b>README.md</b> - a summary of all contents in this repository.
- <b>/DataCleaning</b> - Notebook containing all code used for the data cleaning steps
- <b>/EDA</b> - Notebook containg all exploratory data anlysis and visualizations
- <b>/Preprocessing</b> - Jupyter Notebook containing all code used for data scaling and transformation
- <b>/Modeling</b> - Jupyter Notebook containing all code used for RandomForest, GradientBoost, AdaBoost, & BaggingClassifier code
- <b>/DeepLearning</b> - Notebook containing the neural network code
- <b>/Presentation</b> - A pdf of the powerpoint presentation

### Objective:
Since the financial crisis, it has become increasingly common for banks and lending institutions to use machine learning and AI to create complex credit risk models to sort loans or borrowers into "default" and "non-default" classes. This is normally done to calculate the "PD" (probability of default), a single stage within a multi-part process for modeling credit risk.

Whilst lenders have found that these models do well in calculating the probability of default, the lack of explainability that these black box models present has become increasingly problematic.

The cfpb (the regulatory body responsible for consumer protection in the financial sector) warned:

<i>"[Machine learning] advancements bring new risks, such as unintended side effects and greater potential for unlawful lending, discrimination, or misunderstanding by consumers."</i>

Similarly, FICO (a credit scoring company used by 90% of US lenders) outlined in 2020:
<i>"it is often the case that neither the trained model nor its individual predictions are readily explainable, but regulators and consumers demand explanations... Regulators require that financial institutions provide reasons to customers when taking “adverse action” (i.e. turning down a loan)"</i>

With this in mind, it is crucial that methods are established to explain what was previously considered "unexplainable." Fortunately, there has been rapid advancement within academia in the past 24 months   










### Project Goals:
- To be able to predict, following a car accident, whether or not a dangerous driver was the cause.
- To fulfill this objective, a classification model will be built that identifies whether a car accident was caused by criminal driving behavior, or non-criminal driving behavior.

### Methodology 

   -  Download and clean data from cityofchicago data portal.
   -  Bin primary_contributory_cause column into binary class: 'Criminal Driving' / 'Non-Criminal Driving'.
   -  Feature engineer additional columns.
   -  Perform Exploratory Data Analysis (EDA)
   -  Split the data into a training set and test set.
   -  Fit a logistic regression model to the training set.
   -  Perform hyperparameter tuning using RandomSearchCV / GridSearchCV.
   -  Test the optimized training model on the test data and evaluate score.
   -  Create a presentation to translate findings into actionable insights for the Chicago Police Department.
