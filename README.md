# School District Analysis

## Overview of School District Analysis

## Purpose of the analysis

- The purpose of the analysis is to help Maria analyze data on student funding and students' standardized test scores and to further aggregate the data to showcase trends in school performance.
- These insights in data will be used to make informed discussions and take strategic decisions at the school and district level.

## Resources

- Data Source: [Student Data](https://github.com/manasidek/School_District_Analysis/blob/main/Student_Data_Challenge_Starter_Code/Resources/new_full_student_data.csv)
- Software: Anaconda 22.9.0 ,Python 3.7.6,Jupyter Notebook 6.4.12

## Student Analysis Results

The Script for the analysis is: [Student Data Code](https://github.com/manasidek/School_District_Analysis/tree/main/Student_Data_Challenge_Starter_Code/Solved)

### Collecting the Student Data

Import the Data from the file and store it in a DataFrame. This DataFrame is displayed as follows

The Script used to read the data is:
```
# Create the path and import the data
full_student_data = os.path.join('../Resources/new_full_student_data.csv')
student_df = pd.read_csv(full_student_data)

# Verify that the data was properly imported
student_df.head()
```

Student Data File:

![DataFile](https://github.com/manasidek/School_District_Analysis/blob/main/Images/Student_Data.png)


### Preparing the Student Data for Analysis

- The process of cleaning data needs to begins with checking for null values and duplicate values.

![]()

![]()


- After the above process is completed then checks have to be performed for data types.Changes must be done in order to make data available for analysis. For this data the "grade" column needed to be ultered for analysis.

![]()

![]()


### Summarize the Clean Data

One final check must be performed to confirm that the data is clean.

![]()

### Drilling Down into the Data

- This is the analysis phase. 

- Displying the ultered "grade" column

Student Grades:
![Grade Range]()

- Displaying the first 3 rows and selected columns of data

Selected Row-Column Data:
![3 Rows and 3 columns]()


- Summary for Grade 9 for all the schools

Grade 9 summary:

![Grade9]()


- Dislaying the student with lowest reading score

![Lowest Reading Score]()

- Reading Score for a specific School and specific Grade

![Reading Scores]()

### Comparing the Student Data

- Comparing the type of schools for the math andreading scores

![School Type]()

- Number of students in each school from highest to lowest

![Student Count]()

- Allocated Budget for each grade in Charter and Public Schools

![School Budget]()


## Summary of the Analysis

### Discoveries Made:

- The overall Reading Score is higher than the overall Math Score.

- Math Scores are higher in Charter Schools in comparison with Public Schools, while Reading Scores remain consistent.

- The allocated School Budget for Public Schools is higher than that for Charter Schools.

### Some more analysis than can be performed:

- Analysis can be performed to count the no. of students and no. of schools in each type.

- Perform analysis to count no. of students in each grade in order to justify higher budget allocation in lower grades for Public schools.


