# Netflix-Movies-and-TV-Shows-Clustering
![1188076549](https://github.com/somyakmukherjee/Netflix-Movies-and-TV-Shows-Clustering/assets/110627955/e2b05ae9-1823-4e52-997c-e6b976224828)
The aim of this project is to analyze the Netflix Dataset of movies and TV shows until 2019, sourced from the third-party search engine Flixable. The goal is to group the content into relevant clusters using NLP techniques to improve the user experience through a recommendation system. This will help prevent subscriber churn for Netflix, which currently has over 220 million subscribers.

Additionally, the dataset will be analyzed to uncover insights and trends in the streaming entertainment industry.

The project followed a step-by-step process:

Handling null values in the dataset.
Managing nested columns (director, cast, listed_in, country) for better visualization.
Binning the rating attribute into categories (adult, children's, family-friendly, not rated).
Performing Exploratory Data Analysis (EDA) to gain insights for preventing subscriber churn.
Creating clusters using attributes like director, cast, country, genre, rating, and description. These attributes were tokenized, preprocessed, and vectorized using TF-IDF vectorizer.
Reducing the dimensionality of the dataset using PCA to improve performance.
Employing K-Means Clustering and Agglomerative Hierarchical Clustering algorithms, determining optimal cluster numbers (4 for K-Means, 2 for hierarchical clustering) through various evaluation methods.
Developing a content-based recommender system using cosine similarity matrix to provide personalized recommendations to users and reduce subscriber churn for Netflix.
This comprehensive analysis and recommendation system are expected to enhance user satisfaction, leading to improved retention rates for Netflix.

With the advent of streaming platforms, there’s no doubt that Netflix has become one of the important platforms for streaming. The dataset that we have used for EDA and clustering has been collected by Flixable, a third-party Netflix search engine. There are 12 features and around 7700 observations in the dataset and are mostly textual features.

Through univariate and multivariate analysis, we found trends that will help in understanding what content is being consumed country-wise, depending on some categorical features like rating, type, genres, cast, directors, etc. Clustering was performed along with NLP on textual columns and then a mini-recommendation system was built out of it.

Project Description
In our project, Netflix Movies & TV Shows Clustering, we were able to analyse and perform an unsupervised Machine Learning Algorithm for the unlabelled datasets. The dataset we were provided with contains several columns and other numerical features. We were also asked two questions that could be answered from EDA.

The EDA was done extensively as we needed to derive good insights to support our claim and hypothesis. We were able to answer the two questions that followed along with the EDA, country-wise trend analysis on content and genre; and also to analyse if Netflix was focusing more on Shows rather than Movies.

After we performed EDA, both univariate and bivariate analysis, we have prepared our text columns by following basic text cleaning, stopwords removal, tokenisation and stemming. After the text columns were ready, we selected only features or words that were important using TF IDF Vectorisation and also reduced dimension.

The prepared text columns were clustered after selecting an optimal value from elbow plots. Finally, we used K Means to cluster our dataset into 9 distinct clusters and we were also able to encode or label the dataset accordingly.

Subsets of dataset formed from clustering were analysed and word clouds were plotted, after which we used interactive Plotly visualisation to represent the cluster.

Finally, a simple recommendation system was also tried out, the future scopes for the projects were also identified.
