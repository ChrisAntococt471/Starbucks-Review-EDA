# Starbucks-Review-EDA

![](https://github.com/ChrisAntococt471/Starbucks-Review-EDA/blob/main/CAFE.jpg)

Starbucks Corporation is a well-known American multinational chain of coffeehouses and roastery reserves, with more than 80,000 stores worldwide. Despite being famous, apparently it suffers low rating reviews from customers in some areas, which needs to be addressed as soon as possible.

This notebook's goal is to use Word Cloud and other text analysis tools to analyze customer reviews of various Starbucks shops in order to identify things that need improvement.

The data can be downloaded at https://www.kaggle.com/datasets/harshalhonde/starbucks-reviews-dataset

First, we do text preprocessing technique before we go to the text analysis. We will convert the letters into lowercase, expand contractions, remove numbers, remove punctuation, add stopwords, and lemmatize the texts. Once we're done with the text preprocessing, we will use Word Cloud and Ngrams as methods to analyze customer reviews.

![](https://github.com/ChrisAntococt471/Starbucks-Review-EDA/blob/main/Negative%20Bigrams%201.png)

From negative bigrams, we can see that customer service frequency far exceeds other bigrams. Another bigram that catches the eye is a gift card. Apparently, Starbucks has a gift card feature that allows you to send physical or digital Starbucks Cards to gift, reward, incentivize, or show appreciation towards your customers, clients, and team members, as quoted from their official page. This system, however, is not appreciated by customers.

From positive bigrams, we also found that customer service tops anything by a large margin too. This is always the case for online reviews, as they tend to be polarizing, but in this case, the negative far outnumbered the positive, so it is worth looking. Other positive bigrams are product-related, like great coffee or food.

Now we can conclude that people relatively like the products (in this case, the coffee) but have a lot of bad experience with customer service and cards.

To improve these ratings, Starbucks should focus on the following actions:

Train customer service staff to handle technical problems, especially payment and card issues, while maintaining a helpful attitude, as some customers have appreciated.
Make the terms and conditions more visually appealing so that customers can easily read and understand them. For example, use bullet points, bold key sentences and numbers, and "do's and don'ts.".
Enhance card availability, as several customers have complained about being unable to use their cards.
