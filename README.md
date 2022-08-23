# Unit 4 Homework: Pandas, Pandas, Pandas
In this assignment, you’ll create and manipulate Pandas DataFrames to analyse school and standardised test data.


## Before You Begin

1. Create a new repository for this project called `pandas-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Inside your local Git repository, create a folder for this homework assignment and name the folder `PyCitySchools`.

4. Add your Jupyter notebook to this folder. This will be the main script to run for analysis.

5. Push these changes to GitHub or GitLab.



## Background

Having spent years analysing financial records for big banks, you've finally scratched your idealistic itch and joined the education sector. Your latest role is Chief Data Scientist for your local government area. In this capacity, you'll be helping to make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyse the area-wide standardised test results. You'll be given access to every student's maths and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

## Instructions

Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

**Hint:** Check out a [sample solution](PyCitySchools/PyCitySchools_starter.ipynb) to review the desired format for this assignment.

### Local Government Area (LGA) Summary

Create a high-level snapshot, in a DataFrame, of the area's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average maths score
* Average reading score
* % passing maths (the percentage of students who passed maths)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed maths AND reading)

### School Summary

Create a DataFrame that summarises key metrics about each school, including the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average maths score
* Average reading score
* % passing maths (the percentage of students who passed maths)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed maths AND reading)

### Highest-Performing Schools (by % Overall Passing)

Create a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average maths score
* Average reading score
* % passing maths (the percentage of students who passed maths)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed maths AND reading)


### Lowest-Performing Schools (by % Overall Passing)

Create a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average maths score
* Average reading score
* % passing maths (the percentage of students who passed maths)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed maths AND reading)

### Maths Scores by Year

Create a DataFrame that lists the average maths score for students of each year level (9, 10, 11, 12) at each school.

### Reading Scores by Year

Create a DataFrame that lists the average reading score for students of each year level (9, 10, 11, 12) at each school.

### Scores by School Spending

Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:

* Average maths score
* Average reading score
* % passing maths (the percentage of students who passed maths)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed maths AND reading)

### Scores by School Size

Create a table that breaks down school performance based on school size (small, medium, or large).

### Scores by School Type

Create a table that breaks down school performance based on type of school (government or independent).

### Submission

On [Bootcamp Spot](https://bootcampspot-v2.com), submit a link to the `pandas-challenge` repo that you created for this assignment. Be sure to include a `README.md` file in addition to the Jupyter Notebook that contains your report.

## Rubric

[Unit 4 Homework Rubric](https://docs.google.com/document/d/1VwP0gfKN-ZGZvIhuaKmx00wCcPOMC5qofXXFcUGe90E/edit?usp=sharing)

- - -

## References

Data generated by Mockaroo, LLC. (2021) Realistic Data Generator. [https://www.mockaroo.com/](https://mockaroo.com/). Modified by Trilogy Education Services, LLC.

- - -

© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
