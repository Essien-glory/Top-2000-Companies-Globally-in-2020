# Top-2000-Companies-Globally-in-2020
This Project shows the Global Ranking of the top 2000 companies in the world based on Revenue, Profit, Asset, and Market value as of 2020,  it also includes Global Rank, Country, Continent, latitude & longitude coordinates.

**DATA SOURCE**: kaggle.com
No data  cleaning required 

**TOOL: PowerBI**


The data consists of 
6 continents

60 countries

1924 companies

**DAX FUNCTIONS USED** (COUNT & IF)
COUNT to get the total number of companies ranked globally
 = count(Top2000CompaniesGlobally[Global Rank])
 
 ![Screenshot 2024-01-27 010649](https://github.com/Essien-glory/Top-2000-Companies-Globally-in-2020/assets/139914656/5e394253-e7b0-4d72-9748-dad2d5c371cd)

IF was used to get the profit size 
profit_size = IF(Top2000CompaniesGlobally[Profits ($billion)] < 1,"low","high")

![Screenshot 2024-01-27 010701](https://github.com/Essien-glory/Top-2000-Companies-Globally-in-2020/assets/139914656/f6c3bf77-6ecf-40e0-9605-e9c7886a3c3e)




**The following charts were used to visualize the dataset**
Multi row cards, Cards, table, Funnel chart, Column chart,
Line chart to show the trend overtime,
Slicers to filter,
Pie chart to show the comparison between 2 values,
And Maps to show the continent with the Highest Profit.


**VISUALIZATION**

1.Ranking top 1 in Sales is the USA with a total of $11,164 billion dollars.

With Walmart making the highest sales in 2020, followed by Royal dutch shell.

![Screenshot 2024-07-29 142034](https://github.com/user-attachments/assets/4976e175-31e8-4671-98f5-579c417bb897)

2.
![Screenshot 2024-07-29 140946](https://github.com/user-attachments/assets/c531d235-8af5-445a-8ae1-e5c1d70ca796)

3.
![Screenshot 2024-07-29 141000](https://github.com/user-attachments/assets/9b30169d-d447-4e1d-8397-d8d5274bbf1d)

4. In comparison, Total Asset generated is greater than the market value.

Total Sales made is greater than the profits made.
![Screenshot 2024-07-29 141015](https://github.com/user-attachments/assets/1e3c6b59-1212-4e05-a70a-2e8ccf8fbaa6)


**INSIGHTS**

Total Market value: $37,630 billion

Total Profit:  $2,359 billion

Total Assets:  $152,973 billion

Total Sales: $37,068 billion


1. Ranking top 1 in Country is the USA with a total of $11,164 billion dollars.

2. With Walmart making the highest sales in 2020, followed by Royal dutch shell.

3. North America made the highest Sales as of 2020, using the drill down button, you get to see the country with the highest sales and profit in that continent.

4. Exxon mobil makes above 4 billion dollars in profit and is number 1 in terms of profit , followed by apple.

5. A total of 1321 companies made a profit below 1 billion
6. 603 Companies made a profit aboove 1 billion

7. In Africa, South africa had the highest sales in 2020 

8. In comparison, Total Asset generated is greater than the market value.
9. Total Sales made is greater than the profits made.

10. Filled Map was used to higHlight the continent with the most Profit.
