# Dominos-Pizza-Sales-Analysis: Enhancing Pizza Outlet Efficiency using Power BI
## Breif Introduction:
This report helps to provide insights of a Domino’s Pizza outlet in Mumbai to uncover actionable insights to help the outlet increase sales & improve operational efficiency.

## Objective: 
To identify the actionable insights to help outlet increase sales, changes in menu, customer buying choices and improve operational efficiency.

## Data Cleaning and prepartion:
The given data set was clean with no blanks/empty rows and can be considered for further analysis.
- The data in excel file need to load into power bi, then check the data type of each columns in a tables and change to respective data type. Then transform the data using power query.
- In the given datasets, we have 4 tables contains order details, order_id, pizzas and pizza id with transactions details of 2022 year.
- All these tables have common columns which gives relationship b/w all these tables.
- Merge all these columns into one common table using merge query command for better analysis.
- Merge order_details, order id tables & based on pizza_type_id merge pizza name, category & price from pizza’s and pizza’s id tables.
- Now all required columns are grouped in one table named as (updated_orders) for further analysis.

## Data Analysis:
The Analysis was divided into following categories:
1. Sales highlights: Includes analysis of Sales & Orders trend, Revenue by Pizza Category & Size, Top Performing & least performing Pizza’s in terms of revenue & Qty.

   ![image](https://github.com/vishnupriya-projects/Dominos-Pizza-Sales-Analysis/assets/159273003/8ef24546-fe0f-4909-a41e-7fcae3dc9742)

2. Weekly & Hourly peak time analysis: Calculation of weekend & weekdays sales to identify sales pattern and distribution of time in hourly basis to identify peak hours.

  ![image](https://github.com/vishnupriya-projects/Dominos-Pizza-Sales-Analysis/assets/159273003/cd140268-ea4a-4937-8c45-ec7d87ca1c07)

3. Best pizza combinations & menu optimization using Market basket Analysis: To identify best selling comibations & cross selling items.

   ![image](https://github.com/vishnupriya-projects/Dominos-Pizza-Sales-Analysis/assets/159273003/eebc154f-2afd-4306-bbff-4a1124759967)

## Insights & Recommendations:
- The sales was high in June & orders count was reduced more in Sept & Oct , need to find what are the potential reasons for less orders based on the geographic location details of the outlet, any festival seasons or any health issues occur (like covid cases) etc.
- Among all products, veg & non-veg pizza’s have high demand with overall 96.6% share, so this out let is good for pizza’s rather than other product categories.
- In terms of size, Large & medium holds ~35% share each & 30%  by regular pizza’s. it tells us people prefer the pizza as their complete lunch or dinner rather than snacks.
- In terms of revenue & qty sold, chicken_golden delight, fresh veggie, double cheese margarita, indi tandoori, deluxe veggie, cheese n corn are top 6 performers.
- In terms of qty sold, majority are fresh veggie, double cheese margarita, cheese n corn which are less price compared to remaining veg pizza’s. Similarly in non veg pizza, chicken golden delight was in medium price compared to other non veg pizza category. it can be reason for people preferring to purchase qty due to cost effective.
- Among 12 categories only 8 categories have generated revenue and 4 categories (DIP, Parcel,Pasta veg & pasta non-veg ) doesn’t observed any single transaction in that year.  There are total 9 items under this categories. It means people not preferring to have dips with pizza’s it might be due to additional cost, people are more likely to buy pasta pizza rather than original pasta items.
- Needs Reducing the inventory levels of these items and to sale the existing stock, free dips need to provide based on pizza orders count and can cross sell these items with top selling items with discounts may attract the customers.
- In a day, most orders are happening at 12 to 1 pm, followed by 5 to 7 pm which are lunch & dinner timings. In terms of week, expect Tuesday & Monday remaining all days have highest orders floating at lunch time (12 - 1 pm). For dinner time (5-7 pm) almost all weeks have high orders floating.
- This gives us clear picture of managing the staff based on peak hours & helps to give week off to employees on less order days like Tuesday & Monday and more staff is needed at lunch & dinner timings also help in early preparation of inventory levels according to orders which helps to improve overall operational efficiency.
- In terms of best combinations, fresh veggie - double cheese margarita were frequently bought together with (support 2.1% & lift of 1.3) followed by delux_veggie - chicken_golden delight, fresh veggie - chicken pepperoni etc. Total 13 combinations were identified which are frequently bought & have strong relationship b/w two products (picture attached above).
- With these, new combo’s can be added in menu card with best combinations combo pack’s to choose by customers (“ TRY OUR BEST COMBO PIZZA’S”) with offering discounts will improve sales efficiency.
  
## Acknowledgement:
-Thanks to dataanalystduo team, for providing the data and Special thanks to kalpesh for your guidence through out the project.
