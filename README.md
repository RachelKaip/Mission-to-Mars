# Mission to Mars
In this assignment we were introduced to instroduced to web scraping and various tools needed to access, extract, store and display the data.  With these tools we set out to create a site that would compile all of the latest news and information about the planet Mars from various sources into one place then update that data with a click of a button. 

We started by writing python scripts that leveraged BeautifulSoup and Splinter to visit and scrape data from other websites.  Becasue some of the data scraped were images, we thenstores the information in the non-relational databse, MongoDB.  We then created a Fask script that accessed that data and displayed it neatly on our site using HTML, CSS, and Bootstrap.   

While altering the index.html file to ensure the webpage was responsive to various devices, I also used Bootstrap to bold every heading and give the Mars Facts table Zebra stripes.  