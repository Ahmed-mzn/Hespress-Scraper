# Hespress-Scraper

# Description 
This code scrape all posts of Hespress.com and save it on excel file.
you can choose number of page to scraping by change the param NUMBER_OF_PAGES probably from 1 to 29423 it's augmented evrytime so you need to check Hespress.com, from this url : 
[https://www.hespress.com/?action=ajax_listing&paged=1&tq=MjAyMi0wNC0wNiAwMDowNTowMA%3D%3D&all_listing=1] (https://www.hespress.com/action=ajax_listing&paged=1&tq=MjAyMi0wNC0wNiAwMDowNTowMA%3D%3D&all_listing=1)
and change the param paged in the url to any number you want to check.

## Requirements :

Just install the requirements by executing those cmds

```bash
$ pip install beautifulsoup4
$ pip install lxml
$ pip install requests
$ pip install openpyxl
```
