# In-Game Purchases Analysis
Heroes of Pymoli

To run the code, simply open the 'Store_Analysis" folder and open the .ipynb file within that folder. 
Then, press each right-pointing play button, located to the left of each cell.

My aim in the project was to find which genders and ages of buyers, as well as which in-game store items, brought in the most money for the game "Heroes of Pymoli".
I used pandas, numpy, and Jupyter Notebook to do this.

I counted the total number of buyers,
the total number of unique items, the average item price, the total number of purchases made, and the total revenue gathered.
![image](https://user-images.githubusercontent.com/73863977/120050623-93a1b400-bfeb-11eb-8b3b-5dc86c077c36.png)

I also calculated the numbers of male, female, and non-disclosed-gendered buyers and the percentages of the buyer population which each of those demographics constituted.
![image](https://user-images.githubusercontent.com/73863977/120050631-9d2b1c00-bfeb-11eb-9045-e8df4832ca3e.png)

For male buyers, I calculated the total purchase count, the average purchase price, the total revenue gained, and the average value which each player paid. I repeated these analyses for female and for non-disclosed-gendered buyers. The results for all genders are in this table:
![image](https://user-images.githubusercontent.com/73863977/120050643-a9af7480-bfeb-11eb-9330-7dffaab930b8.png)

I binned the buyers by age into one bin of buyers 9 and under and nine other bins of 4 years-width each. For each bin, I counted the number of buyers and the percentage of the total buyer population which that bin represented.
![image](https://user-images.githubusercontent.com/73863977/120050655-b2a04600-bfeb-11eb-872a-10906efb39c9.png)

For each age bin, I then found the total purchase count, the average value paid by each player, the total purchase value generated, and the average purchase price/person.
![image](https://user-images.githubusercontent.com/73863977/120050671-baf88100-bfeb-11eb-8124-f30ed72c2e47.png)

I then sorted the entire set of buyers by the numbers of purchases made and identified the IDs, names, purchase counts, average amount paid, and total amount paid by each of the buyers with the top 5 greatest numbers of purchases.
![image](https://user-images.githubusercontent.com/73863977/120050682-c350bc00-bfeb-11eb-9135-d5e1e969fc7a.png)

I then listed the IDs, names, purchase counts, prices, and total revenue generated from each of the top 6 most bought items.
![image](https://user-images.githubusercontent.com/73863977/120050695-d19ed800-bfeb-11eb-8047-43edabe7ad84.png)
I also examined the items which generated the top 6 greatest amounts of revenue:
![image](https://user-images.githubusercontent.com/73863977/120050702-d95e7c80-bfeb-11eb-9f81-8ce147068425.png)


OBSERVABLE TRENDS:
1. Male buyers outnumber female buyers by about 6 to 1. However, females tend to pay slightly more, on average, per player, than do males. I am not sure if this difference in average amount paid is merely due to the greater influence of outliers among the smaller female population than among the large male population.
2. There is a 5.6-fold drop in the number of buyers when crossing from the 22=<Age=<25 age bin to the 26=<Age=<29 age bin. This seems like the largest change in buyership shown between consecutive brackets in the age demographics.
3. "Singed Scalpel" was the only game to make the top 5 of most profitable items but not the top 6 most popular items.
