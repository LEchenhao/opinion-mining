#Feature-Based Opinion Mining on Yelp Reviews

Jeff Fossett









1. Data is easy/quick to acquire

Disadvantages of this approach: 

1. Don't get to demonstrate my ability to scrape data to employers (though I have evidence of this elsewhere).



#### Sentiment Data: 

To train my sentiment analysis classifier, I will also need some tagged sentiment data. There are again several options: 

1. Contact author of original paper to see if he will share original data. 
2. Acquire comparable data from elsewhere: 
	* [Bing Liu](http://www.cs.uic.edu/~liub/FBS/sentiment-analysis.html#datasets)
	* [Movie Review Dataset](http://ai.stanford.edu/~amaas/data/sentiment/)
3. Create my own (domain-targeted) dataset using crowdflower or Mechanical Turk. 
4. Create my own dataset by hand (personally)

#### Static Aspect Extraction Data:

Need data to classifiy sentences as being pertinent to particular static aspects relevant to the restaurant domain (e.g. 'food', 'decor' etc.). About 1500 hand-labeled examples should suffice. This would take about a day to do by hand. Could also use crowdflower/mechanical turk.

##Analysis & Presentation











* **Combining Static & Dynamic Aspect Extraction**: See original paper for heuristic approach to this. 
	
**Summarization & Presentation**: 



* [Building a Sentiment Summarizer for Local Service Reviews](http://www.ryanmcd.com/papers/local_service_summ.pdf)
* [Opinion Mining, Sentiment Analysis, and Opinion Spam Detection](http://www.cs.uic.edu/~liub/FBS/sentiment-analysis.html) (Bing Liu)
* [Sentiment Symposium Tutorial](http://sentiment.christopherpotts.net/) (Chris Potts)
	* [WordNet Propogation](http://sentiment.christopherpotts.net/lexicons.html#wnpropagate)