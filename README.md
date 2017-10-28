# Frame Analysis

## Data Sources

* Google Big Query
  * [Reddit Comments](https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_comments)
  * [Hacker News Comments](https://bigquery.cloud.google.com/dataset/bigquery-public-data:hacker_news)
* TV News Archive maintains closed captions for , e.g., [search for "bitcoin tulip"](https://archive.org/details/tv?q=bitcoin%20tulip) (Would need to pull a split by segment. Closed caption data is also noisy with misspellings. Might have to adjust detection model for common captioning errors).
* Is there a news article database?

## Resources and Artcles

* [Metaphors We Live By](https://www.amazon.com/Metaphors-We-Live-George-Lakoff/dp/0226468011): primary text on how metaphor is infused with language and thinking 
* [Sapiens: A Brief History of Humankind](https://www.amazon.com/Sapiens-Humankind-Yuval-Noah-Harari/dp/0062316095/): argues that shared myths are what enable humans to coordinate at a massive scale
* [Frameworks Institute](http://www.frameworksinstitute.org/): Non-profit studying and advising on framing
* [Decision Traps: The Ten Barriers to Decision-Making and How to Overcome Them](https://www.amazon.com/Decision-Traps-Barriers-Decision-Making-Overcome/dp/0671726099/): Part 1 is on Decision Framing
* [Metaphors We Compute By](https://cacm.acm.org/magazines/2017/10/221316-metaphors-we-compute-by/abstract): CACM article on how metaphors are used in software design

## Related Research and Analyses

* [How people talk about marijuana on Reddit: a natural language analysis](https://hackernoon.com/how-people-talk-about-marijuana-on-reddit-a-natural-language-analysis-a8d595882a7a)
* [Proceedings of the Third Workshop on Metaphor in NLP](http://aclweb.org/anthology/W/W15/#1400)

## Research Questions

* How do the dominant frames (most upvotes) vary across communities?
* How do the dominant frames evolve within a community over time?
* How often do community members change their frame? How does this correspond to frame dominance within the community?
* Can word embeddings (e.g., word2vec) be used to improve metaphor detection? If we ran clustering, would we find the same set of frames we manually identify?
