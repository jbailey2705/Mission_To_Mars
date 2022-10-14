# Mission_To_Mars

## Project Overview
The purpose of this project was to build a Web App that will scrape several websites for the most recent Mars data. The extracted data is stored in a NoSQL database, & a HTML page is generated to display our findings.

## Software
- Python 3.7
- splinter 0.14.0
- webdriver-manager 3.3.0
- Flask 1.1.2
- Flask-PyMongo 2.3.0
- BeautifulSoup (bs4) 0.0.1
- html5lib 1.1
- lxml 4.6.3

## Web Scraping Mars data from NASA using Jupyter Notebook
BeautifulSoup and Splinter were used to automate the web browser & perform a web scrape of the sites.

![Screen Shot 2022-10-14 at 8 02 59 AM](https://user-images.githubusercontent.com/109354592/195853860-979a15d1-c31a-479b-abde-07f1714f2add.png)

## Updating the Web App
Bootstrap 3 components, allows us to show the four Mars hemisphere images side-by-side on Desktop browsers, instead of a line. This allows users to see all four images at once.

![Mars Hemispheres](https://user-images.githubusercontent.com/109354592/195853141-126e1c85-7c36-44d8-8510-44bdf1006db4.png)

End result was a fully-functional web application creted with Flask that included images, table with information about Mars in comparison to Earth, and the latest article title and short description scraped from the NASA's webpage. Each time we click on the "Scrape New Data" button new information will be updated on both the website and the MongoDB.

## Code:
- HTML code: [index.html](https://github.com/jbailey2705/Mission_To_Mars/tree/main/HTML#:~:text=.%E2%80%8A.-,index.html,-Add%20files%20via)
- Scraping script: [scraping.py](https://github.com/jbailey2705/Mission_To_Mars/tree/main/HTML#:~:text=.%E2%80%8A.-,index.html,-Add%20files%20via)
- APP script: [app.py](https://github.com/jbailey2705/Mission_To_Mars/tree/main/HTML#:~:text=.%E2%80%8A.-,index.html,-Add%20files%20via)
