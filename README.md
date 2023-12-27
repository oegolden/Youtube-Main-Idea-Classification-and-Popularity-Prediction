# Youtube-Main-Idea-Classification-and-Popularity-Prediction
In this project, I determined whether it was possible to get both the main idea of a video and the popularity of a video based on its title. To Do this I obtained Data from Trending Youtube Video Statistics https://www.kaggle.com/datasets/datasnaek/youtube-new. I classified the data into six categories: Not Popular, Semi-Popular, Popular, Viral, Mega Viral, and Historically Viral. I prepared the data and then used the spaCy Library to attempt to find the main ideas of the YouTube videos by finding the similarity in their tags' word vectors. I then trained and evaluated a Multinomial Naive Bayes classifier on the titles to determine their popularity.

The accuracy of the Main idea model came out to be,
~.02% for 5000 possible main ideas, and ~18000 titles

The accuracy of the popularity predictor model came out to  be,
~79% for 18000 titles, and 6 classifications


Here is the link to the Google Drive of the data sets, import them into the same folder as the Jupyter Notebook, and you can run it: https://drive.google.com/drive/folders/1bb5K0Lej_0GkTrVq-Dbcyx2LeHn1-Laa?usp=sharing
