# RSVP Movies Case Study - SQL Analysis

## Summary
This case study leverages SQL to analyze RSVP Movies' production portfolio, aiming to identify trends and factors that influence the success of their films. By querying historical movie data, including genres, budgets, release years, ratings, and box office performance, this study provides actionable insights for strategic decision-making. Key tasks included data cleaning, aggregation, and filtering to perform in-depth analysis directly within SQL, offering insights that can guide future content production decisions for RSVP Movies.

## SQL Tools and Techniques Used
- **SQL Concepts**: SELECT, JOIN, GROUP BY, HAVING, ORDER BY, WINDOW FUNCTIONS, CTEs (Common Table Expressions), and Subqueries.
- **Database Management System**: MySQL (or applicable RDBMS with similar functionality)

## Key Learnings
- **Data Transformation in SQL**: Improved proficiency in using SQL functions to clean and standardize data, especially around string manipulation for genres, date parsing, and handling missing or NULL values.
- **Aggregations and Filtering**: Practiced using GROUP BY and HAVING clauses to calculate averages (e.g., average rating, average revenue by genre) and applied filtering techniques to analyze specific segments like high-revenue movies or popular genres.
- **Complex Query Building**: Gained experience with multi-step SQL queries using subqueries and CTEs to manage complex analyses, such as identifying top-performing genres over time and calculating the ROI on movie budgets.

## Challenges Overcame
- **Handling Multiple Genres**: SQL analysis of multi-genre films required parsing and managing one-to-many relationships. Utilized techniques such as CROSS JOIN and string functions to split and analyze genres effectively.
- **Dealing with NULL and Missing Data**: Many entries had NULL values for revenue or budget. Addressed this by using COALESCE and filtering out NULL values strategically to maintain dataset integrity without skewing results.
- **Data Aggregation for Temporal Analysis**: Conducted time-based analysis by creating custom fields for release periods (e.g., yearly, quarterly), using date functions to standardize date fields and perform meaningful time-based aggregations.

## Additional Reflections
Working within SQL to analyze RSVP Movies’ data highlighted the power of SQL in performing detailed, real-time data manipulation and exploration without exporting to other tools. This SQL-based approach provided efficient insights directly from the database, making it a powerful option for data-driven decision-making. The experience underscored the importance of understanding database relationships, handling complex data hierarchies, and optimizing queries for performance, especially when working with large datasets.
