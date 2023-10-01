# Develop an Ovulation Calculator Using Python

Implementing an Ovulation Calculator to precisely determine the day of ovulation.

# Motivation

I embarked on this project with the noble intention of aiding individuals who have encountered challenges in identifying their ovulation day and simplifying their life planning. By creating this solution, I sought to alleviate the burden of uncertainty and offer a reliable tool that empowers users to make informed decisions regarding their reproductive health, family planning, and overall well-being. It is my aspiration that this project eases the journey for those in need, fostering a sense of control and confidence in their life choices.

# Description

The calculator takes user inputs for the first date of their last menstrual period and the length of their menstrual cycle and subsequently generates and displays the estimated ovulation date.

Programming Language: Python

Tools & Libraries
---

1. DateTime Module: Utilized for date parsing and manipulation.
2. Error Handling: Implemented to ensure valid user inputs and provide informative error messages.
3. User Interaction: Incorporated user-friendly prompts and instructions.
4. Mathematical Calculation: Utilized to estimate the ovulation date based on the input data.

Technical Functionality
---

1. Input Handling: The calculator prompts users to input the first date of their last menstrual period and the length of their menstrual cycle in days.
2. Data Validation: The program validates user inputs to ensure that the date is in the correct format and that the menstrual cycle length falls within a reasonable range (between 21 and 35 days).
3. Date Calculation: Using the provided information, the calculator estimates the ovulation date by subtracting 14 days from the length of the menstrual cycle, as this is a common approximation for ovulation.
4. Output Display: The calculated ovulation date is displayed to the user in a user-friendly format (dd/mm/yyyy).
