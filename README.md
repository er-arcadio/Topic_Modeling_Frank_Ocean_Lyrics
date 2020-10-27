# Topic_Modeling_Frank_Ocean_Lyrics

### Project 4 at Metis - ["This Repo"](https://github.com/er-arcadio/Topic_Modeling_Frank_Ocean_Lyrics)

**Objective: "What are some key phrases and concepts found in Frank Ocean's song lyrics?"**

In this NLP project, the plan was to scrape song writer, Frank Ocean's, song lyrics from the web to perform topic modeling and clustering on his Album "Blonde" and his entire discography. Afterwards, I plan on using Markov Chains to generate some sudo lyrics in order to foster inspiration. 


## Scraping and Cleaning the Song Lyrics

- Scrape the song lyrics from ["AZ lyrics"](https://www.azlyrics.com/f/frankocean.html)
- Clean the data and preprocess the lyrics for ease of use later on

**Files Refferenced**

[Scraping Song Lyrics Notebook](https://github.com/er-arcadio/Topic_Modeling_Frank_Ocean_Lyrics/blob/master/Scraping_Azlyrics_1.ipynb)


## Topic Modeling, Clustering, and Analysis Over Time 

- Topic model over the single album "Blonde" identifying the most frequent words Frank Ocean uses and extracting common ideas/topics
- Cluster the songs to analyze the dispersion of each topic. 
- Repeat the idea with the entire discography.
- Note: Vectorizing with TFIDF and Topic Modeling with NMF and Clustering with K-Means
- Analyze conclusions and graph the change in topic over time

**Files Refferenced**

[Topic Model, Clusters, and Conclusions Notebook](https://github.com/er-arcadio/Topic_Modeling_Frank_Ocean_Lyrics/blob/master/Topic_Model_Cluster_2.ipynb)


## Gernating Lyrics with Frequencies and Markov Chains

- Create a frequency table of the *X* number of words Frank Ocean uses. Then, *"roll"* a weighted *"X" sided die* that will output a word based on the likelihood of Frank Ocean using the word. Note: this generates uninterpretable sentences; it's quite naive.
- Use the concept of Markov Chains to produce more realistic text. 

**Files Refferenced**

[Lyric Generation Notebook](https://github.com/er-arcadio/Topic_Modeling_Frank_Ocean_Lyrics/blob/master/Generating_Lyrics_3.ipynb)

-----

Here's the [Presentation (pdf)](https://github.com/er-arcadio/Topic_Modeling_Frank_Ocean_Lyrics/blob/master/Presentation_p4.pdf)!

