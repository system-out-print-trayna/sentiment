# sentiment
Sentiment Score for Amazon Reviews

Description:
The provided Python code implements sentiment analysis on Amazon review data sourced from Kaggle. Sentiment analysis involves assessing the positivity or negativity of text. This code demonstrates a simple approach to sentiment analysis using lists of positive and negative words.

Data Retrieval:

Three files are utilized: reviews.txt, positive_words.txt, and negative_words.txt.
The contents of positive_words.txt and negative_words.txt are read into separate lists, stripping whitespace.
Each comment in reviews.txt is transformed into a list of lowercase words using .lower().
Computations:

Sentiment scores are assigned to each review.
For each review, the code breaks down the text into words using split().
If a word in the review appears in the positive words list, the review's score increases by 1. Conversely, if a word appears in the negative words list, the score decreases by 1.
The sentiment score for each review is computed and stored in a list.
Communication:

Display the length and the first three elements of each list (positive words, negative words, comments).
Print the fifth comment and its sentiment score.
Plot frequency distribution of sentiment scores using plt.hist() function. This creates a histogram illustrating the distribution of sentiment scores.
The code provides a foundational understanding of sentiment analysis and can be further enhanced with advanced algorithms. It serves as an introduction to natural language processing, with potential applications in brand sentiment monitoring and customer feedback analysis.
