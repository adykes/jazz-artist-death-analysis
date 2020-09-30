# jazz-artist-web-scraper

This project is a webscraping, data cleaning, and data analysis project on basic biographical information about jazz musicians. 
As a listener and musician of jazz and its related / descendant styles, I've always been fascinated with the lives of jazz musicians 
and how we understand jazz culture now, in the 21st century. A popular stereotype about jazz musicians that is often circulated is
that jazz musicians overwhelmingly die from either drug overdoses or the direct effects of lifetimes of drug abuse. To investigate this, 
I have thought up this project. The main purpose of this project is to collect basic biographical data on jazz musicians (most importantly
their lifespans) and run some basic analysis on the data to extract trends that may or may not support the above thesis about the 
lifestyles of jazz musicians. 

As of the time of writing (9/24/20), I've only completed collecting and cleaning the data on jazz pianists. I will keep a separate file 
in this repository that will show the progress I make over time. I will also update this document with technical details as I clarify some
of the processes and methods that I use for this project. 

**First**, I am going to scrape the pages of lists of jazz musicians from Wikipedia for basic biographical data. For now, those pages are
:
- Pianists: https://en.wikipedia.org/wiki/List_of_jazz_pianists
- Bassists: https://en.wikipedia.org/wiki/List_of_jazz_bassists
- Clarinetists and Flouists: https://en.wikipedia.org/wiki/List_of_jazz_musicians (may do this manually as there aren't enough clarinetists or flutists to make it
worth my time to write a separate webscraper)
- Drummers: https://en.wikipedia.org/wiki/List_of_jazz_drummers
- Guitarists: https://en.wikipedia.org/wiki/List_of_jazz_guitarists
- Organists: https://en.wikipedia.org/wiki/List_of_jazz_organists
- Saxophonists: https://en.wikipedia.org/wiki/List_of_jazz_saxophonists
- Trombonists: https://en.wikipedia.org/wiki/List_of_jazz_trombonists
- Trumpeters: https://en.wikipedia.org/wiki/List_of_jazz_trumpeters
- Vibraphonists: https://en.wikipedia.org/wiki/List_of_jazz_vibraphonists
- Violinists: https://en.wikipedia.org/wiki/List_of_jazz_violinists
- Vocalists: https://en.wikipedia.org/wiki/List_of_jazz_vocalists

A couple of notes about this list
:
- I have included a couple of instruments that are less commonly associated with jazz as a genre. I am mainly doing this to see if there are any interesting trends
among the players of these instruments. However, the data will be less trustworthy as there just aren't that many musicians who play these less common instruments. 
- As this project only considers musicians that are listed on Wikipedia, it will most likely leave out many musicians. I am sorry if your favorite jazz musician
is not included in these lists. Feel free to let me know about this or open up a pull request to add some data. 

I will also do some preliminary data cleaning in Python. 

**Second**, I am going to clean the data in Excel to correct for any errors in the scraping process. While I recognize that in a real-world data analysis project, 
most of the data cleaning would take place in a scripting language, the data here is just too unreliable to be cleaned efficiently in Python. Furthermore, I am 
also going to add the causes of death of each jazz musician to the table, which is something that must be done by hand anyways. 

**Third**, I am going to use SQL and Tableau to analyze and visualize the data, once it's all cleaned and normalized. I am deciding to do the analysis and visualization 
using SQL and Tableau mainly because I need practice in these two technologies. However, I may use Python to create more nuanced visualizations, as I only have the free
version of Tableau and am limited in my freedom to export my visualizations. 

**Fourth**, I am going to publish an article (most likely on Medium), showing my findings. This article will contain a nuanced discussion of my methodology and 
analysis. 

**Fifth and Beyond**, I am going to use the data I've collected to train a machine learning model to generate fake jazz musicians. This step will be a separate project 
from the initial purpose of this project, and will require much more data to be collected. To be specific, I want to create a machine-learning "bot" that will use the 
data I collect to generate a name, instrument, dates, cause of death, genre of jazz, and names of compositions by that fake musician. 

An important disclaimer: All of the data I collect will be from Wikipedia. Obviously this is a flawed approach, as it is impossible to verify the accuracy of 
data on Wikipedia. However, this project is by no means meant to be an authoritative source; rather, this is just a project I am passionate about. I think I will 
find interesting trends and patterns in this data that could reflect reality to some degree, but my data and the analysis I draw will not be peer-reviewed or 
critically examined for major methodological flaws. Please keep this in mind when considering my project. That being said, I would love to hear from anyone and everyone
on how I could improve as I am a novice to data analysis and data science. Feel free to email me at audendykes@gmail.com with any comments or concerns.

Thanks for checking it out! 







