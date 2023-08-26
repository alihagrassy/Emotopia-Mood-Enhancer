# Emotopia-Mood-Enhancer
# The project consists of four main steps:

# 1- Emotion detection: 
using a pre-trained model to detect the user’s emotion from their facial expression and also to know his name if it exist in the database.

# 2-a voice assistance works as a therapy : 
it asks questions based on your facial expression and transcribe the words 

# 3-Mood Classification:
we have used BEFT transformer to work as a mood classifier from 7 moods: (Happy, Sad, Fear, Angry, Joy, Love, Neutral)

# 4-Music recommendation: 
Recommendation works in 2 different phases both have pros and cons:

# the first method :
we used Spotify Recommendation system and use scrapping technique. then we use a custom algorithm to recommend a song that matches the user’s emotion and preference .
cons non automatically running the music.

# the second method:(more automation technique):
a folder that holds a music folder which is works as a playlist and run this folder the music launches.
cons we had to remove Spotify recommendation system since the system takes longer time to generate music which results into removing music preference but kept the emotion.

