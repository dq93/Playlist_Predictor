# Playlist Predictor

<img width="500" height="420" alt="Image" src="https://github.com/user-attachments/assets/20f0cdc5-b2df-4628-8a20-a86333ae41be" />

The purpose of this project is to imitate a music recommendation algorithm using unsupervised machine learning. K-Means clustering is used without scaling, then with scaling and then with PCA. A new sample is then created for the final algorithm. This project uses a dataset of songs from 1950 - 2019 that was taken from a research paper published in 2020 titled "Music Dataset: Lyrics and Metadata from 1950 to 2019". 

Link to the dataset: https://data.mendeley.com/datasets/3t9vbwxgr5/3

# Features of the dataset:

## Categorical

artist_name: The name of the artist

track_name: The name of the song

release_date: When this song was released

genre: The categorical genre of this song

lyrics: The pre-tokenized lyrics of this song. Disclaimer: note that as this is real-world data, lyrical content is often obscene. 

## Quantitative

len:  The number of words in the lyrics of this song

dating: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with dating.

violence: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with violence.

world/life: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the world or life in general terms.

night/time: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do night-life or time.

shake the audience: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with provocative feeling.

family/gospel: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with family-oriented content or the gospel.

romantic: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with romantic feeling.

communication: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with communication (either in romantic terms or otherwise).

obscene: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with obscene content (money, rockstar-lifestyle, etc).

music: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with music (music about music, basically).

movement/places: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with movement or various locations.

light/visual perceptions: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the sun or other physical weather-related patterns.

family/spiritual: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the importance of family or spirituality.

sadness: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the importance of family or spirituality.

feelings: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with emotions, either positive or negative.

topic: The categorical label of lyrical content

age: A score from 0 to 1 expressing how “old” a song is from our perspective. 1 being the oldest, and 0 being the newest.

# Tools:

- Python 🐍

- Pandas 🐼

- Matplotlib 📊

- Seaborn 🌊

- Numpy 🔢

- Scikit-learn (Sklearn) 🤖

Report: https://github.com/dq93/Music_recommendation/blob/main/notebooks/report.ipynb
