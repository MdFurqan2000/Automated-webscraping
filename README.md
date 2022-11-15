# Automated WebScraping
An Automated flipkart mobile phones Webscraper which scrapes price, brand Titles.

In this project I used an autoscraper to automate the scraping of different products and brands.


## Steps
1. instal Autoscraper.

$ pip install autoscraper


2. Import Autoscraper.

from autoscraper import AutoScraper


3. Now paste the URL.

flipkart_url="https://www.flipkart.com/search?q=iphone&as=on&as-show=on&otracker=AS_Query_OrganicAutoSuggest_4_2_na_na_na&otracker1=AS_Query_OrganicAutoSuggest_4_2_na_na_na&as-pos=4&as-type=RECENT&suggestionId=iphone&requestId=ee9e2a8d-3607-4d99-8a1a-c8cb16832257&as-searchtext=ip"


4. Create a wanted list.

wanted_list=["APPLE iPhone 11 (Black, 128 GB)","₹45,990"]


5. Build the scraper.

scraper=AutoScraper()
result=scraper.build(flipkart_url,wanted_list)


6. Now you can print the result.

print(result).
