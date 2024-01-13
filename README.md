# Final Project Tableau - FAA Wildlife Strikes 2000-2015 Analysis

## Project/Goals

The objective of this project is to apply all the Tableau knowledge acquired throughout Course 3 of the Data Analytics Bootcamp.
The goal is to analyze a table of wildlife strikes from 2000-2015 in the United States and turn the data into easily consumable visual insights, creating impactful dashboards that help to answer the following questions:

1. What kind of wildlife category has had more collisions?
2. What kind of damage occurred by wildlife category?
3. When did the majority of the collisions happen? (time of the day, time of the year, phase of the flight)
4. Top five states with the highest number of collisions.
5. Top five airports with the highest number of collisions.
6. Top five airports with the highest cost caused by collisions.

## Process

- Load the dataset into Tableau
- Explore the columns of the dataset
- Create simple visualizations to acquire basic information
- Create more complex visualizations to try to find interesting patterns, trends, or outliers. 
- Try to detect meaningful key points from the visualizations created 
- Create the dashboard to answer the questions mentioned above

## Results

The following are the findings acquired from the dataset ‘FAA Wildlife Strikes, 2015’ of option 2. 

1. *What kind of wildlife category has had more collisions?* The dataset divides the wildlife in 4 categories, Birds, Terrestrial Mammals, Bats, and Reptiles. Birds are by far the category with the highest number of collisions, 95.73%, followed by Terrestrial Mammals, 2.98%. To answer this question a simple text table was created.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124807/tableau-project/Q1_Wildlife_Category_dc9qcs.png)

2. *What kind of damage occurred by wildlife category?*
	Each collision was classified as causing one the the following damages: None, Minor, Substantial, Medium, and Destroyed. Focusing on the Birds category, the majority of the collisions (24,214) caused no damage. 866 collisions caused substantial resulting in the highest cost across all categories. Two side-by-side bars valuations were created to analyze simultaneously the number of strikes and cost by wildlife category.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124807/tableau-project/Q2_Wildlife_Category_Damage_dsvp9a.png)

3. *When did the majority of the collisions happen? (time of the day, time of the year, phase of the flight)*
	- Time of the day: 72.8% of all collisions occurred during the day, followed by 17.4% that occurred during the night. A pie chart was used to visualize this data.
	
	![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q3_When_-_Time_of_the_Day_eziev1.png)
	- Time of the year: The highest number of collisions during a year was between July/August and the lowest was between January/February. Likely this pattern is because there are more birds in North America during the summer and they migrate south during the winter. To visualize this pattern a continuous line chart was created.
	
	![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q3_When_-_Time_of_the_Year_smammr.png)

	- Phase of the flight: More than half of the collisions occurred during the Approach and Landing Roll phases. A stacked bar chart was created to also visualize the wildlife category.
	
    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q3_When_-_Phase_of_the_Flight_ry9vno.png)

4. *Top five states with the highest number of collisions.* The top five states with the highest number of collisions are California, Texas,  Florida, New York, and Pennsylvania. A map with the parameter ‘Top N’ was used to identify the top five states.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q4_Top_5_States_zggutv.png)

5. *Top five airports with the highest number of collisions.* Refer to the image below for the top five airports with the highest number of collisions. A horizontal bar chart with the parameter ‘Top N’ was used to identify the top five airports.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124809/tableau-project/Q5_Top_5_Airports_-_Strikes_p61hip.png)

6. *Top five airports with the highest cost caused by collisions.* Refer to the image below for the top five airports with the highest cost caused by collisions. Just as in the prior question, A horizontal bar chart with the parameter ‘Top N’ was used to identify the top five airports.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q6_Top_5_Airports_-_Cost_igv8cf.png)

### Outliers
- Of all airports, LaGuardia Airport - NY is the only airport that had more collisions during the night than during the day.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124807/tableau-project/Outlier_01_-_LaGuardia_Airport_qre3ek.png)

- Even though Troy Municipal Airport - AL had only 2 collisions, it is the third airport with the highest cost.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124807/tableau-project/Outlier_02_-_Troy_Municipal_Airport_twli9n.png)

## Challenges 
Since Tableau is highly customizable, sometimes is hard to find a specific tool or how to do certain tasks. Occasionally Tableau gives the impression of having too many options.

## Future Goals
If more time was available, it would be interesting to find the number of flights per airport per year to give the number of collisions more context.
