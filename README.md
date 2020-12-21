# Introduction
A python notebook that uses Pushshift API to crawl content from Reddit.

## :ledger: Index

- [About](#beginner-about)
- [Usage](#zap-usage)
  - [Instructions](#package-instructions)
- [Resources](#page_facing_up-resources)
- [Credit/Acknowledgment](#star2-creditacknowledgment)

##  :beginner: About
Just a simple python notebook.

## :zap: Usage
1. Clone or download this project.
2. Open redditCrawler.ipynb in Jupyter Notebook or VSCode (minimally with Python 3.6).


###  :package: Instructions
- Modify params in fetchObjects function as desired.
- Modify or remove start timestamp as desired.
- Modify the subreddit and mode arguments as desired in the extract_reddit_data function call.
- Run resumeFromLast to resume in the case that crawling stops unexpectedly.


##  :page_facing_up: Resources
Pushshift Reddit API: https://github.com/pushshift/api


## :star2: Credit/Acknowledgment
Code was built upon the original code in this article:
https://www.osrsbox.com/blog/2019/03/18/watercooler-scraping-an-entire-subreddit-2007scape/

