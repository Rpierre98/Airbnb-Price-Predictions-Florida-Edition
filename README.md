# Airbnb-Price-Prdeictions-Florida-Edition
"The "Airbnb Price Predictions Florida Edition" is a data science capstone project aimed at predicting the daily prices of Airbnb listings in Florida. With the increasing popularity of Airbnb as an alternative to traditional accommodation options, understanding and predicting the factors that influence daily listing prices can be valuable for both hosts and travelers.

## Notebooks

The project consists of three Jupyter notebooks:

1. [EDA/Cleaning](notebooks/EDA_Cleaning.ipynb): This notebook performs exploratory data analysis and data cleaning tasks. It covers loading the raw dataset, examining its structure and statistics, handling missing values, cleaning the data, and conducting exploratory data analysis.

2. [Feature Engineering](notebooks/Feature_Engineering.ipynb): In this notebook, feature engineering tasks are performed to prepare the data for modeling. It includes preprocessing text data, creating new features based on descriptions and temporal patterns, handling missing values, and exploring top amenities.

3. [Modeling](notebooks/Modeling.ipynb): The modeling notebook focuses on building predictive models for Airbnb prices. It covers loading the preprocessed data, conducting a baseline prediction, training a Gradient Boosting model and a LassoCV model, making predictions, and evaluating the model's performance.

## Key Findings

Here are some key findings from the project:

- The exploratory data analysis revealed interesting insights about the dataset, such as the distribution of room types and neighborhoods, as well as the correlation between variables.
- Feature engineering tasks, including text preprocessing, temporal feature extraction, and handling missing values, enhanced the dataset and provided valuable information for modeling.
- The Gradient Boosting model demonstrated strong performance in predicting Airbnb prices, with a low mean squared error (MSE) and mean absolute error (MAE).
- The LassoCV model also showed promising results, accurately estimating the daily prices of Airbnb listings.

## How to Use

To replicate the project or use the provided models, follow these steps:

1. Clone the repository to your local machine.
2. Open and run the notebooks in the provided order: EDA/Cleaning, Feature Engineering, and Modeling.
3. Follow the instructions within each notebook to load, preprocess, analyze, and model the data.
4. Adapt the code and models to fit your specific requirements or use the provided models for predicting Airbnb prices in Broward County.

## Dataset

The dataset used in this project is based on the "listings-3.csv" file, which contains Airbnb listings in Broward County, Florida. The dataset was cleaned and preprocessed as part of the project.

You can access the dataset [here](http://insideairbnb.com/get-the-data/). 

Note: Please ensure that you have the necessary permissions and comply with any applicable terms of use or licenses when accessing and using the dataset.


## Acknowledgements

The project was developed as part of a data science capstone project. The dataset used in this project was sourced from Airbnb. Special thanks to the instructors, mentors, and the open-source community for their valuable contributions.

Feel free to explore the notebooks and adapt the code for your own projects or analysis. Enjoy exploring Airbnb prices in Florida!

## License

This project is licensed under the [MIT License](LICENSE).

