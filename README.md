## Blocket car data

### Jonas Lundgren  
### Updated: 
            Jan 26, 2019
            Feb 02, 2019
            May 09, 2019
---

### Files
- `Webscraping_Cars.ipynb` Webscrapes https://www.blocket.se/ of cars for sale.
- `Blocket_Car_pySpark.ipynb` Contains data exploration using pySpark
- `blocket_carsYYYY-MM-DD.csv` Data scraped at YYYY-MM-DD


### Sources 

https://www.youtube.com/watch?v=XQgXKtPSzUI&t=0s&index=2&list=LLgrRgAlce_d0J02aHPrp4nA

University of California, Santa Barbara: PSTAT 135/235, winter quarter 2019

### Explanation
- Part 1: Webscraping of cars for sale in Skåne, Sweden from private sellers. Scraping is done from Swedish buy and sell site https://www.blocket.se/ using BeautifulSoup. Note: The data is not cleaned neatly and requier more work if it would be used.
- Part 2: Data preprocessing done using pySpark since I wanted to practice and was not necessary for a data set containing about 2500 rows (scraping done on Jan 26 2019). Visualizations are done using pandas and matplotlib.

#### Note: 
Formating of the webpage where the scraping was done could change if this is read at a later time.

---  
