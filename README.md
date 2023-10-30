# Sentiment Analysis Project (Basic Python)
**Final Project in Python Functions, Files, and Dictionaries course: Sentiment Analysis**
## Project Overview
The Sentiment Analysis Project with Basic Python is a simple text analysis project that explores fundamental Python functions and techniques to understand and interpret sentiment within textual data. Unlike complex machine learning or natural language processing (NLP) models, this project focuses on a more straightforward and accessible approach to sentiment analysis.

For this final project in the Python Functions, Files, and Dictionaries course, we delved into the world of sentiment analysis. This intriguing project involved the use of synthetic Twitter data, stored in a CSV file named "project_twitter_data.csv." This file contains information on each tweet, including the text of the tweet, the number of retweets, and the number of replies. Additionally, we had access to two separate word lists, one for positive sentiments ("positive_words.txt") and another for negative sentiments ("negative_words.txt").

Our primary objective was to construct a sentiment classifier capable of discerning the positivity or negativity of each tweet. The end result was a CSV file named "resulting_data.csv" with columns for the Number of Retweets, Number of Replies, Positive Score (indicating the presence of positive words in the tweet), Negative Score (indicating the presence of negative words in the tweet), and the Net Score (representing the overall sentiment) for every tweet. The final step involved uploading this CSV file to either Excel or Google Sheets and creating a graph to visualize the relationship between the Net Score and the Number of Retweets.

To kick off the project, I defined a function named `strip_punctuation()` to eliminate any punctuation characters from a given word, employing the `.replace()` method for strings.

Following that, I implemented the `get_pos()` function, which takes a string representing one or more sentences and calculates the count of positive words within the text. To determine positive words, I referred to the "positive_words" list. The function returns a positive integer, signifying the number of positive word occurrences in the text. It's worth noting that all the words in "positive_words" are in lowercase, so I ensured that the input string was also converted to lowercase.

Similarly, the `get_neg()` function, which followed the "strip_punctuation" template, determined the count of negative words in a given string, using the "negative_words" list. It, too, returned a positive integer, reflecting the number of negative word occurrences in the text, with the string being converted to lowercase.

Lastly, the key part of the project involved merging all the functions and crafting code to open the "project_twitter_data.csv" file, which contained the fabricated Twitter data. Our mission was to build the sentiment classifier, gauging the positivity or negativity of each tweet. We integrated the previously created functions into this code. The end result was the creation of the "resulting_data.csv" file, complete with the specified headers: Number of Retweets, Number of Replies, Positive Score, Negative Score, and Net Score. The project also included the additional task of generating a graph depicting the relationship between Net Score and the Number of Retweets. Instructions for this last component could be found on Coursera if accessing this textbook through that platform.

## Project Description

The project comprises the following key components:

1. **Data Collection**: To start the project, you need to acquire text data that contains sentiment. This data can be gathered from various sources, including social media posts, product reviews, or any textual content expressing opinions or emotions.

2. **Data Preprocessing**: The text data is preprocessed to clean it and prepare it for analysis. This may involve tasks like lowercasing, punctuation removal, and basic text cleaning.

3. **Sentiment Analysis Functions**: Instead of using machine learning or NLP models, this project leverages basic Python functions to analyze sentiment. You can develop functions that assign sentiment scores or labels to text based on simple rules or keyword matching.

4. **Model Testing**: After implementing the sentiment analysis functions, you can test their performance on sample text data and evaluate their effectiveness in categorizing sentiment as positive, negative, or neutral.

5. **Customization and Enhancement**: The project can be customized and enhanced by adding more rules or refining the existing functions to improve accuracy.

6. **Documentation**: Project documentation includes the README.md file, describing the project, its components, and how to use it.

## Contributors

- [Niraj Bansal](https://github.com/NirajB1602)

Feel free to fork, contribute, and share this project with others interested in basic sentiment analysis using Python.
