# Graph-Based Movie Recommendation System Using Neo4j

## Overview
This project implements a **graph-based movie recommendation system** using **Neo4j**, a graph database that efficiently represents relationships between movies, users, and ratings. The system provides **personalized movie recommendations** based on user preferences, ratings, and movie relationships.

## Features
- **Graph-based representation** of movies, actors, directors, and genres
- **Content-based filtering** for personalized recommendations
- **Cypher queries** for retrieving movie recommendations
- **Python pipeline** for data insertion and querying
- **Tableau visualizations** for insights into movie relationships

## Dataset
- **Source:** [IMDB Indian Movies Dataset](https://www.kaggle.com/datasets/arshadali12/imdb-indian-movies-dataset)
- **Size:** 5659 rows × 10 columns
- **Columns:** `Name`, `Year`, `Duration`, `Genre`, `Rating`, `Votes`, `Director`, `Actor1`, `Actor2`, `Actor3`
- Data is **imported into Neo4j** and structured as a **graph database**

## Implementation
### Data Processing
- Import movie dataset into **Neo4j** using **Cypher queries**
- Establish **nodes** for movies, actors, genres, and directors
- Create **relationships** between entities

### Model Architecture
- **Neo4j Graph Database** stores movie relationships
- **Cypher Queries** retrieve relevant recommendations
- **Python Pipeline** automates data insertion and querying
- **Tableau** visualizes insights and relationships

### Recommendation Approach
- **Content-Based Filtering**
  - Suggests movies based on **actor, director, or genre**
  - Sorted by **ratings** for better recommendations
- **Cypher Queries for Recommendations:**
  - Find movies with similar genres
  - Suggest movies based on actors
  - Recommend movies based on directors

## Results
- **Efficient recommendations** generated using Cypher queries
- **Ranked results** based on movie ratings
- **Tableau visualizations** helped analyze movie relationships

## Applications
- **Personalized Movie Suggestions**
- **User-Specific Recommendations**
- **Graph-Based Data Analysis**
- **Scalable System for Future Enhancements**

## Future Work
- Extend recommendation system to **collaborative filtering**
- Integrate with **real-time user preferences**
- Implement **hybrid filtering techniques**
- Improve **graph visualizations** for better insights
