
## Code Overview

The code performs the following steps:

1. Loading the dataset and preprocessing:
   - Reading the CSV file and displaying basic information about the DataFrame.
   - Handling missing values by dropping them and resetting the DataFrame index.
   - Converting email texts to lowercase for uniformity.
   - Replacing email addresses, URLs, currency symbols, phone numbers, and numeric characters with placeholders.
   - Removing punctuation, extra white spaces, and common stopwords.

2. Data Analysis:
   - Visualizing the count of labels (spam vs. non-spam) using a bar plot.
   - Creating distribution plots to analyze the length of emails before and after cleaning.

3. WordCloud Visualization:
   - Generating WordClouds to visualize frequently occurring words in spam and non-spam emails.

4. Building the SVM Model:
   - Converting email texts into numerical vectors using the TF-IDF representation.
   - Splitting the dataset into training and testing sets.
   - Training the SVM classifier on the training data.
   - Evaluating the model's performance using accuracy, precision, recall, and F1-score.
   - Plotting the confusion matrix heatmap to visualize the model's predictions.

## How to Use

1. Install the required dependencies as mentioned above.

2. Download the dataset file (`spam_or_not_spam.csv`) and place it in the same directory as the code file.

3. Execute the code in any Python environment (Jupyter Notebook, Google Colab, or Python IDE).

4. The output will display various visualizations and the final accuracy score of the SVM model.

Note: The code assumes that the dataset file is in the correct format and has the necessary columns. Please ensure that the dataset file is valid before running the code.

Feel free to explore and modify the code to improve the model or perform additional analyses on the data. Happy coding!
