# Pewlett-Hackard-Analysis

## Overview/Purpose of the analysis: 
   * The purpose of this report is to better prepare Bobby's manager for the upcoming "silver tsunami." By leveraging SQL (pgAdmin), we were able to determine the number of retiring employees per title and identified the employees who are eligible to participate in a mentorship program. 
   * Of note, In order to ensure we stayed organized and maintained a clear understanding of the relationship between each spreadsheet, we continously referenced the Entity Relationship Diagram (ERD) we initially created (pictured below). This diagram proved to be essential in the table creation process since primary keys and foreign keys needed to be designated properly.    
     ![ERD](Analysis_Projects_Folder/Pewlett-Hackard-Analysis_Folder/EmployeeDB.png)
   
## Results: 
   * Deliverable 1: Determining the number of retiring employees per title
     * In order to determine the number of retiring employees per title, we first created a SQL table named "retirement_tables" which combined pertinent data from the "employees" and "titles" tables such as employee number, last name, first name, titles, etc and extracted only the birth dates between 1952 and 1955. The table was then exported as a csv. 
     
   * Delverable 2: Identifying the employees eligible to participate in a mentorship program

## Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
   * How many roles will need to be filled as the "silver tsunami" begins to make an impact?
   * Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
