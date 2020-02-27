# Baltimore_fire_department_salary_vs_employment_time
![image](https://github.com/Jason112Fu/Baltimore_fire_department_salary_vs_employment_time/blob/master/Annual%20salary%20vs%20employment%20time.png)

The equation means the average initial annual salary is $51168 and increases $1384.3 per year. The R square is the proportion of the variance in the dependent variable that is predictable from the independent variable. In this case, it means 49.02% of the annual salary change is caused by the employment time change.

industry question: what is the relationship between annual salary and employment time in Baltimore City fire department.

data question: the linear regression of annual salary and employment time data

data answer: as described above

industry answer: as described above


https://data.baltimorecity.gov/browse?category=City+Government


Description:

clean the DESCR column to remove the department subcategory numbers.

Insert a new column after the HIRE_DT column and name this employment_time_years. In the first cell of this column type in =TODAY()- and then click on the cell in that row under the HIRE_DT column, and drag this value down for the length of our column.

filter dataset for Baltimore City fire department.

choose column "empolyment_time_years" and "ANNUAL_RT" to do linear regression.
