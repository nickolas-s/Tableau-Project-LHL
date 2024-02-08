![](https://res.cloudinary.com/dnfecsurp/image/upload/v1707360893/tableau-project/repo_header_frxcbr.png)

# FAA Wildlife Strikes 2000-2015 Analysis - Tableau Project LHL

## Project Goals

The objective of this project is to apply the Tableau knowledge acquired throughout Course 3 of the Data Analytics Bootcamp. The goal is to analyze a table of wildlife strikes from 2000-2015 in the United States and create impactful dashboards that provide easily consumable visual insights. Specifically, we aim to answer the following questions:

1. Which wildlife category has had the most collisions?
2. What types of damage occurred by wildlife category?
3. When did the majority of the collisions occur? (time of day, time of year, phase of the flight)
4. What are the top five states with the highest number of collisions?
5. What are the top five airports with the highest number of collisions?
6. What are the top five airports with the highest cost caused by collisions?

## Process

- Load the dataset into Tableau.
- Explore the dataset columns.
- Create simple visualizations to gather basic information.
- Develop more complex visualizations to identify interesting patterns, trends, or outliers.
- Extract meaningful insights from the visualizations.
- Create dashboards to address the questions mentioned above.

## Results

The following are the findings acquired from the dataset. 

1. *Which wildlife category has had the most collisions?* The dataset categorizes wildlife into four categories: Birds, Terrestrial Mammals, Bats, and Reptiles. Birds account for the majority of collisions, with 95.73%, followed by Terrestrial Mammals with 2.98%. A simple text table was created to display this data.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124807/tableau-project/Q1_Wildlife_Category_dc9qcs.png)

2. *What types of damage occurred by wildlife category?* Each collision was classified into one of the following damage categories: None, Minor, Substantial, Medium, and Destroyed. Focusing on the Birds category, the majority of collisions (24,214) caused no damage. 866 collisions caused substantial damage, resulting in the highest cost across all categories. Side-by-side bar visualizations were created to analyze the number of strikes and costs by wildlife category.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124807/tableau-project/Q2_Wildlife_Category_Damage_dsvp9a.png)

3. *When did the majority of the collisions occur? (time of day, time of year, phase of the flight)*
	- Time of the day: 72.8% of collisions occurred during the day, followed by 17.4% at night, as shown in the pie chart below.
	
	![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q3_When_-_Time_of_the_Day_eziev1.png)

	- Time of the year: Collisions peaked between July/August and were lowest between January/February, possibly due to bird migration patterns. A continuous line chart illustrates this trend.
	
	![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q3_When_-_Time_of_the_Year_smammr.png)

	- Phase of the flight: Over half of collisions occurred during the Approach and Landing Roll phases. A stacked bar chart visualizes this data along with the wildlife category.
	
    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q3_When_-_Phase_of_the_Flight_ry9vno.png)

4. *What are the top five states with the highest number of collisions?* The top five states with the highest number of collisions are California, Texas, Florida, New York, and Pennsylvania. The map with the parameter 'Top N' identifies these states.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q4_Top_5_States_zggutv.png)

5. *What are the top five airports with the highest number of collisions?* Refer to the image below for the top five airports with the highest number of collisions. A horizontal bar chart with the parameter 'Top N' was used to identify these airports.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124809/tableau-project/Q5_Top_5_Airports_-_Strikes_p61hip.png)

6. *What are the top five airports with the highest cost caused by collisions?* Refer to the image below for the top five airports with the highest cost caused by collisions. A horizontal bar chart with the parameter 'Top N' was used to identify these airports.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124808/tableau-project/Q6_Top_5_Airports_-_Cost_igv8cf.png)

### Outliers
- LaGuardia Airport in NY is the only airport with more collisions at night than during the day.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124807/tableau-project/Outlier_01_-_LaGuardia_Airport_qre3ek.png)

- Despite having only 2 collisions, Troy Municipal Airport in AL ranks third in terms of cost.

    ![](https://res.cloudinary.com/dnfecsurp/image/upload/v1705124807/tableau-project/Outlier_02_-_Troy_Municipal_Airport_twli9n.png)

## Challenges 
Due to Tableau's high level of customization, it can be challenging to find specific tools or perform certain tasks. The abundance of options can sometimes be overwhelming.

## Future Goals
Given more time, it would be interesting to analyze the number of flights per airport per year to provide additional context to the number of collisions.