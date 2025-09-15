# 🎬 Advanced SQL queries analysis on a movie database

This project demonstrates advanced SQL queries on a multi-table movie database schema. I used advanced techniques like CTEs, Window Functions, and Joins.

## 📊 Database Schema
The analysis is based on a relational database with the following tables:
- movies
- financials
- actors
- movie_actor
- languages

## Questions & Solutions
Here are the challenges I tackled and my approach to solving them.

**Question:** Identify the top 3 studios which have the highest average Return on Investment (ROI) 
	for their movies. Only consider studios with more than 1 movies.
 
**Approach:**
- Joined the movies and financials tables.
- Handled currency unit conversion within a CTE.
- Calculated ROI as (revenue - budget) / budget.
- Used aggregation and a HAVING clause to filter studios with >1 movies.
- Used limit

**Result**
! Result for Question 1(./ans 1.png)










