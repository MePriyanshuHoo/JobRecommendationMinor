# Job Recommendation Portal

This is a job recommendation portal that uses machine learning algorithms to recommend jobs to users based on their input query. The portal takes in a dataset of over 27,000 jobs, preprocesses the data, and merges the relevant attributes to generate a single string attribute for each job. It then uses cosine similarity to calculate the similarity between the user's query and the string attribute of each job to recommend jobs to the user.

## Requirements

- Python 3.6 or higher
- Pandas
- Scikit-learn
- NLTK

## Installation

1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the `app.py` file to start the server.

## Usage

1. Open the portal in a web browser.
2. Enter a query in the search bar and submit.
3. The portal will recommend jobs based on the query.

## Methodology

The portal uses the following methodology:

1. Data preprocessing: The dataset is cleaned, null values are filled, and relevant attributes are selected.
2. Merging features: The position, company, city, employment type, job description, and attributes are merged into a single string attribute for each job.
3. Machine learning model selection: The RandomForestRegressor model is selected, and its target value is calculated using cosine similarity.
4. Splitting the dataset into training, validation, and testing sets: The dataset is split into three sets for training, validation, and testing purposes.
5. Tuning the hyperparameters of the model using cross-validation: The hyperparameters of the model are tuned using cross-validation to optimize its performance.
6. Evaluation metrics and performance analysis: Evaluation metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE) are used to analyze the performance of the model.
7. Limitations and challenges: The limitations and challenges of the project are discussed.
8. Conclusion and future scope: The project is concluded, and the future scope of the project is discussed.

## Credits

This project was created by Priyanshu Vishwakarma and Ayush Patel as part of Bachelor of Technology at IIIT Bhopal.

