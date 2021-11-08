**Analyzing the Transcripts of TED Talks**

From my topic modelling, I got the following topics: 
- Topic 0 is CITIES 
- Topic 1 is TECHNOLOGICAL DEVELOPMENTS
- Topic 2 is SLEEP / LIFE IN THE DIGITAL AGE
- Topic 3 is MEDICINE
- Topic 4 is FAMILY + COMMUNITY
- Topic 5 is PLAY
- Topic 6 is CLIMATE CHANGE
- Topic 7 is DIGITAL
- Topic 8 is EDUCATION
- Topic 9 is POLITICS
- Topic 10 is EARTH SCIENCES
- Topic 11 is RELATIONSHIPS + SEX(ES)
- Topic 12 is CULTURE + FEELINGS
- Topic 13 is OCEANS/ WATER CULTURE
- Topic 14 is (ORAL) CULTURE

These topics are derived by using a CountVectorizer (compared with the TDIDF model and chosen for better initial results), with tuned parameters of 
stop words, ngrams, token_pattern, max_df, min_df and an LDA topic modeler (compared with NMF and LSA modellers), with tuned parameters of n_components, doc_topic_prior, topic_word_prior, max_iter. 

Here are the plLDAvis visualizations for 4 of the topics and lastly, a word cloud representation of those topics: 
![Topic1](https://user-images.githubusercontent.com/81533137/140824744-2eac1dc8-9ddd-45c3-b6b6-073802281242.png)
![Topic2](https://user-images.githubusercontent.com/81533137/140824749-13359a14-f793-497e-bcf0-6138ff3916e0.png)
![Topic3](https://user-images.githubusercontent.com/81533137/140824753-bbe2f111-4fc8-49d2-88e5-b042d9941002.png)
![Topic4](https://user-images.githubusercontent.com/81533137/140824756-5d006358-f047-4e90-a6f2-52bd80415899.png)

![wordcloud](https://user-images.githubusercontent.com/81533137/140825607-010c8f51-3c35-4d9a-bfe4-794d40af6c00.png)
