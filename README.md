# Problem Statement
This Project focus on helping HR to easily access information about their employees. The dashboard is build in a way that HR can explore the total number hired, active and terminated employees, they can find the number of employees in each department, the location and whether they work at Heardquarters or in the brunch. They are also able to see how what potion of emploees is Females and males both terminated and active. They can also explore the education level and age of the employees as well as the age and average salary of employees. On the other hand,the HR is also able to navigate and view individual details by entering the employee ID and information such as Demographics, role, salary, status of employment and length of employment.

# Background
This project was born from desire to explore tableau as well as to assist HR to easily find information about their employees.

### The questions answered through this dashboard were:

1. What is the total number of employees Hired? how many are active and how many terminated?
2. How many employeees are actively in each department and how many have terminated?
3. What is the total number of the employees working at heardquarters and how many are in other brunches?
4. How many employees are in each city?
5. How many employees are males and how many are females, how many are active and inactive?
6. What is the total number of employees with certain level of education?
7. What is the toatl number of employees in each age range?
8. Does education level indicate best performance?
9. How many employees based on gender are there and what is their average salary?
10. What is the average salary and age of each role?

#Tool used
For my deep dive into the data analysis Human Resources Dashboard, I used Tableau.

### Steps followed 

- Step 1 : Load data into Tableau, Hired, Active and Terminated sheets and all were CSV files.
- Step 2 : Take time to learn data, data types and clean the datasets.
- Step 3 : Created new worksheet called Hired by year. An area graph was used to visualise the total number of hired employees by year from 2015 to 2024.
- Step 4 : A new calculation was created to calculate the total percentage of hired employees.
- Step 5 : Created new worksheet called Terminate by year. An area graph was used to visualise the total number of terminated employees by year from 2015 to 2024.
- Step 6 : Calculation fieldS were created to calculate the total percentage of terminated employees and another one to find the age of each employee since only the date of birth was provided in the dataset.
- Step 7 : Created new worksheet called Department. A bar graph was used to visualise the total number of employees both hired and terminated in each department.
- Step 8 : Created new worksheet called Job_Title. A bar graph was used to visualise the total number of employees hired in each role and it was sorted by the role with the most employees. Roles were ranked by the created calculated field to find the rank of the top 2.
-  Step 9 : Created new worksheet called states. A bar graph was used to visualise the total number of employees employees in all states and ranking was also used.
- Step 10 : Created new worksheet called Age. A bar graph was used to visualise the total number of employees hired in each age.
- Step 11 : Created new worksheet called cities. A bar graph was used to visualise the total number of employees in all cities.
- Step 12 : Created new worksheet called Location. A bar graph was used to visualise the total number of employees in either Heardquarters or Branch.
- Step 13 : Created new worksheet called Map_states. A map was used to visualise the total number of employees in each states.
- Step 14 : Created new worksheet called Gender. A pie graph was used to visualise the total number of males and females employees both hired and terminated.
- Step 15 : Created new worksheet called Age vs Education. A graph was used to visualise the total number of employees according to their age and level of edication.
- Step 16 : Created new worksheet called Age_groups. A bar graph was used to visualise the total number of employees according to their age, i.e employees with ages less than 25 years, those that are between 25 and 35 and so on untill 55+ years.
- Step 17 : Created new worksheet called Education_level. A bar graph was used to visualise the total number of employees in each level of education. i.e High School, Bachelors, Masters and those with PHD.
- Step 18 : Created new worksheet called Education vs performance. A bar graph was used to visualise the total number of employees in each level and their overall perfomance.
- Step 19 : Created new worksheet called Gender vs Education. A graph was used to visualise the total number of employees in each level and their gender as well as the average salary.
- Step 20: Created new worksheet called Age vs salary. A graph was used to visualise the average salary of the role and the average age.
- Step 21: Finaly 2 dashboards were created. one shows all the visuals mentioned above and the is a filter button where they can choose which gender information to visualize or they are fitler by either status, location ot hired date.
- Step 22: HR can also navigate to endividual employees details. This will pop another dashboard where information such as ID, Demography, role, geographics, salary status of employement and length of employment will be shown. This information will show details for all employees unless HR enters certail ID to show individual details.
- Step 23 : HR can also download the information on the dashboard as pdf of save as a picture.

### Some insights
 
 ### Number of Employees
 
 - There is a total of 8,950 employees hired from 2015 to 2024.-
 - Active employees are 7,985.
 - 966 employees terminated  
 
 
 ### Departments

- Operations department has most hired employees, most active employees and most terminated employees, with 2429 active and 289 terminated employees.
- Sales department is the second most highest with 1634 active employees and 201 terminated employees.
- HR department has the least number of both active and terminated employees. There are 152 Active employees and only 12 terminated employees.

 ### Location

 - New York has most employees with the total number of 6,270, The city with most employees is New York City with 2,959 employees folowed by Rochester and Buffalo.
 - West Virginia is the state with least employees and the city is West Virginia with most employees is Charleston with 38 employees followed by Huntington with 34 employees and lastly Morgantown with 31 employees.

- Heardquarters has most employees (6,270), that is 70% of the employees and 30% is portion of employees working in Branches.

### Gender

- 54% of employees are Males while 46% of the employees are Females. In both genders, 11% of hired employees terminated while 89% is still active.

### Education & Age

- Most emplooyees (1,588) have Bachelors degree and are between 34 and 44 years.
- Less emplooyees (79) have PHD and are between 24 and 34 years.
- No employees who are less than 25 years and hold a PHD.

### Education & Perfomance

- In employees whose education level is High School, 34% need improvement, 32% satisfactory, 21% perfom good and 13% is excellent.
- In employees who have bachelors degree, 50% perform Good, 30% satisfactory, 12% excellent and 8% need to improve.
- In employees who have masters degree, 41% perform Good, 35% perform excellent, 19% satisfactory and 5% need to improve.
- In employees who have PHD, 48% perform excellent, 34% good, 13% satisfactory and 5% need to improve.
  
### Education, Salary & Gender 

- Females with High School level have average salary of 61,000 while males have an average of 63,000.
- Females with Bachelors degree have average salary of 66,000 while males have an average of 74,000.
- Males with Master degree have average salary of 80,000 while females have an average of 86,000.
- Males with PHD have average salary of 80,000 while females have an average of 93,000.

### Role, Salary & Gender 

- The average salary of a Finance Manager is 125,143 and the average age of this role is 50 years.
- Followed by IT Manager with average salary of 113,907 and average age of 45.
- HR assistant has the least average salary of 60,645 and average age of 38.


  ![Top Paying Roles](Assets/1_top_paying_jobs.PNG)
*Bar graph visualizing the salary for the top 10 salaries for data analysts.*


