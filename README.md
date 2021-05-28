# In-Game Purchases Analysis
Heroes of Pymoli

To run the code, simply press the open the .ipynb file in the 'Heroes of Pymoli" folder and press the right-pointing play button to the left of each cell.

My aim in the project was to find which genders, age ranges, and specific items brought in the most revenue for the store in the game "Heroes of Pymoli".
I used pandas, numpy, and Jupyter Notebook to do this.

I counted the total number of players,
the total number of unique items, the average item price, the total number of purchases made, and the total revenue gathered.

I also calculated the numbers of male, female, and other & non-disclosed gendered players and the percentages of the total number of players which each of those demographics constituted.

For male players, I calculated the total purchase count, the average purchase price, the total revenue gained by Heroes Of Pymoli, and the average value which each player paid to the company. I repeated these analyses for female and for other & non-disclosed gendered players.

I binned the players by age in one bin of players 9 and under and nine other bins of 4 years-width each. For each bin, I counted the number of players and the percentage of the total number of players which that bin represented.

For each age bin, I then found the total purchase count, the average value paid by each player, the total purchase value generated, and the average purchase price/person.

I then sorted the entire set of players by the numbers of purchases made and identified the IDs, names, purchase counts, average purchase price paid, and total amount paid to the company for each of the players with the top 5 greatest numbers of purchases.

I then identified the IDs, names, purchase counts, prices, and total revenue generated from each of the top 6 most often bought items,
and for the items which generated the top 5 greatest amounts of revenue.



I chose to analyze the top 6 most often bought items because of the confusion which results from comparing the df of the greatest total value items and the df of the most-bought items. 
This confusion results from the fact that multiple items appear in boths dfs, but the "most-bought items" df has duplicated numbers in the "Purchases Count" column, and some items outside the top 5 have the same Purchase Counts as ones inside the top 5.
It makes more sense to show the top 6.



OBSERVABLE TRENDS:
1. Male players outnumber female players by about 6 to 1. However, females tend to pay slightly more, on average, per player, than do males.
2. There is a 5.6-fold drop in the number of players when crossing from the 22=<Age=<25 age bin to the 26=<Age=<29 age bin. This seems like the largest change in playership shown in the age demographics.
3. "Singed Scalpel" was the only game to make the top 5 of most profitable items but not the top 6 most popular items.
