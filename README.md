# Python_Data_Scraping_Webpage

# Project Title: NBA webscraping seasonal data 

In the current repository is an algorithm that help us scrape a webpage and find historical data from NBA


We are opening the website: https://www.basketball-reference.com/ and we extract 3 different tables, one with the teams standing, one with the players stats per season and one with the mvp votes.
We are extracting the informations for all the seasons from 1991-2020.
## DataQuest Challenge

This project was initially inspired by a challenge on DataQuest. The original challenge can be found [here](https://app.dataquest.io/m/99996/web-scraping-nba-stats-in-python/2/exploring-the-pages-to-scrape).

## Modifications

While the initial code and inspiration came from the DataQuest challenge, I have made several modifications and improvements to tailor the solution to my specific needs. These changes include (but are not limited to):

- Orginized the code and creating functions. That way the program could be used in any editor saving time
- Also, I have alter the opening of the html files so it will be more efficient
- Updating the reading of the html command using the StringIO, because the old method would not be valid in the future. 
  

## Dependencies

In order for the code to run correctly you need to create 3 folders inside the folder location where the program would stored. The folders should named: "team", "Player", "mvp". Inside this files would stored the html for each season.

## Credits

Many thanks to Dataquest (https://app.dataquest.io/m/99996/web-scraping-nba-stats-in-python/1/project-overview) and the instructor of the project (https://www.youtube.com/watch?v=JGQGd-oa0l4)

The github for the original code is here: https://github.com/dataquestio/project-walkthroughs/tree/master/nba_games
