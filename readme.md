# DataWhisperer - Interact With Your Dataset
<hr />

DataWhisperer is an open-source website tool developed in
Python. It is used to automate any classic ML task like 
regression, classification, clustering, dimensionality
reduction, or ranking. It can automate basic data cleaning
and preprocessing techniques, provide all required data
visualization column-wise, find the best model for the
dataset, train the model, and display the training and
testing results.

The most interesting feature in the website is the ability
to generate fundamental patterns and insights about the
dataset.

## Features
- Automate the process of data preprocessing.
- Perform basic visualizing tasks, to check for various feature properties.
- Find and select the best model for the task and the dataset.
- Train, test and validation the accuracy for the model.
- Find basic insights like linear seperability, feature importance.
- Advanced insights like hierarchies, associate rules, frequent item-set mining.

## Testing Datasets
All datasets used for testing this project have been acquired from the below listed sources:
- **Loan Approval Dataset:** [Loan Appoval Dataset - Kaggle](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)
- **Weather Prediction Dataset:** [Weather Classifcation Dataset - Kaggle](https://www.kaggle.com/datasets/nikhil7280/weather-type-classification)
- **HR Employee Analytics:** [HR Employee Analytics](https://www.kaggle.com/datasets/kmldas/hr-employee-data-descriptive-analytics)


## Usage

Here's how you can use the app to your benefit:

- **Upload A Dataset:** Upload any .csv or .xlsx file, check the site for limitations.
- **Data Visualization:** You can view basic statistics of your dataset, and also column-wise statistics.
- **Data Preprocessing:** My code can finally generate completely data preprocessed training, testing and validation data splits back.
- **Model Generation:** *This part takes a little time.* The website finds the best model for your dataset, and display's the training, testing and validation classification report, along with the confusion matrix.
- **Fundamental Patterns And Insights:** You can check for basic insights like feature importance, linear separability, and some advance insights like associate rules, itemset mining, and hierarchies usnig a dendrogram.

## Local Run

Here's how you can locally run the app. This app is currently under development. This way of  running the app is highly recommended, as the deployment has limited CPU and memory.

You need python > 3.10 to run the app.

- **Clone The Repo**: If you have git installed, cloning the repository can make this process easier.
- **Download Zipped Code:** A zip file can be downloaded in the code section of this page. Unzip the file, and you can see this repository's directory structure.
- **Install With Pip:** Navigate to the folder, and run the following command:

```python

pip install -r requirements.txt
```
- **Run Your App:** Now, you can run the app using the command:
```python
streamlit run DataWhisperer.py
```

## Future Scope
The future scope of this project is to bring in other classic ML problems like classification, regression and ranking.

Any contributions to its development are highly encouraged.

## Acknowledgements
This project is a complete brain child of 
Abhiram Mangipudi and Varshith Reddy. If you like the work, please consider leaving a star, or coming forward for contributions.

## License
This project is released under the [MIT License](./LICENSE)
