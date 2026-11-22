# Plan Document 
This has both of my plans for the 4.3 Hw, and my plans for setting up this repository 
## Hw 4.3 plans 
Goal: Create a reproducible Quarto document that organizes data and creates graphs, that can be downloaded and rendered
Sub-goals:
- Make a summary table for different diamond dimensions by clarity 
- Create a plot that compares the Big Ten Women's Basketball teams 
- Use the Monte Carlo integration and estimate the area under a curve 
- Compare gen AI responses based on when given a plan or not
- Reflect on what has been learned in the course
Needs:
- R Studio, packages(tidyverse, knitr, kableExtra), Quarto, Tinytex, Github
- Diamonds data from ggplot2, the Big Ten Women's basketball data from the BTAA competition, and given calcium data
- The Quarto website guide
- The given Claude response photos
Steps:
- Set up the Quarto document starting with the YAML header
- Write the entire setup chunk to prepare the code for each of the datasets needed
- Tidy and organize the diamonds data, making summary tables that show clarity by dimension
- Make a Big Ten bar graph showing the average points per game
- Run the Monte Carlo estimation for 10, 100, 1000, and 10000 points
- Write the plan for the calcium data, give it to Claude, and compare it to the response it gives when no plan was given
- Write all of the narrative texts and use cross-referencing
- Add in the personal reflection for the course, and the code and gen AI appendix
- Render the PDF
## Repo Plan 
Goal: Put all of the parts of HW 4.3 into a public repository that has all of the branches, issues, and commits for the project 
Needs: 
- A Github account and access to the website 
- The different files from the project (ReproducibleDataAnalysis.qmd, ReproducibleDataAnalysis.pdf, teams.csv, team_box.csv)
- The given images from the generic Claude response
- This plan doc and the completed README
Steps:
- Make the 4.3 project repository and make it public
- Make a dev branch to do all of the changes on
- Make different issues for the tasks: adding the reproducible data analysis qmd and pdf, and one for finishing the README
- Add in the files, having the commits close the issues
- When adding the team_box.csv file, add it using the Github desktop since the file is too large
- Open a pull request to merge everything from the dev branch to the main one
- Make any new changes on the dev branch, and then pull and merge to the main branch 
