# Strom patterns and Organizational Responses


## Group Members
- Chung, Kai

- Goodwin, North 

- Im, Eunsang 

- Liu, Calvin 

- Chaux, Gabriel 


# Scenario

As the global population continues to increase, CO2 and greenhouse gas emissions continue to increase as well. Consequently, temperatures have also risen causing volatile weather patterns and more extreme storms. As a result, organizations, such as emergency services and insurance firms, must respond appropriately.

# Project Overview 

The scope of this project is to see how major organizations involved in storm events must react in an effective and efficient manner, to meet the requirements of their stakeholders. Our database used for this project is from the year 1959 due to a lack of comprehensive information in other data sets for other years. The two major groups of organizations we focused on in this project are insurance firms and emergency services. We manipulated the data to see…

1) Which states should have the highest insurance cost based on Tornado Events?
2) For which months should Emergency services invest the most payroll?

# Data Table

- The primary dataset used is based on 1959 storm events, which includes storm type, date, location, property damage, injuries, and more.
- The data can be accessed at https://catalog.data.gov/dataset/ncdc-storm-events-database2
  

<img width="1282" alt="Image" src="https://github.com/user-attachments/assets/d7ca1aad-bfc1-4b38-b116-9eb72c3cdbd4" />

* note that our data does not have complete data for states: Washington, Oregon, Nevada, Utah, Vermont, Massachusetts, New Jersey *


# Data Dictionary 

![Image](https://github.com/user-attachments/assets/3e6783e3-9eba-4603-8cf4-740acad5ac3e)

![Image](https://github.com/user-attachments/assets/a0b83e29-152a-428b-9148-2c69b2449417)

![Image](https://github.com/user-attachments/assets/2ef6c73e-b8be-417e-ac2e-70b7f64e878a)

# Questions

1) Which states should have the highest insurance cost based on Tornado Events?

<img width="378" alt="Image" src="https://github.com/user-attachments/assets/bef27cd4-5d82-431c-948d-6713c6247599" />


This question uses: 

- Rows: Longitude
- Columns: Latitude 
- Filters: Event Type 
- Marks: MAX(Tornado F Scale), SUM(Direct Deaths), State
  

2) When Should the Government Boost Storm Response Investment?


![Image](https://github.com/user-attachments/assets/132ef406-446b-4661-8657-aab5932f3f6e)


This question uses:

- Rows: COUNT(Event_ID)
- Columns: Month_name
- Marks: COUNT(Event_ID)


# Findings and Summary

- States like Texas and Oklahoma incurred the highest damage from tornadoes and should be prioritized for increased insurance premiums.
- Emergency services should prepare for increased activity in spring and early summer months, when storm-related injuries peak.


# Tools Used 

- Tableau (for visualization)
- Terminal on MacOS (for repository changes)
- Git & GitHub (for version control)
- Microsoft PowerPoint (for final presentation

# Cloning this repository 

1) Open your terminal

  
2) Navigate to the directory where you want to clone the repo

   "cd path/to/your/directory"
   

3) Clone the repository using Git

   "git clone https://github.com/Kaichung862/sql_project2.git"


4) Navigate into the project folder

   "cd sql_project2"


5) Open the project and enjoy!






