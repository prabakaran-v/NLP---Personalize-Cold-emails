# Personalize Cold emails using NLP & Deep Learning

![personalization_heading](https://user-images.githubusercontent.com/46706767/58305746-d9cd4700-7e16-11e9-95ef-da5386728ce3.png)


In account-based B2B sales, effectiveness in getting quality leads depends on powerful research about the prospects and personalizing the reachout with quality information. It is said "Personalizing that first outreach can make the difference between a sale and a dead end."

This project focusses on identifying the opportunities in US Retail Industry for Analytical services and Digital Transformation. In order to write personalized emails, the intelligence on a prospect/account is gathered from various news articles published in a well known website [www.retaildive.com](www.retaildive.com)(the website covers all the latest trends in US Retail). B2B sales folks working in IT/Analytics firms(under Retail vertical) can use the intelligence to grab the attention of the potential prospects easily.

In future, if a tool/platform is developed based on this prototype, a news article entering the platform will be first webscraped, cleaned and then will be segregated into any of the given topics based on its context. Next the platform will check for its 'usefullness' to the domain the sales team/business engaged in. If it is found to be useful, the platform extracts a summarized version of the article to be used for personalizing the sales pitch. <i>Identifying such useful intelligence about a particular prospect will be done in a matter of seconds, saving a lot of time, manpower and sales cycle.</i> 

This project consists of 5 parts:
 <br/><b>Part 1 - Web Scraping:</b> Articles are scraped using BeautifulSoup and the final content along with title are converted into a dataframe
 <br/><br/><b>Part 2 - Data Cleaning & Visualization:</b> Text preprocessing is done using NLTK and spaCy. A WordCloud visualization is plotted to identify the context/important words in each article
 <br/><br/><b>Part 3 - Topic Modelling:</b> Articles are segregated into 4 topics/categories using Latent Dirichlet Allocation(LDA) algorithm from Gensim package. The topics identified are (a) Quaterly news/Press release, (b) Techonology/Digitilization, (c) Loyalty Program/Marketing and (d) Supply Chain/Management changes
 <br/><br/><b>Part 4 - Text Classification:</b> Using algorithms like Naive Bayes, SVM and LSTM, articles are classified according to the 'usefullness' factor to the domain i.e. to identify whether a particular article will be useful for a sales folk to be used for personalizing his email pitch.
 <br/><br/><b>Part 5 - Text Summarization:</b> Using TextRank algorithm, we get an extractive summarized version of the articles. The key sentences identified in the entire document can be used in cold emails for a personalized reachout.


