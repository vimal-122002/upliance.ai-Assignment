# Food Order Analysis

This project performs comprehensive data analysis on food order datasets, focusing on dish popularity, meal time preferences, cooking session performance, and demographic influences. It generates visualizations and insights to guide business decisions.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset Description](#dataset-description)
- [Installation](#installation)
- [Usage](#usage)
- [Outputs](#outputs)
- [Business Recommendations](#business-recommendations)
- [License](#license)

---

## Project Overview

This project aims to:

1. Analyze dish popularity and revenue.
2. Examine order distribution across different meal times.
3. Assess cooking session performance.
4. Identify demographic factors affecting orders.

It provides actionable insights through a combination of statistical analysis and visualizations.

---

## Features

- **Dish Popularity Analysis**: Identifies the most popular dishes and top revenue generators.
- **Meal Time Distribution**: Examines order distribution across meal times.
- **Cooking Session Performance**: Analyzes session duration and user ratings for cooking sessions.
- **Demographic Insights**: Provides insights into order patterns by age groups.
- **Report Generation**: Compiles findings into a comprehensive text report.

---

## Dataset Description

The analysis requires three CSV files:

1. **UserDetails.csv**:
   - `User ID`: Unique identifier for users.
   - `Age`: Age of the user.
   - `Registration Date`: Date when the user registered.

2. **OrderDetails.csv**:
   - `Order ID`: Unique identifier for orders.
   - `User ID`: Identifier linking the user to the order.
   - `Dish Name`: Name of the dish ordered.
   - `Order Date`: Date of the order.
   - `Amount (USD)`: Amount spent on the order.
   - `Order Status`: Status of the order (e.g., Completed).
   - `Time of Day`: Meal time (e.g., Breakfast, Lunch).

3. **CookingSessions.csv**:
   - `Session ID`: Unique identifier for sessions.
   - `User ID`: Identifier linking the user to the session.
   - `Dish Name`: Name of the dish cooked.
   - `Session Start`: Start time of the session.
   - `Session End`: End time of the session.
   - `Duration (mins)`: Total duration of the session.
   - `Session Rating`: User rating for the session.

---
