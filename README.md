# Mexico Restaurant Ratings Analysis

Power BI dashboard analyzing restaurant ratings, consumer behavior, and dining insights using a Mexico restaurant dataset.

---

## Project Overview
This project analyzes restaurant ratings provided by consumers along with restaurant characteristics and consumer preferences. The objective is to understand the factors that influence customer satisfaction and restaurant performance using interactive Power BI visualizations.

---

## Objectives
- Analyze consumer demographics and preferences
- Explore restaurant distribution across cities and states
- Study the relationship between restaurant services and ratings
- Identify top-performing restaurants based on ratings
- Present insights through an interactive Power BI dashboard

---

## Dataset

The dataset consists of multiple related tables:

### Consumers
Contains demographic and lifestyle information about consumers.

- Consumer_ID
- City
- State
- Country
- Age
- Occupation
- Budget
- Smoker
- Drink_Level
- Transportation_Method
- Marital_Status
- Children

### Consumer Preferences
Stores cuisine preferences for each consumer.

- Consumer_ID
- Preferred_Cuisine

### Restaurants
Contains restaurant information.

- Restaurant_ID
- Name
- City
- State
- Country
- Price
- Alcohol_Service
- Smoking_Allowed
- Parking
- Franchise
- Area

### Restaurant Cuisines
Lists cuisines served by restaurants.

- Restaurant_ID
- Cuisine

### Ratings
Consumer ratings for restaurants.

- Consumer_ID
- Restaurant_ID
- Overall_Rating
- Food_Rating
- Service_Rating

Rating Scale:

| Rating | Meaning |
|------|------|
| 0 | Unsatisfactory |
| 1 | Satisfactory |
| 2 | Highly Satisfactory |

---

## Data Preparation
Data cleaning and transformation were performed using Power BI Power Query.

Steps included:
- Importing datasets
- Cleaning and transforming data
- Creating calculated columns
- Building relationships between tables

---

## Key Insights

### Consumer Insights
- Most consumers belong to the **young adult age group**.
- The majority of consumers are **non-smokers**.
- **Public transportation** is the most common transportation method.

### Restaurant Insights
- Many restaurants **do not provide parking facilities**.
- **Mexican cuisine** is the most preferred cuisine.
- Most restaurants follow **smoke-free policies**.

### Ratings Insights
Top restaurants based on overall ratings include:

- Tortas Locas Hipocampo
- Puesto de Tacos
- Cafeteria y Restaurante El Pacífico
- La Cantina Restaurante
- Restaurant La Chalita

---

## Dashboard Features
The Power BI dashboard includes interactive visualizations such as:

- Consumer distribution by city and state
- Age group analysis
- Restaurant distribution
- Cuisine preferences
- Transportation patterns
- Restaurant rating comparisons

Filters allow users to explore the data by **city, cuisine, and consumer demographics**.

---

## Tools Used
- Microsoft Power BI
- Power Query
- DAX

---

## Author
Aditi Dattatrya Zuge
B.Tech Computer Science Engineering
