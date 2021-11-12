## TED Talks Over the Years

**Abstract**

This project works with a corpus of 4005 TED Talk transcripts to do topic modeling on the documents. It uses CounterVectorizer() and LDA to come up with 15 distinct topics and attaches the topics back to the original dataframe on which further analysis is done to see how the topics have shifted over the years as well as in relationship to viewership and commentary. The last two are engagement metrics which are important to gauge in the context of different topics from the perspective of the conference. In the end we found out that there were certain topics that were not as heavily engaged with later in time: Climate Change, Education, Design / Ideas, Tech Developments/ Ideas and some that were on the rise: Gender / Feminism(s), Medicine.

**Design**

The project aimed to study the TED talks given and uploaded to the website over the years to see which different topics the talks were given in, and how user engagement as measured by views & commenting changed over the years. The TED talks transcripts were preprocessed and then with the use of a vectorizer & topic modeler split into topics. The resulting 15 topics were: CLIMATE CHANGE, COMMUNITY, GLOBAL POLITICAL ECONOMIES, GENDER / FEMINISM(S), CITIES, EDUCATION, MEDICINE, FOOD SYSTEMS, DESIGN / IDEAS, (ORAL) CULTURE, BRAIN / ANIMAL, BUSINESS / ECONOMIES, GAME / META, TECHNOLOGICAL DEVELOPMENTS / DIGITAL, ENERGY / EARTH. Of these, one was selected (GENDER / FEMINISM(S)) to further analyze and interpret in detail. 

**Data**
- The dataset is a TED Talks dataset found on Kaggle that has over 4000 talks. 
- The dataset has a column that has the transcription of each talk. A typical document is around 3000 words; in terms of characters the mean of the talks is around 10K characters. 
- Additional features of the dataset include: "views, speaker, (speaker) occupations, recorded_date, published_date, event, available_languages, duration, (number of)comments, topics".
- Of these, year, views & comments were heavily relied upon at metadata after the topic modeling to analyze how the topics have changed over time in terms of importance and viewer engagement. 

**Algorithms**
- Text preprocessing
- CountVectorizer, TF-IDF compared
- With CountVectorizer: stop_words, token patterns, max_df, min_df, n_gram were tuned.
- LDA, NMF, LSA compared 
- With LDA: n_components, learning_method, theta, beta, doc_topic_prior, topic_word_prior, max_iter were tuned. 
- KMeans for initial clustering (very basic) 
- Rec- sys looking at cosine similarities between documents
- Interpretation: topics were analyzed as a percentage and overall  
- Interpretation: topic importance was analyzed over the years
- Interpretation: views overall & per topic (& per topic per video) were analyzed
- Interpretation: comments overall & per topic (& per topic per video) were analyzed
- One of the topics (Feminisms) was analyzed further in detail to see how the topics importance has shifted over the years by looking at the number (and percentage) of talks, number (and percentage) of video views & number (and percentage) of comments. 

**Tools**
- Pandas & Numpy for EDA
- Matplotlib, Seaborn, WordCloud and pyLDAvis for Visualization 
- Scikit-learn for modeling

**Communication**

The project was presented with a slideshow in which topic modeling and later interpretations & analyses were narrated. 
