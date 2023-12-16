# web-scraping-challenge: Module 11 Challenge Assignment
## [Part 1](https://github.com/lvit001/web-scraping-challenge/blob/main/Starter_Code/part_1_mars_news.ipynb)
- For part 1, all the code used was based on code learned in the BootCamp course. Did not require outside help.
- Successfully scraped code from the Mars New Website and used a for loop to extract the title and preview of the articles on the page.
- These titles and previews were added to individual dictionaries and then appended to a list.
- The list was printed out and the titles and previews were displayed as requested.
## [Part 2](https://github.com/lvit001/web-scraping-challenge/blob/main/Starter_Code/part_2_mars_weather.ipynb)
- Successfully scraped code from the Mars data table and used a for loop to extract all table elements.
- Since the elements all had the same tag `<td>` and no available id/class to distinguish them, set all of the `<td>` values in the data row equal to the list of variables `id, terrestrial_date, sol, ls, month, min_temp, pressure` as those were the column names in order.
- Created dictionaries for each row of data and appended these dictionaries to a list. The list was then turned into a data frame.
- Later on, defined functions to convert rows into either int64 or float64 datatypes for later analysis and visualization purposes.
- Proceeded to plot average min-temp and average pressures over the 12 martian months to determine which months had the highest/lowest temp & pressure. See graphs below:
- ![image](https://github.com/lvit001/web-scraping-challenge/assets/140283164/e8528497-8a37-4f6e-8320-513839cffac1)
- ![image](https://github.com/lvit001/web-scraping-challenge/assets/140283164/a2afca44-93a8-4900-9abc-f9a7dcc7494f)
- Additionally, plotted min-temp over the days that data was recorded on mars. See graph below:
- ![image](https://github.com/lvit001/web-scraping-challenge/assets/140283164/4277c293-9c0f-45d7-843a-351171669161)
- All three graphs aligned with the provided data analysis at the bottom of the file.



