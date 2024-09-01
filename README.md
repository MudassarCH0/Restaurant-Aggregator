
***Table of Contents***<br>

* Description
* Tools & Dataset
* Execution
* Results
* Recommenation
* Link  

\
***Description***<br>

Zomato is a multinational restaurant aggregator and food delivery company. As an on-boarding BIA, the goal was to analyze the business performance of restaurants and test hypothesis, such as what restaurants are popular? what restaurants generate the highest revenue? why?.     

\
***Tools & Dataset***<br>

* Tools: Power BI
* Zomato Data
  * five source files
    * food
    * menu
    * orders
    * restaurant
    * users 
  * Four files used
    * user (user_id), name, age, gender, marital status, occupation, monthly income, education, family size
    * orders (user_id, r_id), currency, sales_amount, sales_qty, order_date
    * menu (menu_id, r_id, f_id), cuisine, price
    * resturant (id->r_id), name, city, state, rating, rating_count, cost, cuisine
    * food (f_id), item, veg_or_non_veg
  * Entity Diagram <br> ![image](https://github.com/user-attachments/assets/99477fa1-5be1-4825-ad50-fd5d536acce9)


\
***Execution***<br>

* Data Processing: explore data, backup data, clean data, filter data, decomposition plan, data visualization mockups
* Key Performance Indicators (KPIs): Popular Restaurant per City, Food Preference, Overall Sales, Popular Items, Sales per Items, Popular Item Sales per City, Weekday Sales, Average
  Check per Restaurant, Satisfied Customers per Restaurant, Unsatisfied Customers per Restaurant, Customer Repeat Rate, Highest Sales per Restaurants
* Visualization: KPI card, Line Chart, Bar Chart, Bar Chart, Pie Chart, Table
* Process: found types of apps that are out there, created DAX column with review weigh values, DAX column with average developer review values, new table with many-to-one, filter to
  select review count greater than 500

\
***Results***<br>

* Weekly reviews stay the same with 4 to 5 ratings
* Average review weigh was 5.48
* More than half of the developers had more than 50k reviews

\
***Recomnendation***<br>
* Apps with high review count have greater success
* To measure success new apps should have weekly review count between 35K to 50K<br><br> 

> [!Note]
> [Project Link](https://public.tableau.com/app/profile/mudassar.chaudhry/viz/FinalProject_17173229631950/NotesIStoryline)
