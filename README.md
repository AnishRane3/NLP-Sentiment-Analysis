#NLP Sentiment Analysis of Amazon Product
This project performs sentiment analysis on customer reviews of an Amazon product. By scraping the reviews directly from the Amazon website, the project applies a series of Natural Language Processing (NLP) techniques to determine the overall sentiment (positive, negative, or neutral) of the product.

Key Libraries Used:

pandas: For data manipulation and analysis.
requests: To fetch HTML content from the Amazon product page.
BeautifulSoup: For parsing HTML and extracting review data.
re and string: For text preprocessing, including removing unwanted characters and punctuation.
nltk (Natural Language Toolkit): Used for tokenization, removing stopwords, and lemmatization.
TextBlob: For performing sentiment analysis on the processed text.
WordCloud: To generate a visual representation of the most frequent words in the reviews.
matplotlib: For plotting and visualizing the sentiment analysis results.
Project Workflow:

Data Collection: Reviews are scraped from Amazon using the requests library and parsed with BeautifulSoup.
Text Preprocessing: Reviews are cleaned by removing HTML tags, punctuations, and stopwords. The text is then tokenized and lemmatized.
Sentiment Analysis: Using TextBlob, each review is analyzed to determine its sentiment score.
Visualization: A word cloud is generated to visualize the most common words, and the sentiment distribution is plotted using matplotlib.
This project offers a straightforward approach to sentiment analysis, with the potential to expand and apply more advanced NLP techniques.
