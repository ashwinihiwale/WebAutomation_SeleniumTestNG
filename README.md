# WebAutomation-OrangeHRM-Selenium-TestNG
## Scenario
Login to orange hrm demo site https://opensource-demo.orangehrmlive.com/
Create 2 new employees and save it to a JSON list
Now go to PIM dashboard and search by 1st user name. Assert that the user is found.
Now click on the user from the search table and update id by random userid
Now again search the user by new user id from the PIM dashboard menu and assert that the user is found
Now logout from admin and login with the 2nd user from your JSON list
Now click on My Info menu
Select Gender and Blood Type and save it
Click on contact details and input address and email
Logout the user

# Technology and Tool Used
  - Selenium Webdriver
  - TestNG
  - Java
  - Maven
  - intellij idea


# How to run this project
- clone this project.
- hit the following command into the terminal.
  gradle clean test.



#Report

<img width="804" alt="image" src="https://github.com/user-attachments/assets/15e1b8e1-8e16-44c2-a1ef-683f607402a8">


