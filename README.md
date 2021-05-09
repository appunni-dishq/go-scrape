# go-scrape
A Distributed large scale scraper written using GoLang

### Motivation

This is a project I have been wanting to do in Golang for so long, after using Python for it I understood the pain points in web scraping. This project is built as a far better solution for the issues persisted in python.

### Features Provided by the project as of Alpha v0.0.1

1. Config based scraping
2. Regex based crawling
3. Monitoring
  - Health per Website
  - Success rate per website
  - Error classified per type
4. Distributed logging
5. Kubernetes Deployment support from Day 1
6. Ability to connect to multiple data sinks (Kafka, File, Google Spread Sheet)
7. Schema validation for each data scraped
8. Data Structure supports : Nested Tables, List, String, DateTime, Integer, Float, Hash Maps

### Future features planned 

1. Ability to add machine learning on top of Crawling link discovery (Automates Crawling)
2. Ability to automate per Domain (Food, Finance, Stocks)
3. Domain discovery per Domain , Category and Per Country (Food, Recipe, United States)



