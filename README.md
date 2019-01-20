# Project-2-Artistic-Gymnastics-World-Championship

USA Artistic Gymnastics World Championship


Getting Started
Please find within this repository the following files associated to the project:
    - GYM README.md
    - Gym_Analysis.ipynb
    - Artistic Gymnastics World Championship.pptx
    - ALL_Gym_Team_Finals.csv
    - USAGym_Indiv_All_Around.csv
    - Images folder
        - Graph Plot 1: team.png
        - Graph Plot 2: indvidual.png
        - Image of the database and tables: MySQL database and tables image.PNG

Prerequisites
We already had all the software installed that was needed for this project.

Built With
    - Chrome
    - Visual Studio
    - MS Excel
    - MySQL
    - Jupyter Notebook
    - Github
    - Python
    - Pandas
        - Pandas Libraries
            - pandas
            - matpltlib
            - sqlalchemy
            - mysql.connector
            
Steps:

  - We began by researching the specific websites that gave us the listings of scores for the Gymastics Championship. Within the website we first attempted to scrape the data. But as we looked through the html inspect element page, we came to realize that the data posted on webpage was a pdf format and couldn't be scraped.

  - As our secondary option, we copied and pasted the data into excel, and arranged the data in to a readable format that could be imported to the database and another source.

  - Using MySQL we created a new database named usa_gyms so we can perform Extract Transform Load - ETL operation to import our data into database. Once we had the data in MySQL, we realized that there are still some additional scrubbing needed to be done as well as some missing data to be added. 
      - For Scrubbing - Re-arranged the column names
                      - Performed Update functions on rows and column data that were missing and/or misplaced. 

  - The next portion of the project, we used git bash to open the jupyter notebook to begin writing our code and performing further analysis.    

  - Once we opened our jupyter notebook, we first had to initiate the connection to MySQL database where we stored our data. As soon as we were able to make the connection to the database, we began writing code to pull the two tables of data and placed into individual dataframes.

  - We began to analyze and brainstorm how we could best plot the data using different python libraries. We decided to use pandas, matplotlib and sql alchemy libraries to build our visualization.     

  **Please reference "Gym_Analysis.ipynb" jupyter notebook file to see how we coded and developed our diagrams. There is a reference text throughout the code walking you through each developments.**  
             

Authors 
Shefali Sinha   Gathering Data, cleaning data, research, Analysis, presentation development
Sidney Katz     Inspired Subject, research, Coding
Lauren Taft     Gathering Data, research, MySQL ETL, Analysis, presentation development
