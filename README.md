#                                                   Module 7 Challenge - April 2020
##                                                           Doris B. Cohen


### Technical Analysis
Recently, we did an internal review of all staff, their department, title, salary and retirement eligibility. Based on this review, it is noted that nearly 10% of our staff is eligible for retirement! Due to the size and percentage of retirement candidates, this is a “silver tsunami” of sorts. This could have a significant impact on our business. We strive to deliver the best services to our internal and external customers. With 33,118 people eligible for retirement, we could lose quality of service, momentum, as well as company intellect and understanding. We welcome new employees coming on board but take pride in our tenured staff and the skillset they bring to the fold. 

**Title	            Total**
 -Senior Engineer	  8,434
 -Senior Staff	    7,889
 -Engineer	        7,387
 -Staff	            7,005
 -Technical Leader  1,609
 -Assistant Engineer	792
 -Manager	              2
 **Eligible ret   	33,118**

I utilized our Human Resources and department mental information which included; department, salary, title, employee number, employee birthday and employee start date to determine ways to get ahead of this “silver tsunami”. In doing so, I filtered thru our data to focus on how many people are eligible for retirement and who could serve as mentors. I used various SQL functions; GROUP BY, DISTINCT ON, PARTITION, ORDER BY, COUNT, INTO, SELECT, INNER JOIN, OUTER JOIN, AS, ON, DESC, FROM and WHERE. I faced some challenges in this project, as I realized that the way we capture the data per employee does lend itself to conflated numbers. So, I methodically went thru the data to provide the best summary of our employee information so we can make decisions on next steps. I used PgAdmin to analyze, cull and synchronize the data and remove duplicates. The SQL statements are listed in the file called ModuleSevenChallenge.sql. This files provides a step-by-step summary of the datasets and how I completed each part of the analysis.  








In this analysis, it became clear that time is of the essence. We have a significant number of employees who are eligible for retirement. This is great for them but poses some challenges to our company. We will lose significant intellectual resources, as many of these candidates eligible for retirement are engineers and senior staff. To that end, we have a unique opportunity to work with a group of these individuals who can mentoring the next generation of Pewlett Hackard employees. This is great news! The only downside is that this group only makes up a small fraction of those eligible for retirement. We have 1,549 employees that can participate in our mentoring program. This only 5% of the number of employees eligible for retirement. Thankfully, this is a cross-section of the employees who are eligible for retirement. The only group that is not represented in this list are Managers. However, there are only 2 managers on the retirement list. Although this is an important role, the number is small. 

Mentoring Program by Title	 Total 
Assistant Engineer	29
Engineer	190
Senior Engineer	529
Senior Staff	569
Staff	155
Technique Leader	77
Grand Total	1,549






Pewlett Hackard is committed to excellence and professionalism in the workplace. We are the industry leader in providing the best products and services in our market. We strive to be in sync with the mission, vision and values that are present in all we say and do. For this reason, I have provided a detail list of the analysis, along with recommendations for future growth and planning.
In order to have a successful transition and “changing of the guards”, I recommend the following, as it will benefit our current, new and retiring staff. This will put Pewlett Hackard in a good position to be prepared for they months and years ahead.
Recommendations:
1.	Put a system in place to start the mentoring program
2.	Make sure all the necessary components of a mentoring program are in place
3.	Notify eligible mentoring candidates
4.	Work with Human Resource to promote 2 new managers
5.	Provide retirement information to those leaving the workforce
6.	Begin a hiring campaign
7.	Review salaries to determine equity in roles, experience and education as the hiring process begins. 

Files and attachments:
•	Postgres/PgAdmin 	ModuleSevenChallenge.sql, Challenge7.tar

•	NotNull/ValueLength	schemas.sql

•	Table 1: Number of Retiring Employees by Title
o	PNG		recenttitle.png
o	CSV		recenttitle.csv
•	Table 2: Mentorship Eligibility
o	PNG		tipartsal.png
o	CSV		tipartsal.csv

•	Tech Report		Challenge7TechnicalAnalysis.docx

•	Schemas 
o	Conceptual ERD	ConceptualERD.png
o	Logical ERD		LogicalERD.png
o	Physical ERD		PhysicalERD.png

•	Module Exercises
o	Queries		queries.sql
o	Test tables		testtables.sql
o	Exercises		finalmossevenexercises.sql
o	Downloads
	departments.csv
	employees.csv 
	dept_manager.csv
	dept_emp.csv
	salaries.csv
	titles.csv

If you have any questions or require additional files and information, please do not hesitate to contact. I’m available by phone, email or Slack. 

Authored by Doris B. Cohen
PostgreSQL Practitioner
