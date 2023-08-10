# Sentiment Analysis and Visualization Script

An interactive Python script that performs sentiment analysis on customer reviews using the TextBlob library and visualizes the sentiment distribution. The script reads customer reviews from a CSV file, extracts sentiments, and generates a bar plot for visualization. A comprehensive README provides instructions to set up and run the script.

## Getting Started

### Prerequisites

- Python 3.x
- Pandas
- mysql-connector
- textblob
- matplotlib

### Usage

1. Clone the repository or copy the script to your local environment.
2. Make sure you have the required Python libraries installed by running:

   ```
   pip install pandas mysql-connector-python textblob matplotlib
   ```

3. Place the 'customer_review.csv' file in the same folder.
4. Adjust the MySQL connection settings in the script:

   ```python
   host = '127.0.0.1'
   database = 'python_lib'
   user = 'root'
   password = ''
   ```

5. Run the script using:

   ```bash
   python sentiment_analysis.py
   ```

6. The script will read the customer reviews from the CSV, perform sentiment analysis, and save the results to a new CSV ('sentiment_dataset.csv').
7. It will also generate a bar plot visualizing the sentiment distribution.


Remember to adjust the paths and filenames as needed, and ensure that you have the necessary libraries installed before running the script.


## Author
[Ankita Shekhawat]
