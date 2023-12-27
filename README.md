# Youtube-Main-Idea-Classification-and-Popularity-Prediction
In this project I Determined whether it was possible to get both the main idea of a video, as well as the popularity of a vide obased off of its title. To Do this I obtained Data from Trending Youtube Video Statistics https://www.kaggle.com/datasets/datasnaek/youtube-new. I classified the data into six categories: Not Popular, Semi-Popular, Popular, Viral, Mega Viral, and Historically Viral. I prepared the data and then used the spaCy Library to attempt to find the main ideas of the youtube videos by finding the similarity in their tags' word vectors. I then trained and evaluated a Multinomial Naive Bayes classifier on the titles to determine their popularity.

The accuracy of the Main idea model came out to be,
~.02% for 5000 possible main ideas, and ~18000 titles

The accuracy of the popularity predictor model came out to  be,
~79% for 18000 titles, and 6 classifications

