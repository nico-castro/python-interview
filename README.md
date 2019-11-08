# python-interview
A Python interview question for prospective python engineering candidates

## Question
First, create an Episode class that has the following fields:
  Airdate - (datetime) Datetime when the episode aired
  Description -  (str) The full description of the episode
  GUID - (str) Globally unique ID for the episode
  Link - (str) A link to the specific episode
  Tags - (list) A list of tags
  Title - (str) Title of the episode
  
Second, parse the Radiolab feed - https://www.wnycstudios.org/feeds/series/podcasts?limit=150 - into 
a list of episodes.

Third, the ouput of the main function should be the titles of all of the episodes. 

## Useful Tidbits
`feedparser` is a library that is commonly used to parse feeds in python - https://pythonhosted.org/feedparser/


