# Clustering-and-Sentiment-Analysis

The project involved clustering restaurants using KMeans algorithm based on various features such as cost, cuisine, locality, and meta-tags. After grouping similar restaurants together, I analyzed the clusters to identify any trends in the data. The project also included sentiment analysis of customer reviews to gain insights about customer preferences and satisfaction. The findings were presented using visualizations to draw useful conclusions about the sentiments expressed by customers.

# Objective

India is renowned for its vast array of restaurants and hotel resorts offering a diverse range of multi-cuisine, symbolizing the country's unity in diversity. In this project, we aim to analyze customer sentiments towards these establishments and draw valuable conclusions through visualizations. Additionally, we will categorize Zomato restaurants into various segments.

# Methods Used

    • Descriptive Statistics
    • Data Visualization
    • Machine Learning -Supervised-Learning -Unsupervised-Learning
    
# Tech Stack

    • Python
    • Pandas
    • Numpy
    • Matplotlib
    • Seaborn
    • Scikit-learn
    • NLP

# About the Data 

The Zomato-Restaurants dataset contains two distinct files, each with unique information. The first file, "Zomato restaurant reviews," includes data such as the name of the restaurant, name of the customer, their review, rating, follower details, time of review, and number of photos uploaded. This information is typically used for sentiment analysis.

The second file, "Zomato Restaurant names and Metadata," provides details such as the name of the restaurant, a link to order on their restaurant on Zomato, average cost, tags for the restaurants, cuisines, and timings. This data is often utilized for clustering.

# Steps involved

    • Exploratory Data Analysis - Performed exploratory data analysis and text preprocessing
    • Data Cleaning - We have to drop the entire feature as there are 50% null values.
    • Feature Selection - For sentiment analysis, we have used rating and reviews features. - For clustering we got cost, cuisine and timing of the restaurant as the features to build the model.
    • Model building - For sentiment analysis, developed different models like:- Multinomial NB, Logistic regression, Random forest classifier - For clustering the restaurants we have used the k-means and hirerchical clustering
    
# Sentiment Analysis

To gain insights into the proportion of positive and negative reviews, various visualizations were created such as plotting the distribution of ratings, displaying the top 10 and bottom 10 restaurants based on their average rating, and examining the cost summary of the restaurants. The dataset was pre-processed by removing emojis and punctuations, and only using adjectives and verbs to reduce dimensionality. The TF-IDF vectorizer was employed to transform the dataset, and sentiment analysis was performed using the TextBlob() library, which resulted in a root mean square error (RMSE) score of 0.88. Additionally, word clouds were generated to represent positive and negative phrases.

# Clustering

I performed several data pre-processing steps on the restaurant data, including calculating the weekly opening time for each restaurant, grouping some cuisines together to enable one-hot encoding, removing unnecessary variables, and normalizing the data. Subsequently, I applied both K-means clustering and hierarchical clustering algorithms to cluster the data.

# Conclusion

Used clustering techniques to segment the restaurants based on their characteristics and conducted sentiment analysis on the reviews to gain insights into customer experiences. This provided valuable insights for improving the overall customer experience and optimizing restaurant performance.


