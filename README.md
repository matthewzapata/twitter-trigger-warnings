# Twitter Trigger Warnings
This project's goal is to create a model that can determine if a movie or TV show has a scene of self harm in it.

The data sources for this project were Twitter, IMDB, and Tumblr:
[Twitter](https://www.twitter.com)
[IMDB](https://www.imdb.com/chart/moviemeter?ref_=nv_mv_mpm)
[Tumblr](https://istheresuicideinit.tumblr.com/)

Data was obtained from these sources using BeautifulSoup and Selenium. Specifically, BeatifulSoup was used to scrape IMDB and Tumblr, while Selenium was used for Twitter due to it being able to handle infinite scrolling.