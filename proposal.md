**Dataset**

The dataset is a TED Talks dataset found on [Kaggle](https://www.kaggle.com/miguelcorraljr/ted-ultimate-dataset) that has over 4000 talks, almost all of them in English. 
It has a column that has the transcription of each talk. Additional features of the dataset include: views, speaker, (speaker) occupations, recorded_date, published_date, 
event, available_languages, duration, (number of)comments, topics. 

Each transcript will be broken up in order to shorten each document somewhat. Possible break points could be (laughter) or (applause) phrases in each document. 

**Question(s)**
Topic modeling should answer the question of: 
- What are some of the topics that have been favorites at the TED Talks over the years? 

Later, further analysis could answer questions of: 
- How have (topic) trends changed over the years? 
- How about over geographies (given that these are recorded at different locations)?
- Do the topics / lengths of the talks have to do with the amount of engagement the talk generates? 

And a possible recommendation system could be: 
- Asking a user their set of interests, can we recommend a TED talk for them to watch? 

**MVP Goal**
- Do a topic modeling for the dataset. 
