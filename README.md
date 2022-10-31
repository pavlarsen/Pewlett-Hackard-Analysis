# Pewlett-Hackard Analysis

## Overview of Project

### The HR department at Pewlett Hackard is planning a soft-landing strategy for the thousands of soon-to-retire employees. Current HR department has 6 different tables with employee and department information. With the help of a relational database, it will be possible to relate each data point within the different files and be able to answer specific questions that would help determine the best strategy. For this case, we used PostgreSQL and pgAdmin to build the relational database. Our first goal is to be able to determine a) how many current employees will be considered for retirement plans b) how many of those soon-to-retire employees would qualify for a new strategy the "Mentorship Program" which will be helpful for the company's talent development and a good opportunity for the retirees to still be present with the company.

---

## Analysis Results

Key findings summary:

![Captura de pantalla 2022-10-31 a la(s) 12 29 05](https://user-images.githubusercontent.com/113866707/199082710-e453b1ba-5cde-4eb2-8bae-9784b179d777.png)

- More than 70K employees will be in retirement age soon. This represents almost 30% of PH current total employees. Near 70% of near to retire staff held a Senior position.

- PH will face a shortage of Senior staff which will affect the performance of the company. In order to prevent a potential loss of "cumulative experience" years. PH needs to address the situation and realize that its current structure will have to change drastically, with current employees having to cover for Senior positions.

![Captura de pantalla 2022-10-31 a la(s) 13 16 09](https://user-images.githubusercontent.com/113866707/199091331-1518d4cc-9880-45af-badd-5039ceb91ab9.png)

- From the current available employees. 1,549 would benefit from a Mentorship Program. The criteria for this consideration will be to offer the program to those employees who were born in 1965. The idea is to invite retired employees to coach these employees for them to gain the experience and skills needed for Senior positions.

- By implementing a correct Mentorship Program, the company would be able to handle the next 8 years (before 1965 generation) retires, to prevent any damage in human capital.

    
---

## Summary

- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
For this question, it would be needed to have a list of total employees grouped by age group and roles in order to visualize the whole impact of the silver tsunami. With this information, we will be able to assess the company's leadership structure, define a development program for remaining employees. Determine hiring criteria to face the impact of the silver tsunami. Are all those roles needed for the next 5 - 10 years? What is the vision for the company for the long term? By planning accordingly with the proper headcounts per role, the HR team can plan any possible human capital needs.

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett-Hackard employees?
By a simple glimpse, we will only have 1.5K employees to have age seniority for HP, however the gap from the silver tsunami is to fill another 68.5K roles. From those, 50K are Senior positions. In terms of mentors, yes, HP will have plenty of gross available mentors (depends on them if they want to join), the issue will be the mentees. The company must develop a structure plan to focus which of the remaining employees will need what training from the mentors. HR team could use SQL to create different tables of a final mentor - mentees by department and title and this way develop the staff accordingly.

