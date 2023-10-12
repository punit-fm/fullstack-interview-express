Time - 45 mins
## Steps to follow

- Clone this repository
- Start a server in express app
- Use ***studentsData.json*** to import the data
- Tasks
  1. Create an API to return all the data in response
  2. Create an API to take **roll_no** as parameter and return the following json data in response
     ```
     {
       "roll_no": number,
       "name": string,
       "average_marks": number,
       "maximum_marks": number,
       "minimum_marks": number
     }
     ```
  2. Create an API to take **subject name** as paramter and return the following json data in response
     ```
     {
       "subject": string,
       "maximum_marks": number,
       "name": string
     }
     ```
  3. Use error handling to manage the APIs properly

*Note: Be sure to follow best practices for coding, including properly commenting your code and organizing it in a way that is easy to read  and understand.*

### Structure of studentsData.json file

The file has json data of marks of students in different subjects