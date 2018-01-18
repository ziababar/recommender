# Recommendation Systems
Recommendation Systems series for the Waterloo Data Science and Data Engineering meetup

## Presentation on Recommender Systems (30 minutes)
- Explaining and Building recommendation systems
- Understanding Recommendation Systems
  - The need for Recommender Systems
- Defining the business understanding and requirements
- Taxonomy of Recommender Systems
  - Domain
  - Purpose
  - Context
  - Personalization Level
  - Whose Opinions
  - Privacy and Trustworthiness
  - Interfaces
  - Algorithms
- Evolution of Recommender Systems
- Approaches in Recommendation Systems
  - Collaborative filtering approaches
  - Content-based filtering approaches
  - Hybrid approaches
- The Data Science process pipeline for Recommendation Systems
  - Idea (e.g. sell more)
  - Data (log data)
  - Algorithms (recommender algorithm)
  - Model (offline results)
  - Offline testing (test implementation on saved data)
  - Online testing (test on real users)
- Three part series
  - (1) Introducing Recommendation Systems
  - (2) Building Recommendation Models
  - (3) Productizing Recommendation Systems

## Environment and Setup (20 minutes)
- Azure Notebook
- Python
- Pandas
- Machine learning library like scikit-learn
- Dataset used
  - https://github.com/practical-recommender-systems/moviegeek (contains MovieGeek database)
  - https://github.com/sidooms/MovieTweetings (contains dataset of movie tweets, regularly updated)
  - http://files.grouplens.org/datasets/movielens/ml-100k.zip (movielens database)
- Example projects
  - https://github.com/practical-recommender-systems/moviegeek
  - https://cambridgespark.com/content/tutorials/implementing-your-own-recommender-systems-in-Python/index.html
  
## Session 1: Introducing Recommendation Systems (40 minutes)
- Sourcing data
  - Determining implicit and explicit data
  - User behavioral data
  - Hands On: Capturing user behavioral data from an website
- Solving the problem of cold start
  - Hands On: Generating data
- Exploring and visualing data
  - Hands On: Performing data exploration
  - Hands On: Visualizing data using pandas
- Feature Engineering
  - Hands On: Pre-process data
  - Hands On: Transform data
- Selection of approaches based on data
  - Non-personalized
  - Personalized
  - Semi/segment personalized
  
## Session 2: Building Recommender Models
- Algorithms used
- Building
- Training
- Evaluating recommenders
- Preexisting recommenders
  - Apache Spark MLlib

## Session 3: Productizing Recommeders
- Deploying recommendation systems
- Real-time stream processing and recommendation
- Collection user behavioral data 
- Defining performance measures
- Evaluating model performance
- Cold-start scenarios
- A/B testing
- Ongoing monitoring of recommender
