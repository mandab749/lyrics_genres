## Predicting Song Genre using Naive Bayes

##### Data Description:
- 380,000+ lyrics from the website MetroLyrics.com
- Columns: Name of Song, Year, Artist, Genre, and Full Lyrics of Song
- 10 different Genres
- Year range: 1960-2016
- link to full data: https://www.kaggle.com/gyani95/380000-lyrics-from-metrolyrics/data  
- link to powerpoint: https://docs.google.com/presentation/d/1EhT8-WtQ6U8qXPrslITmv8keqQyuBGkdhvhMWYL7kR4/edit?usp=sharing

##### What is in each folder?

- Data Prep (Part 1):   
       - Cleaning the data and doing word tokenization   
       - lemmatizing the words   
       - saving it to a csv (saved csv is named lyrics_final).     
       
- EDA: Exploratory Data Analysis to familiarize myself with the dataset.     

- Predicting (Part 2):  
       - splitting train & test data   
       - applying TFIDF vectorization to the lyrics   
       - predicting genres using Naive Bayes   
       - resulting confusion matrix of misclassifications   
       - proving ideas for future analysis
