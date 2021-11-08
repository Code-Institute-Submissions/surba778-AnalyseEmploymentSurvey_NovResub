# AnalyseEmploymentSurvey
This module analyses the employment survey details in the excel sheet named
employmentsurvey.xlsx.Excel sheet contains 5 different categories as sheet
and each sheet contains questions the survey results for same. It enables user to enter a survey data. In this
application we read each sheet in the excel sheet and calculate the percentage
of the survey results assuming the total no of employees as 40.And update
the survey result of all the sheets to sheet named Results.

## Features
  - This app make use of available employment survery data in an excel sheet, analyses the data and updated the analysed data into a sheet named Results.
    ![Excel before running](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/excel_before_running.JPG)
  - App asks for the username, presents him with a welcome message about the application, asks whether user would like to input the survey data.If yes,user would be prompted to
    select the topic and gets the data from the user.Once user has entered the survey data, data is updated to the excel sheet.
    ![Getting user survey data](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/get_user_survey_data.JPG)
    User data is updated to the excel sheet.
     ![User data is updated](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/user_data_updted.JPG)
  - Once the data is entered. User will be prompted whether he would like to analyse the data or not.If yes,survey data is analysed and 
    updates the final_data values to the sheet named Results and the final data is also printed to the console.
    ![Result sheet](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/results_sheet_created.JPG)
    ![Final output](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/finaloutput.JPG)
  - In order to parse the excel sheet, openpyxl module is used.
  - User gets an welcome message once he inputs his name and he can select whether he wants to execute the application or not.
  
## Testing
  - I confirmed that this project is responsive and works good.
  - Tested application with different input values.
  - Application prompts for a input, until a valid input is provided.
    - App validates the username and keeps prompting until a valid username is entered.
    ![Validating username](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/validating_username.JPG)
    - User should select only the listed topics i.e between 1 to 6. If not it keeps asking for the valid topic selection.
    ![Validating topic selection](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/validating_topic_selection.JPG)
    - While entering the survey data, user should provide the first value as a string since the fist value is question.This is also validated while the user inputs the data.
    ![Validating user survey data](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/validating_user_survey_data.JPG)
    
  
## Validator Testing
  - [Python validator](http://pep8online.com/) No error occurs.
     ![Pep8 image](https://github.com/surba778/AnalyseEmploymentSurvey/blob/main/readme-images/Pep8testing.JPG)

## Improvements
  - Would like to implement below features in future.
    - In order to make this program more user friendly, the ability to export the database to a printable format - such as a PDF.

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

## Credits
- **Code Institute** - for git template IDE and heroku deployment instructions.
-  [Openpyxl module](https://openpyxl.readthedocs.io/en/stable/tutorial.html) for reading and writing the excel sheet data.
- Mentors help and advice
- Tutors help
