# AnalyseEmploymentSurvey
This module analyses the employment survey details in the excel sheet named
employmentsurvey.xlsx.Excel sheet contains 5 different categories as sheet
and each sheet contains questions the survey results for same. In this
application we read each sheet in the excel sheet and calculate the percentage
of the survey results assuming the total no of employees as 40.And update
the survey result of all the sheets to sheet named Results.


## Features
  - This app make use of available employment survery data in an excel sheet, analyses the data and updated the analysed data into a sheet named Results.
  - This create a new worksheet called Result and update the final_data values to the sheet.
  - In order to parse the excel sheet, openpyxl module is used.
  - User gets an welcome message once he inputs his name and he can select whether he wants to execute the application or not.

## Testing
  - I confirmed that this project is responsive and works good.
  - Tested application with different input values.
  - Application prompts for a input, until a valid input is provided.
  
## Validator Testing
  - [Python validator](http://pep8online.com/) No error occurs.

## Improvements
  - Would like to implement below features in future.
    - User should be able to input the survey details.
    - Update the excel sheet with the user input and analyse the data.

## Technologies used
  - [GitHub:](https://github.com/)
    - GitHub is used to store the project's code after being pushed from Git.    
  - [VisualStudio](https://code.visualstudio.com/)
    - Visualstudio is used to develop the code and then to store this code in the Github.

## Deployment
- The site was deployed to Heroku pages and the live link can be found here [Live link](https://analyseemploymentsurvey.herokuapp.com/)
  The project was deployed to Heroku Pages using the following steps...
    1. Log in to Heroku and then from the Heroku dashboard click the "create new app"
    2. Now, if you look at the navigation at the top, you'll see  Overview, Resources, Deploy, Metrics  and so on. Be sure that Deploy is selected. 
       Then on the second row, click on the GitHub icon.
    3. Once the application is successfully connected with Heroku account, click Deploy Branch to deploy your application.
    4. Once the application has been deployed,click on View to open application.
    5. Heroku allows developers to quickly and almost painlessly deploy an application on a web server.
    6. Log in to GitHub and locate the [Github repository](https://github.com/surba778/AnalyseEmploymentSurvey)