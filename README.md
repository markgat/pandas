# pandas
Large data set of grades, students, and budgets spanning 15 schools analytically explored through Pandas' DataFrame capabilities. Passing rate is  defined as having a score that is equal to or greater than 70. Education is essential, and having the analytical skills to see what is going within institutions is invaluable. 
![school](school.jpg)
## Getting Started
### Installing
1) Git clone the repository to your local machine:
    ````
    $ git clone https://github.com/markgat/pandas.git
    ````
## Running
1) Create a terminal within the directory of the local repository, and enter the command ````$ jupyter notebook```` with a "y".
2) When the new page loads, locate ````school_analysis.ipynb```` within Panda->PyCitySchools and open it
3) From here, you can run the blocks one-by-one by selecting the first block and clicking "Run" on top, for each cell, to see the process of analytics, or selecting "Cells" from the top bar and then "Run All" to see it execute all at once.
4) To shutdown, select "Quit" on Jupyter directory webpage.
## Data Preview
### Source Data (Schools)
CSV record of 15 schools listing its ID, name, whether it is a district or charter school, the size/population of the institute, and overall budget.

![Schools](Images/schools.png)
### Source Data (Students)
CSV with a record of 39,170 students. Each student has their listed ID, name, gender, grade, school name, reading score, and math score.

![Students](Images/students.png)
### Output: Merged Student and Schools CSVs
Initial data manipulation is a merge of both CSVs by joining relevant school information to the corresponding student.

![Merged_Data](Images/merged_csvs.png)
### Output: Short Overall Summary
A very brief, holistic summary to quickly assess performance of all the students by average scores and percentages. This is prefixed by a total count of schools, students, and dollars in budget to give a sense of scale for the data. 

![Overall](Images/overall_avgs.png)
### Output: Merged CSVs Organized by School
An overall summary organized by the 15 individual schools, and their students' performances by averages. Total school budget and its derived individual student budget, total school budget, total student count, and type of school are also included in order to give context to the averages and schools.

![Summary_by_Schools](Images/merged_summary.png)
### Output: Schools