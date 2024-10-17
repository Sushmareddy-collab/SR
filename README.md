# Sentiment Analysis of Amazon Product Reviews
Project Overview
This project performs Sentiment Analysis on a dataset of Amazon product reviews. The aim is to classify customer feedback into three sentiment categories: Positive, Neutral, and Negative. Additionally, the project explores trends in customer satisfaction and dissatisfaction across different product categories.

#Dataset
The dataset used in this project is sourced from Kaggle and contains various Amazon product reviews, including text reviews, product ratings, and metadata such as the date of review and product categories.
Dataset Source: Amazon Product Reviews Dataset
File Used: Reviews.csv

Project Steps
The project workflow includes the following steps:

Data Collection:

The dataset is loaded from a CSV file.
Data Cleaning and Preprocessing:

Missing data is handled, and the review text is cleaned by converting to lowercase, removing special characters, and stop words.
Sentiment Analysis:

Using the TextBlob library, each review’s sentiment polarity is computed and categorized into Positive, Neutral, or Negative sentiments.
Data Visualization:

Visualizations, including bar charts and word clouds, are generated to show the distribution of sentiments and the most common words in positive and negative reviews.
Insights and Recommendations:

The analysis summarizes trends in product reviews and provides insights into customer feedback patterns.
Technologies Used
Programming Language: Python
Libraries:
Pandas: For data manipulation and analysis.
TextBlob: For sentiment analysis.
Matplotlib: For visualizations.
WordCloud: For generating word clouds.
nltk: For natural language processing (tokenizing and removing stop words).
Results
Sentiment Distribution: The analysis shows the percentage of positive, neutral, and negative reviews.
Top Products: Products with the highest and lowest sentiment scores are identified.
Key Insights: Patterns in customer satisfaction and dissatisfaction are highlighted.
How to Run the Project
To run this project, follow these steps:

Clone this repository:
bash
Copy code
git clone https://github.com/your_github_username/your_repo_name.git
Install the required libraries:
bash
Copy code
pip install textblob matplotlib wordcloud nltk
Run the Jupyter Notebook or Python script to perform sentiment analysis.
Future Work
Topic Modeling: Explore the main topics in positive and negative reviews.
Model Training: Implement machine learning models to improve the accuracy of sentiment predictions.
License
This project is open-source under the MIT License.
