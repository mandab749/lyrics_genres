## Predicting Song Genre using Naive Bayes

##### Data Description:
- 380,000+ lyrics from the website MetroLyrics.com
- Columns: Name of Song, Year, Artist, Genre, and Full Lyrics of Song
- 10 different Genres
- Year range: 1960-2016
- link to full data: https://www.kaggle.com/gyani95/380000-lyrics-from-metrolyrics/data

##### What is in each folder?

- Data Prep:   
       - Cleaning the data and doing word tokenization   
       - lemmatizing the words   
       - saving it to a csv (saved csv is named lyrics_final).   
- EDA: Exploratory Data Analysis to familiarize myself with the dataset.    
- Predicting:
    - splitting train & test data   
    - applying TFIDF vectorization to the lyrics   
    - predicting genres using Naive Bayes   
    - resulting confusion matrix of misclassifications   
    - proving ideas for future analysis
