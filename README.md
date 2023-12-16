# web-scraping-challenge: Module 11 Challenge Assignment
## Part 1
- For part 1, all the code used was based on code learned in the BootCamp course. Did not require outside help.
- Successfully scraped code from the Mars New Website and used a for loop to extract the title and preview of the articles on the page.
- These titles and previews were added to individual dictionaries and then appended to a list.
- The list was printed out and the titles and previews were displayed as requested.
## Part 2
- Successfully scraped code from the Mars data table and used a for loop to extract all table elements.
- Since the elements all had the same tag `<td>` and no available id/class to distinguish them, set all of the `<td>` values in the data row equal to the list of variables `id, terrestrial_date, sol, ls, month, min_temp, pressure` as those were the column names in order.
- Created dictionaries for each row of data and appended these dictionaries to a list. The list was then turned into a data frame.
- Later on, defined functions to convert rows into either int64 or float64 datatypes for later analysis and visualization purposes.
- 
