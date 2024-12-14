# UplianceAssesment

Loading Data:

The datasets UserDetails.csv, CookingSessions.csv, and OrderDetails.csv were loaded and inspected for structure and initial understanding.
Merging Data:

A two-step merge:
CookingSessions and OrderDetails based on Session ID.
The combined dataset (user_cooking) with UserDetails based on User ID.
This consolidated information facilitates multi-dimensional analysis.
Inspection of Combined Data:

The merged DataFrame (df) was reviewed for completeness, size, and potential inconsistencies (e.g., null values in sessions or orders for specific users).
Primary Dimensions Explored:

User details: Demographics (age, location, and preferences).
Session details: Dish, duration, session ratings, and completion status.
Order details: Amount spent, time of order, and ratings.
Insights To Focus On:
Cooking Sessions vs Orders:

How the session ratings correlate with the corresponding order ratings.
Does session duration impact dish rating or completion probability?
Dish Preferences:

Most popular dishes across users, locations, or meal types.
Meal type trends by time of the day or demographic group.
Demographic Trends:

User behavior variations (e.g., favorite meal type or total orders by age, location).
Order Trends:

Analysis of order statuses (e.g., frequency of cancellations, reasons, and timing).
Spending habits segmented by user attributes.
