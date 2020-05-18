<img src="https://bit.ly/2VnXWr2" width="100"/>

# 420
Zahid Sánchez Barrón

DAPT CDMX March 2020

## Content
- [Introduction](#introduction) 
- [Aproach](#aproach)
- [Aproach](#aproach)
- [Challenges](#challenges)
- [Links](#links)

<a name="introduction"></a>

## Introduction
Recopilation of Marijuana products, with detailed strain information. Data was retrived from strains.evanbusee.com API and from leafly.com. Different csv are available in extra_csv folder.

<a name='aproach'></a>

## Aproach
Data from API was downloaded and turned into 3 different csv.
Scraping process used two different classes, one for scraping flowers and other for scarping strains. Each class scraped twice, first time to get links and second time to get the info. Data was saved to "strain.csv","products.csv", those were merged into a complete leafly dataframe, this dataframe was mreged with the API df, was cleaned and saved into a csv called "weed.csv".

<a name="challenges"></a>

## Challenges
Asyncio was difficult to understand and implement, it reduced considerably scraping time.

<a name="links"></a>

## Links
[API Documentation](http://strains.evanbusse.com/) |
[Leafly](https://www.leafly.com/)