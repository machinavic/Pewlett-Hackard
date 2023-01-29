# Pewlett-Hackard-Analysis

##Overview of the analysis: 
On this assignment, functions and other processes related to the SQL handling were learnt.

This particular job was focused to optimize the Human Resources strategies for a company named Pewlett- Hackard, determining in first place the number of Retiring Employees by Title as first question, and in second instance the amount of Employees Eligibles for Mentorship program was determined as well.

In order to retrieve all those answers, 6 tables were created initially and later on 6 more as product of joining some of the initial tables to deliver the requested results.

##Results: 

**Deliverable 1: Number of Retiring Employees by Title.
Retirement Titles were determined first, so 133776 employees were determined in this step.

![retirement_titles_image]

As second step within this deliverable, duplicate rows were removed using the "DISTINCT ON" statement. This time, out of 133776 employees in the first query, 72458 were determined this time.

![unique_titles_image]

And as final, the number of employees by their most recent job title who were about to retire were retrieved using the "COUNT()" statement as well: Out of all the titles, only these seven positions (7) were shown.

![retiring_titles_image]

**Deliverable 2: Employees Eligible for Mentorship Program.

To work on this, three (3) tables were joined together, and duplicated rows removed using the "DISTINCT ON" statement. Data was filtered and 1549 employees will be mentored as shown here below:

![mentorship_eligibility_image]

##Summary: 

Summarizing the analysis, 133776 employees will be retired, and just 1549 roles will be ready to mentor the next generation of Pewlett Hackard employees.