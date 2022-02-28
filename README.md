# Pewlett_Hackard_Analysis

## Overview of The Analysis:
The purpose of this new analysis is to help management at Pewlett Hackard determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. With this analysis Pewlett Hackard should be better prepared for the retirements to come and minimize the amount of talent leaving by re-purposing them into a mentor/trainer role within the company. 

## The Results
- First, we created a Retirement Titles table that consisted of all of the upcoming retirees which included their employee number, first and last name, title, and when they started and left their position. (Below image shows top 10 from table) 

![retirement_titles_top_10](https://user-images.githubusercontent.com/95251140/155906758-39cd80a5-0c77-4e49-88e7-50f01189078f.png)

- The main issue from the Retirement Titles table is we ran into duplicate entries for some employees likely because they switched titles over the years. To correct this, we created a Unique Titles table to remove the duplicates and only have the most recent title of each employee displayed, we also excluded employees that had already left the company. (Below image shows top 10 from table)

![unique_titles_top_10](https://user-images.githubusercontent.com/95251140/155906874-96ccbf59-7b8c-4e28-b72a-cc0b613360fa.png)

- Then we created a Retiring Titles table so that we could show the number of employees retiring in each specific title field.

![retiring_titles_table](https://user-images.githubusercontent.com/95251140/155907096-0d995f5f-82db-4789-8007-365af5e7d92e.png)

- Finally we created the Mentorship Eligibility table to show all of the employees, who were born between January 1, 1965 and December 31, 1965, currently eligible to be a part of the mentorship program. (Below image shows top 10 from table)

![mentorship_eligibilty_top_10](https://user-images.githubusercontent.com/95251140/155907458-0920d2c1-03dc-44d6-bf8c-c3636ca84171.png)

## Summary
- The total number of retiring employees is 72,458 and the breakdown by title is in the Retiring Titles table shown under the results section above.
- For the second question are there enough qualified retirement ready mentors in each department, we had to create a new table to show the count of employees in each specific title field that could be a mentor. (Below image shows top 10 from table) 

![eligible_mentors_table](https://user-images.githubusercontent.com/95251140/155908783-b1e16198-2dfc-4e1f-9550-d25af0ce19f4.png)

Looking at the numbers Pewlett Hackard should have enough employees that are eligible to become mentors, the only area they will be lacking in for mentorship appears to be with managers. So along with a mentorship program they may want to develop a management training course. 
