# social media Project

##  Overview

Let’s use your Social Media Analytics dataset (the one with users, posts, comments, likes, followers) — and generate 30 SQL questions, grouped by difficulty (Easy → Medium → Hard), 
based on the exact pattern framework we built earlier: 👉 SELECT → Aggregation → JOIN → Subquery → Window Function → CTE → Real-world Analytics.

---

SQL Practice Set — Social Media Analytics Dataset (30 Questions)
Level 1: Easy (Basics, Filtering, Aggregation)
These test your fundamentals — SELECT, WHERE, ORDER BY, and basic COUNT() or SUM().
1. List all users with their registration date sorted by newest first.
2. Find all posts created after '2024-01-01'.
3. Count the total number of posts in the system.
4. Find how many comments each post has.
5. Retrieve all users who have posted at least once.
6. Display the total number of likes received across all posts.
7. Show the top 5 posts with the highest number of likes.
8. List all users whose username starts with 'A'.
9. Find the date of the most recent post.
10. Get the total number of followers per user.
 
 - Concepts used: SELECT, COUNT, GROUP BY, ORDER BY, basic filters.

---

Level 2: Medium (Joins, Grouping, Subqueries)
Now we test logical thinking and relationships across tables — e.g., users ↔ posts ↔ likes ↔ comments.

11. Find users who never created any posts.
12. List posts along with the number of comments and likes they received.
13. Find the top 3 most active users based on number of posts.
14. Retrieve users who commented on their own posts.
15. For each user, find the average likes received per post.
16. List users who have liked more than 10 different posts.
17. Find users who follow more than 5 other users.
18. Get all comments that were made on posts published in the last 7 days.
19. Show the number of comments made by each user, ordered by count descending.
20. Find posts that received zero comments or zero likes.
 - Concepts used: JOINS, GROUP BY, HAVING, Subquery (NOT IN, EXISTS), DATE functions.

---

Level 3: Hard (Analytics, CTEs, Window Functions, Real-world Insights)
These simulate real data engineer interview questions — using CTEs, RANK, and analytic logic.

21. Find the top 3 most followed users.
22. Find the most liked post for each user.
23. Calculate the engagement rate per post = (likes + comments) / followers_of_author.
24. Using a window function, rank all users by total likes received on their posts.
25. Find the user with the highest average likes per post.
26. Find posts that performed above average engagement rate.
27. Use a CTE to calculate the total likes and comments for each post, then get the top 5 overall posts.
28. For each user, show their month-over-month post growth (using DATE_FORMAT and LAG).
29. Identify the top influencer — user who received the maximum likes from unique followers.
30. Create a view user_summary that includes total posts, total likes received, and follower count per user.
 - Concepts used:
* CTE
* Window Functions (RANK, ROW_NUMBER, LAG)
* Aggregate Calculations
* JOINs across multiple entities
* Analytical reasoning on engagement metrics
---

##  Setup Instructions

1. **Create the database**
   ```sql
   CREATE DATABASE social_media_db;
   USE social_media_db;


## Analysis

The documentation of the data analysis process is included in the file [*social_media_db.sql*]()

## Summary

The project was done for the purpose of practice and to improve skills in SQL.
  
