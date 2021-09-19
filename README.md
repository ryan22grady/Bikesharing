# Bikesharing

## Project Overview
Now that Bobby has proven his SQL chops, his manager has given the two of us more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. We then were instructed to write a report that summarizes the analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

## Results
- With the retirement_titles table, we were able to see all employees elligible for retirement and then associate those elligible with how long he or she has worked at company and the current job title.

<img width="485" alt="Screen Shot 2021-08-01 at 7 38 24 PM" src="https://user-images.githubusercontent.com/84995704/127790595-24b33154-1c72-4f93-8022-15416720e6b9.png">

- The unique_titles table  allowed us to further refine the retirement_titles table by removing deplicate rows of titles, so we can get a better count of elligible employees. 

- Our retiring_titles illustrated us the a majority of the employees of retirement age (57,668/90,398 = 64%) have senior titles.

<img width="175" alt="Screen Shot 2021-08-01 at 7 40 10 PM" src="https://user-images.githubusercontent.com/84995704/127790640-8b7e0b58-5881-4ad2-a177-0ec7723f98dc.png">

- The last part of our project displays mentorship eligibility. Here we noticed that most employees who meet the age requirement for the mentorship program are eligible for retirement and have senior titles. Clearly, the strength of the mentorship program is reliant on senior-titled employees who are eligible for retirement, making the program somewhat vulnerable. 

<img width="581" alt="Screen Shot 2021-08-01 at 7 39 00 PM" src="https://user-images.githubusercontent.com/84995704/127790614-086bbb4b-22f1-4aec-82ea-95bd372e0afa.png">

## Summary
At the moment at Pewlett Hackard, 64% of their employees are eligible for retirement and/or being redirected to mentorship initiatives. This implies that Pewlett Hackard are likely going to need an extensive hiring process in the upcoming years, since more than 50% are eligible losses. The good news, however, is that there is an ample pool of qualified, retirement-ready employees to mentor the next genermation. Further querying that isolates specific departments could provide better insight into the areas of the company that stand to be most effected.  Additional queries into manager to employee ratio could aid as well. 
