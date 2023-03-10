# KNN-Classification-BookPurchase


My goal for this passion project (since I love books and reading!) was to make and start with a simple Machine Learning Algorithm, the classification one with KNN.

Some items I can highlight by having done this project:

- I created the dataset, and I started to dig into concepts as 'Data Strategy', or for example in the cleaning fase, which was the best option for the data that was null? I had some other features as 'Año Leido' or 'Rating' which had only a few rows filled with values, since I haven't read the majority of the books in the dataset yet, but I have them bought. So I decided to delete those features which weren't relevant for my analysis (at least for now).
-I performed Feature Encoding with LabelEncoder, since I was getting an error because I was working with text data and not numerical. When trying this, I encountered that there were other tools to help me do it, such as one-hot encoding. It's something that I really want to focus on when doing my next projects, that is to experiment more with data preprocessing and cleaning tools, to see which one works better with my models.
- I got a warning message while making the model, and that is that some of my labels have no predicted samples so the precision and F-score for those labels are undefined and have been set to 0.0. I have already began investigating into this, and considering adding more data, use a different evaluation metric or a more robust classification algorithm like random trees.

Feedback is more than welcome :)
