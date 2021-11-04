# Mission-to-Mars

## Project Overview

The purpose of this project is to build a Web App that will scrape several websites for the most recent Mars data. The extracted data is stored in a NoSQL database (Mongo database) and then an HTML page is created to display the findings.


## Software
- Python 3.7
- splinter 0.14.0
- webdriver-manager 3.3.0
- Flask 1.1.2
- Flask-PyMongo 2.3.0
- BeautifulSoup (bs4) 0.0.1

## Scraping Mars Data
Selecting the "Scrape New Data" button will obtain the latest news, images, and facts about Mars. News titles and summaries are extracted from  NASA Mars Exploration Program News Website.The featured images are extracted from the Jet Propulsion Laboratory's Space Images  website and  Mars hemisphere images are extracted from Astropedia Website. Finally, the Mars facts are gathered from Galaxy Facts. 

![image](https://github.com/NadaAdem/Mission-to-Mars/blob/main/Resources/web.png)


### Mongo database is updated to contain the full-resolution image URL, title for each hemisphere image , News and update image .
![image](https://github.com/NadaAdem/Mission-to-Mars/blob/main/Resources/mongo.png)

## Add Bootstrap 3 components

### The webpage is mobile-responsive.

![image](https://github.com/NadaAdem/Mission-to-Mars/blob/main/Resources/phone.png) ![image](https://github.com/NadaAdem/Mission-to-Mars/blob/main/Resources/phone%203.png)

### Styling the "Scrape New Data" button

![image](https://github.com/NadaAdem/Mission-to-Mars/blob/main/Resources/web1.png)

### Adding the hemisphere images as thumbnails, like the image below

![image](https://github.com/NadaAdem/Mission-to-Mars/blob/main/Resources/hemisphere.png)
