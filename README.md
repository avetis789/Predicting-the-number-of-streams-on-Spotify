Predicting Spotify Streams

About the Project
This project aims to predict the number of streams a new song will receive on Spotify based on various audio features and specificities of approximately 6500 songs. By analyzing these features, we seek to understand listeners' preferences and potentially trigger more streams on the platform.

Data Analyzed
Approximately 6500 Songs: The dataset includes a variety of song audio features and specificities.
Target Variable: The target variable is 'streams', which is continuous and represents the number of streams a song receives.
Research Question: Based on the available features, can we predict with accuracy how many streams a new song will get?
If successful, songwriters will gain insights into listener preferences, potentially increasing streams on Spotify.

Linear Regression Results
R-squared: 49% of the variance in streaming numbers can be explained by the predictors.
F-Statistic: Indicates a statistically significant relationship between streams and other features.
Prediction Results: Suggest a 15% to 22% error rate, indicating the model's usability.

Gradient Boosting Regressor
The model suggests a good fit with the data, with very close training and test results.
Further optimization resulted in even closer training and test results, with Mean Squared Errors at 0.022 and 0.024, respectively.

Most Influential Feature
Valence: Found to be the most influencing feature in determining the number of streams.
Positiveness of the song influences streaming frequency, suggesting songwriters focus on writing positive songs for increased streams.

Weak Points / Shortcomings
The model heavily depends on one feature, potentially oversimplifying the problem and introducing bias.
Overfitting and capturing feature-specific noise may limit the model's effectiveness in capturing underlying patterns and relationships.

Conclusion
The model performs well but relies predominantly on audio components of the song. Suggestions are made to incorporate additional features such as song reviews, ratings, genre, artist popularity, and social media metrics for more meaningful insights.

Getting Started
To replicate or build upon this project, follow these steps:

Prerequisites
Python, Jupyter Notebook

Required libraries
Pandas, NumPy, Scikit-learn

Installation
Clone the repository. Install the required dependencies using pip install -r requirements.txt.
Open the Jupyter Notebook files to explore the project.

Data Sources
Link to raw data: https://www.kaggle.com/datasets/julianoorlandi/spotify-top-songs-and-audio-features

Future Improvements
Incorporate additional features such as song reviews, ratings, genre, artist popularity, playlist ads, and social media metrics for more comprehensive analysis.

Acknowledgements
Special thanks to Chegg Skills study platform for great study materials.

Contact
For questions, feedback, or collaboration opportunities, contact tnyeghiazaryan@gmail.com
