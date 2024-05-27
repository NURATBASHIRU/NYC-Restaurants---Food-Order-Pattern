# NYC-Restaurants---Food-Order Pattern
### Project Overview
This visualization represents real restaurants in the United States. An Exploratory Data Analysis was carried out in order to create visual representation of Customer Purchase Pattern (CPP). This analysis allowed me to assess each restaurant's business performance, types of cuisine (and it niche) and ultimately; customers' purchase. In this analysis, we will observe the diffent category of analysis. Firstly, I created a Key Performance Indicator(KPI) - for clarity on the critical aspect of performance, allowing us to focus on what really matters in this analysis. I also created visualization for the following;
- Food Order Categorised By Weekdays: Represents the general business performance for weekdays and weekends using a donut chart.
- Food Order By Restaurant Name: Restaurant performance - each resaurant is being visually represented on an treemap and their performance is being analysed by the size of each block.
- Customer Rating For Each Cuisine: This prooves the rating for each cuisine type on a scale of 3, 4 or 5 and the number of customers that agree to each rating is being displayed on a heatmap.
- Cost Of Order By Cuisine: Using a horizontal barchart, I created a visualization that shows comparison between the most expensive cuisine and the least expensive cuisine in this category.
- Lastly, Rating For Cuisine Types: This shows the relationship / pattern between each rating for each cuisine.

### Data Source
Kaggle [https://www.kaggle.com/datasets/ahsan81/food-ordering-and-delivery-app-dataset]

### Tools
Excel Workbook
Tableau

### Data Structure
- order_id: Unique ID of the order
- customer_id: ID of the customer who ordered the food
- restaurant_name: Name of the restaurant
- cuisine_type: Cuisine ordered by the customer
- cost: Cost of the order
- day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
- rating: Rating given by the customer out of 5
- food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
- delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information
### Result / Findings
Here is a link to the Tableau Dashboard created for this course; [https://public.tableau.com/views/NYCRESTAURANTDATA/FoodOrderDashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link]
- Customers order more during the weekend
- American, Japanese and Italian Cuisines Have the highest order rate
- Shake Shack is the most popular restaurant in New York
- American, Japanese and Italian Cuisines have the highest frequency of '5 star' ratings. Although, we have a significantly high amount of "not given" - customers who have refused to give any rating at all out of the three categories provided - and I recommend that the restaurants should encourage customers to give a rating. so 'Rating' can be properly measured for each cuisine type.

### Recommendations
- The restaurants should increase staff strenght and food availability for weekend sale activities.
- The restaurants should create a niche for the American, Japanese and Italian dishes since they are the most ordered. The restaurants may as well invest more in these dishes while generally improving on the other dishes.
- Restaurants may also create varieties for these dishes. since customers are really invested in it, they mas as well be open to other options.
