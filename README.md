🍽️ Zomato Data Analysis Using Python

📌 Project Overview

This project analyzes restaurant data from Zomato to gain insights into:

Popular restaurant types

Distribution of ratings

Voting patterns by restaurant type

Online order availability

Approximate cost distribution for couples

The dataset consists of 148 restaurants with features such as name, ratings, votes, cost, and type.

📂 Dataset

The dataset used is: Zomato-data-.csv
It contains the following columns:

name → Restaurant name

online_order → Whether online ordering is available (Yes/No)

book_table → Whether table booking is available (Yes/No)

rate → Restaurant rating (converted to float)

votes → Number of votes received

approx_cost(for two people) → Average cost for two people

listed_in(type) → Type of restaurant (e.g., Buffet, Dining, etc.)

🛠️ Data Cleaning

Converted ratings from "x.x/5" format to float values.

Checked for missing values → none found.

Verified data types (float, int, object).

📊 Analysis Performed

Restaurant Types → Count of restaurants by type.

Votes by Restaurant Type → Aggregated votes grouped by type.

Most Voted Restaurant → Identified the restaurant with the maximum votes.

Online Order Availability → Distribution of restaurants offering online orders.

Rating Distribution → Histogram of ratings.

Approximate Cost → Cost distribution for couples.

Online Order vs Restaurant Type → Countplot comparison.

📈 Visualizations

Countplots (Restaurant Types, Online Order, Cost Distribution)

Line Plot (Votes by restaurant type)

Histogram (Rating distribution)

Countplot with Hue (Online Order vs Restaurant Type)

🏆 Key Insights

Empire Restaurant received the maximum votes.

Most restaurants fall into categories like Buffet and Dining.

Ratings are generally clustered around 3.5 to 4.5.

Many restaurants support online ordering, but distribution varies by type.

🚀 How to Run

Clone this repository:

git clone https://github.com/username/Zomato-Data-Analysis-Using-Python.git


Install required libraries:

pip install pandas numpy matplotlib seaborn


Run the notebook in Google Colab or Jupyter Notebook.

📌 Tools & Libraries

Python 3

Pandas

NumPy

Matplotlib

Seaborn

📜 License

This project is for educational purposes only.
