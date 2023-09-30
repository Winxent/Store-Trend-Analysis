# US Store Sales and Trends Analysis (Tableau)
To investigate a US store sales and trends using data analysis

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Introduction
Datasets provided: https://drive.google.com/file/d/1ZS_NQCydGnny5t4G-7WnFtxfB1W-4yvY/view?usp=sharing

The Excel datasheets were reviewed, and three sheets were received: Orders, People, and Returns. Details of all sales, profit, orders, regions, and products are contained in the Orders data. The names of salespeople and their respective regions are found in the People sheet. The Order IDs of returned orders can be found in the Return sheet. 

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Using Tableau
The 'Region' detail from the Orders table can be mapped with the 'Region' in the People table to track salespeople. The databases can be connected based on region. Similarly, the 'Order ID' from the Orders table can be mapped with the 'Order ID' in the Return table to track regionally returned orders. Information like this indicates that the blending of information from these tables can be used to answer our analysis questions.

<img width="1152" alt="Screenshot 2023-09-30 at 1 47 11 PM" src="https://github.com/Winxent/Store-Trend-Analysis/assets/146320825/0ca4eae6-d6f2-4e49-a119-96b679ba6af2">

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Dashboard
Interactive Dashboard: https://public.tableau.com/shared/8GQHHX53X?:display_count=n&:origin=viz_share_link

<img width="1369" alt="Screenshot 2023-09-30 at 2 08 07 PM" src="https://github.com/Winxent/Store-Trend-Analysis/assets/146320825/e5b68da9-92ab-4271-9966-f9ae1788056b">

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Summary
Using Tableau interactive visualization, we can answer the store sales questions below:

### 1. For WEST region, which state has highest sales?

<img width="437" alt="Screenshot 2023-09-30 at 2 02 08 PM" src="https://github.com/Winxent/Store-Trend-Analysis/assets/146320825/3fbff8bf-538d-4b5f-9e30-6c3921df1e39">

By clicking on the west region, the interactive dashboard will only shows west regional information. From Sales State Geographic symbol map, the biggest circle indicates California has the highest sales. 

### 2. How many unique TOTAL ORDERS received in WEST region?

<img width="785" alt="Screenshot 2023-09-30 at 2 08 54 PM" src="https://github.com/Winxent/Store-Trend-Analysis/assets/146320825/6c218ebe-815e-43e3-b172-47b922c64fdc">

Again by clicking to any west region, the total order will changed to indicate only west regional's total order.

### 3. In SOUTH region, which SUB-CAT has highest sales?

<img width="830" alt="Screenshot 2023-09-30 at 2 11 46 PM" src="https://github.com/Winxent/Store-Trend-Analysis/assets/146320825/e4cdf582-d76b-4ec1-ad23-ead2c2e98439">

By clicking on South region from the interactive dashboard, we can see that Cunsumer segment phones sub-category has the highest sales.

### 4. What are the TOTAL SALES of sub-cat CHAIRS in CONSUMER segment?
From the Top 5 Subcat.Sales bar chart, consumer chair has about 173K sales.

### 5. Which SHIPPING MODE has lowest PROFIT in EAST region?

<img width="1223" alt="Screenshot 2023-09-30 at 2 15 15 PM" src="https://github.com/Winxent/Store-Trend-Analysis/assets/146320825/e0d4759d-52ac-4af8-9668-176e7402255e">

by clicking on East region and referring to preferred shipment table we can see that same day mode has the lowest profit for only $7980 
