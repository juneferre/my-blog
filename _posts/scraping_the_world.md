---

layout: post
title: "(Web) Scraping the World"
author: "June Ferre"
description: "A brief overview of the basics of webscraping using a trip budget website"
image: /assets/images/webscrape.jpg

---

### **Why Travel Costs?**

Traveling has always been an interest of humanity. However now, more than ever before, it is more accessible and affordable. I would also argue that social media has influenced an increase of travel as well, making it quite the hot topic and "cool thing to do". Like many, I have been interested in traveling since I was a little girl, dreaming of unique sights, architecture, art, and culture that traveling has to offer. While I've traveled some, my desire to explore the world continues. 

Many people would agree that traveling during college is a great time to travel due to flexibility. However, college can be expensive, as can traveling! So in an effort to better understand how much money should be allotted to saving for travels, I made a dataset that contains the [Wikipedia's 2018/2016 top 100 ranked Most Visited Cities](https://en.wikipedia.org/wiki/List_of_cities_by_international_visitors) and [Budget Your trip's](https://www.budgetyourtrip.com/) pricing information for the corresponding cities. 

<br><br>


### **What is the average amount Mid-Range budget travelers spend per day in the Top 100 Most Visited Cities in the world from 2016-2018?**

Before gathering my data, my question focused on one question, "What is the average amount Mid-Range budget travelers spend per day in the Top 100 Most Visited Cities in the world from 2016-2018?" However, since gathering the data, there are many more questions I've asked and will share with you further on in the post. 

<br><br>

### Ethics & Good Practice

#### **Wikipedia**

We scraped a Wikipedia table in class which felt like a green flag to scrape Wikipedia again, but just to be sure I read through the robots.txt file. 

#### **BudgetYourTrip.com**

I first read the robots.txt file which specified that it disallowed using the Search feature but nothing else. I then checked the [Privacy/Terms of Use](https://www.budgetyourtrip.com/termsofuse.php) which indicates scraping is prohibited unless you have written consent. To comply with their conditions, I emailed the provided email and explained what I was using the data for. They gave me written consent to scrape their data as long as I followed a few conditions.  

<br><br>

### **Web scraping basics**

I'm by no means and expert at web scraping, but I'll provide some basic yet helpful steps I took to start a project like this. 

#### **#1 Find a Source of Data**

Depending on the question you are trying to answer/topic you're interested in, this is arguably the hardest part of the process. During my search for data, I realized that real-world data hardly ever comes in a perfectly neat dataset with all the information you might need to answer your question. Infact, the data you do find rarely contains all the information you need, which means you will probably need multiple sources of data. Sometimes you find out your question just doesn't have accessible data, so if that's the case you might have to adjust your question tailored to data that is accessible. 

**Note**: Always check the Terms of Use and robots.txt file to ensure it is ethically scraped. 


#### **#2 Inspecting the Website**



- Overly detailed accounts are not required (and discouraged)

- Just provide enough info to help someone else potentially get started with a similar project

5. EDA highlights: summary statistics, summary graphics, and/or information about final dataset (e.g., total sample size, counts of categorical variables, numerical summaries of numeric variables)

- What are the most interesting findings of your EDA?

6. Links to find further information and /or resources

7. A link to your code in a separate GitHub repo
