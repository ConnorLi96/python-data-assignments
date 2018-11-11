
# Assignment 1 -- Data collection and ideation

## Topic and summary
  - The data journalists' information and their contributions information on Github
  - We find a website there are many different individual information about data journalists, we decide to scrape all existing information for further data journalism study. Right now, the process divided two parts ```Orginal Website``` and ```Github Scraper and Analysis```. We want to use this data to study below points.
      - The importance of coding for data journalism
      - The post content in their Twitter account
      - Find out the gap between work requirements and data journalist's coding ability.


## Orginal Website
### Data source
  - http://jplusplus.github.io/global-directory/
### Data fields (type, sample data); 
  - ```Name``` - String. e.g. ```Justin Myers```
  - ```Institution``` - String. e.g. ```The Associated Press```
  - ```Location``` - String. e.g. ```United States, Brooklyn (US-VA)```
  - ```Github adress``` - String. e.g. ```http://github.com/myersjustinc```
  - ```PGP adress``` - String. e.g. ```https://martingonzalez.net/assets/key.asc```
  - ```Mail adress``` - String. e.g. ```mailto:julius.troeger@morgenpost.de	```
  - ```Twitter adress``` - String. e.g. ```http://www.twitter.com/juliustroeger	```
  
  - The result is in [Result.csv](https://github.com/ConnorLi96/python-data-assignments/blob/master/assignment1/Data_Journalism.csv)
  - The codes is in [Assignment01.ipynb](https://github.com/ConnorLi96/python-data-assignments/blob/master/assignment1/Assignment01.ipynb)
### Data volume
  - 217 rows × 8 columns
  - 217 data journalists's information, including their names, institutions, locations, github adress, PGP adress,Mail adress,Twitter adress

 
  
## Github Scraper and Analysis

### Data source
  - All of links are from above data cleaning (87 links)
### Data fields (type, sample data); 
  - ```Name``` - String. e.g. ```Justin Myers```
  - ```How many days the have contributions``` - String. e.g. ```40```
  - ```The number of Wholeyear_contributions``` - String. e.g. ```825```
  - ```The date of Last_contributions``` - String. e.g. ```2018-09-08```
  
  - The result is in [Result.csv](https://github.com/ConnorLi96/python-data-assignments/blob/master/assignment1/Github_Analysis.csv)
  - The codes is in [Assignment01.ipynb](https://github.com/ConnorLi96/python-data-assignments/blob/master/assignment1/Assignment01.ipynb)
### Data volume
  - 87 rows × 3 columns
  - The Github information (including:How many days the have contributions;The number of Wholeyear_contributions;The data of Last_contributions) in 87 data journalists who have github account. We want to know how many data journalists still coding.
  
### License
  - CC 4.0
