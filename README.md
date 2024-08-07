# Book Recommendation System

# Overview
This project demonstrates how to build a personalized book recommendation system using collaborative filtering. We utilize various data processing techniques and machine learning algorithms to recommend new books to users based on their reading preferences.

# Features
Data Processing: Handling large datasets with over 228 million rows.

Collaborative Filtering: 
Creating a matrix to find users with similar tastes in books.

Cosine Similarity: 
Calculating similarity between users to generate recommendations.

TF-IDF: 
Using Term Frequency-Inverse Document Frequency for text data processing.

Pandas Styling: 
Enhancing the presentation of DataFrame columns.

# Technologies Used
Pandas: For data manipulation and analysis.

Scikit-learn: For implementing machine learning algorithms.

NumPy: For numerical computations.

# Project Steps
1. Dataset Collection
The dataset is collected from Goodreads Book Data scraped by researchers at UCSD. It is available at https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/books
which contains three important files are as shown below:
#### Download these files

#### books_titles.json
https://drive.google.com/file/d/1I1qv9TRQqNgYbUDjSaDegv4EPpx097t3/view?usp=sharing

#### goodreads_interactions.csv
https://drive.google.com/open?id=1zmyLV7XW2dfQVCLeg1LbLLfQtHD2KUon

#### book_id_map.csv
https://drive.google.com/uc?id=1CHTAAwNyzvbi1TR08MjrJ03BxA266Xxr

#### Liked_books.csv
https://drive.google.com/file/d/1dhPhfD5AhOJrjdf8Jhv0DpXDpF4qYNnb/view?usp=sharing

2. Exploring the Dataset
We start by exploring our dataset to understand its structure and contents. This helps in determining the necessary preprocessing steps.

3. Filtering the Data
Given the large size of the dataset (228 million rows), we filter it to reduce the row count for efficient processing. This step involves removing irrelevant or redundant data.

4. Creating the Collaborative Filtering Matrix
We construct a collaborative filtering matrix, where users are represented as vectors based on their book ratings. This matrix is the foundation for identifying similar users.

5. Calculating Cosine Similarity
Using cosine similarity, we find users with similar reading tastes. This metric helps in determining the angle between user vectors, indicating their similarity.

6. Generating Recommendations
With similar users identified, we generate personalized book recommendations. We rank these recommendations based on their relevance to the target user.

7. Styling DataFrames
To present the recommendations in a user-friendly manner, we apply styling to the pandas DataFrames, enhancing readability and aesthetics.

# Results
By the end of this project, we achieve a personalized list of Book Recommendations tailored to individual user preferences.
