# Netflix Movie Recommendation System
(case studies), Recommendation systems based on user viewing patterns, specifically for Netflix. The recommendation system is powered by machine learning, leveraging a combination of collaborative and content-based filtering to provide the most relevant recommendations.

## Description

A movie recommendation system is an AI-based tool designed to generate personalized movie suggestions for Netflix users. This tool utilizes both collaborative filtering and content-based recommendation techniques. It can predict what movie a user might like by learning from their past behavior and other users with similar preferences.
This project aims to develop a movie recommendation system based on user viewing patterns, specifically for Netflix. The recommendation system is powered by machine learning, leveraging a combination of collaborative and content-based filtering to provide the most relevant recommendations.

## Technologies

This project is implemented with the following technologies:

- Python
- Pandas
- Numpy
- Scikit-learn
- Tensorflow

## Features

1. **User Recommendation:** The system suggests movies to users based on their previous viewing patterns and ratings.
2. **Item Recommendation:** The system suggests similar movies to a particular movie, aiding users in finding related content.
3. **User-Item Recommendation:** The system provides recommendations for movies that a user might like based on similar users' preferences.

## Dataset

The Netflix prize data set is used in this project, which contains 100480507 ratings given by 480189 users for 17770 movies.


## System Design

The recommendation system is designed using a hybrid model which incorporates both collaborative and content-based filtering:

- **Collaborative Filtering:** This method makes automatic predictions (filtering) about a user's interests by collecting preferences from many users (collaborating). It uses user behavior, activity, or information and predicts what users will like based on their similarity to other users.
- **Content-Based Filtering:** This method uses only information about the description and attributes of the items users have previously consumed to model user's preferences. 

## How to Run

To use this project, follow the steps below:

1. Clone the repository: `git clone https://github.com/mostafathemar/Netflix-Movies.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Run the main script: `python notebook.ipynb`


## License

This project is licensed under the terms of the MIT license.

## Contact

For any queries, please feel free to reach out to us at `mostafa@email.com`.
