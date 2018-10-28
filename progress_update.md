**PROGRESS UPDATE ON FINAL PROJECT**

I downloaded available PDFs of annual reports of issued EB-5 visas from the Travel.State.Gov website (2000 to 2017).

I used Tabula to extract the datasets I would use. I exported them as CSV files. I opened the files in Microsoft Excel individually and edited and organized the tables.

Most of the tables had six columns – one for country names, four for the number of each different type of EB-5 visa issued to each country, and one for the total number of the visas issued to each country. However, I only needed two columns from these, that is for the country names and the total number of EB-5 visas issued, so I removed the other four columns. I added another one for years to help in joining the data frames later. I renamed the two other columns from “Foreign State” and “Employ. Preference Total” to “country” and “total”, respectively.

The data was grouped in terms of continents. Some row entries were names of world regions. I removed them. Other rows had names of world regions and numbers of EB-5 visas issued for the regions. I removed these too. There were also rows for the grand totals of the visas issued. I also removed these.

The names of two divisions of China – Taiwan and “PRC nationals adjusting under CSPA” – were missing for some of the tables because they had a dash before them and were therefore being read as formulae. I put them inside parentheses and this got rid of the problem.

More editing and organization included putting inside one row parts of country names that Tabula had put in different rows.

The next step after this cleaning and formatting is joining the 18 datasets.