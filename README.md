# Metis projects

please email me if you will like to see complimentary presentations for the projects

Which houses make the best investments?

Created a web-scraper using Beautiful Soup and Selenium on Redfin to gather data on homes  and their historical prices. Parsed the description with NLP to get additional vectors to add to XGBoosted layered regressions to analyze the data. I normalised price changes on the local House Pricing Index to extract the properties most correlated with homes that outperformed average real estate gains in the area. I found the location, and regularly updated homes made the best investments. Also longer descriptions with detailed descriptions including quality materials correlated highly with groups of homes that make the best investments.


TED Talk Recommenders

Designed a recommender for TED Talks by using pairwise distance on the transcripts for each TED Talk. Applied TF-IDF for vectorization, and NMF for topic modeling. Designed multiple outputs based on the vectorizer's min_df and max_df to narrow and widen the scope of the words processed. I concluded with two recommenders, one that suggested videos that were stylistically similar to a video input, and one that suggested videos that were topically similar to a video input.


Instacart Auto-cart Generator

Using Kaggle Instacart dataset, engineered features to predict which items are most likely to be in a user's next cart.  Used a random forest classifier and I found that the recommender worked well with a weighted F1 score of 0.368. Predictions for items in the cart were all items that were likely to be ordered again based on amount (excluding events) and one time buys (such as cookware).


Can your Personality Help Predict your Productivity?

Created several web-scrapers to gather data on GDP, population,  and country code converters. Utilized Big-5 personality data and feature engineered to discover a link between particular personality traits and GDP per capita. Utilized Scikit Learn to get correlations. I concluded that there are significant personality features that predict productivity: most notably Conscientiousness and Agreeableness.
