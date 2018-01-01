# Scraping Reddit Metrics For Cryptocurrency Data

### About
Script to pull Subscriber Growth and Total Follower Count data from Reddit Metrics.

### Prerequisites
```
pip install BeautifulSoup  
pip install numpy 
pip install sklearn 
pip install matplotlib 
```

### Backstory

Reddit Metrics is a site, separate from Reddit, that has data on various subreddits. Such as Subscriber Growth, Milestones, etc...

I was curious to see if the Subscriber growth rate of a cryptocurrency held any predictive power for its future price. Take Bitcoin, for example. There does seem to be some predictive power, but the conclusion does not hold for the other coins. Blue is price, Red is Subscriber Growth Per Day, Green is Total Follower Count. All the data was normalized using sklearn.

![Bitcoin](https://user-images.githubusercontent.com/32149087/34464985-01708d8a-ee67-11e7-8a4b-312590050574.png)

Cheers. 
