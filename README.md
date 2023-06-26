
![Star Badge](https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99)
[![View Main Folder](https://img.shields.io/badge/View-Main_Folder-971901?)](https://github.com/yaswanthteja/SQL_Case_Studies#sql_case_studies)
[![View Repositories](https://img.shields.io/badge/View-My_Repositories-blue?logo=GitHub)](https://github.com/yaswanthteja?tab=repositories)
[![View My Profile](https://img.shields.io/badge/View-My_Profile-green?logo=GitHub)](https://github.com/yaswanthteja)


# [8-Week SQL Challenge](https://8weeksqlchallenge.com) <img src="https://s3.amazonaws.com/thinkific-import/357412/n0nS0vA3RmOtzsH99jyf_Data_With_Danny_Round_Logo_png" align="right" width="120" />

> This repository contains all of my code submissions for the **#8WeekSQLChallenge**! 
> 
> All case study's requirements and resources are available on the challenge [website](https://8weeksqlchallenge.com).



# 🍕 Case Study #2 Pizza Runner

![image](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2/blob/master/images/Readme/Pizza%20Runner_Case%20Study2.png)

## 📚 Table of Contents
- [Business Task](#business-task)
- [Entity Relationship Diagram](#entity-relationship-diagram)
- [Case Study Questions](#case-study-questions)

 - Solution

  - [Data Cleaning and Transformation](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2-/blob/master/D.Data%20Cleaning%20and%20Transformation.md)
  - [A. Pizza Metrics](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2-/blob/master/A.%20Pizza%20Metrics.md)
  - [B. Runner and Customer Experience](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2-/blob/master/B.%20Runner%20and%20Customer%20Experience.md)
  - [Complete SQL Syntax](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2-/tree/master/SQL%20Syntax)
- [Solution on Dev](https://dev.to/yaswanthteja/8-week-sql-challenge-case-study-2-pizza-runner-e0o)

***

## Business Task
Danny is expanding his new Pizza Empire and at the same time, he wants to Uberize it, so Pizza Runner was launched!

Danny started by recruiting “runners” to deliver fresh pizza from Pizza Runner Headquarters (otherwise known as Danny’s house) and also maxed out his credit card to pay freelance developers to build a mobile app to accept orders from customers. 

## Entity Relationship Diagram

![image](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2/blob/master/images/Readme/Entity_relationship_Diagram.png)

## Case Study Questions

### A. Pizza Metrics

View my solution [here](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2/blob/master/A.%20Pizza%20Metrics.md).










1. How many pizzas were ordered?
2. How many unique customer orders were made?
3. How many successful orders were delivered by each runner?
4. How many of each type of pizza was delivered?
5. How many Vegetarian and Meatlovers were ordered by each customer?
6. What was the maximum number of pizzas delivered in a single order?
7. For each customer, how many delivered pizzas had at least 1 change and how many had no changes?
8. How many pizzas were delivered that had both exclusions and extras?
9. What was the total volume of pizzas ordered for each hour of the day?
10. What was the volume of orders for each day of the week?

### B. Runner and Customer Experience

View my solution [here](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2/blob/master/B.%20Runner%20and%20Customer%20Experience.md).

1. How many runners signed up for each 1 week period? (i.e. week starts 2021-01-01)
2. What was the average time in minutes it took for each runner to arrive at the Pizza Runner HQ to pickup the order?
3. Is there any relationship between the number of pizzas and how long the order takes to prepare?
4. What was the average distance travelled for each customer?
5. What was the difference between the longest and shortest delivery times for all orders?
6. What was the average speed for each runner for each delivery and do you notice any trend for these values?
7. What is the successful delivery percentage for each runner?

### C. Ingredient Optimisation
view my solution [here](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2/blob/master/C.%20Ingredient%20Optimisation.md)

1. What are the standard ingredients for each pizza?
2. What was the most commonly added extra?
3. What was the most common exclusion?
4. Generate an order item for each record in the customers_orders table in the format of one of the following:
- Meat Lovers
- Meat Lovers - Exclude Beef
- Meat Lovers - Extra Bacon
- Meat Lovers - Exclude Cheese, Bacon - Extra Mushroom, Peppers
5. Generate an alphabetically ordered comma separated ingredient list for each pizza order from the customer_orders table and add a 2x in front of any relevant ingredients
6. For example: "Meat Lovers: 2xBacon, Beef, ... , Salami"
7. What is the total quantity of each ingredient used in all delivered pizzas sorted by most frequent first?

### D. Pricing and Ratings

1. If a Meat Lovers pizza costs $12 and Vegetarian costs $10 and there were no charges for changes - how much money has Pizza Runner made so far if there are no delivery fees?
2. What if there was an additional $1 charge for any pizza extras?
- Add cheese is $1 extra
3. The Pizza Runner team now wants to add an additional ratings system that allows customers to rate their runner, how would you design an additional table for this new dataset generate a schema for this new table and insert your own data for ratings for each successful customer order between 1 to 5.
4. Using your newly generated table - can you join all of the information together to form a table which has the following information for successful deliveries?
- customer_id
- order_id
- runner_id
- rating
- order_time
- pickup_time
- Time between order and pickup
- Delivery duration
- Average speed
- Total number of pizzas
5. If a Meat Lovers pizza was $12 and Vegetarian $10 fixed prices with no cost for extras and each runner is paid $0.30 per kilometre traveled - how much money does Pizza Runner have left over after these deliveries?

### E. Bonus Questions

If Danny wants to expand his range of pizzas - how would this impact the existing data design? Write an INSERT statement to demonstrate what would happen if a new Supreme pizza with all the toppings was added to the Pizza Runner menu?

***




- [SQL_Dannys_Diner_CaseStudy1](https://github.com/yaswanthteja/SQL_Dannys_Diner_CaseStudy1)


- [SQL_Dannys_Pizza_Runner_CaseStudy2-](https://github.com/yaswanthteja/SQL_Dannys_Pizza_Runner_CaseStudy2-)

- [SQL_Dannys_Foodiee-Fi_CaseStudy3](https://github.com/yaswanthteja/SQL_Dannys_Foodiee-Fi_CaseStudy3)

- [SQL_Dannys_Data-Bank_CaseStudy4](https://github.com/yaswanthteja/SQL_Dannys_Data-Bank_CaseStudy4)






