# Movie Recommender System Using Association Rules

## Overview
This project utilizes association rules to create a movie recommendation system. The system identifies films that users might enjoy based on their previous ratings. The method can also determine movies likely to be disliked, enhancing the recommendation quality.

## Technologies
- **Python & Libraries**: Used `numpy`, `pandas`, and `mlxtend` for data manipulation and association rule mining.
- **Data Preprocessing**: Employed `TransactionEncoder` for converting datasets into a suitable format for applying the Apriori algorithm.
- **Modeling Technique**: Applied `apriori` and `association_rules` from `mlxtend.frequent_patterns` to derive both positive and negative recommendations based on user preferences.

## Process
1. **Data Loading and Cleaning**: Loaded movie and rating data, dropping irrelevant columns.
2. **Filtering Ratings**: Distinguished positive from negative ratings to treat them separately.
3. **Transaction Creation**: Transformed user ratings into transactions of watched movies.
4. **Apriori Algorithm**: Implemented to find frequent itemsets and derive association rules.
5. **Recommendations**: Generated based on high confidence and lift from the association rules.

## Achievements
- Developed a versatile recommender that not only suggests movies but also identifies potential dislikes.
- Enhanced user experience by personalizing movie recommendations based on historical data.
