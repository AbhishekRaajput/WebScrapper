# WebScrapper
A WebScraper that scrapes details of Batsmen of each team that played in a world cup.
Request package was used to make parallel requests to the server and Cheerio is used to extract data out of it
Nodejs fs module was used to create directories of each team and xlsx module is used to create excel file for each Player


Main.js
 This file contains the piece of code contains the main executable link which collects data from the website and converts it into readable form.
 All the other files are direclty linked with Main.js
 
Math1.js
  This piece of code works for a single match and collects the data.
  
AllMatch1.js
  This piece of code is basically a for loop for all single matches i.e. it collects data from all the required matches.
