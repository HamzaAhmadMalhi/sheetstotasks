# sheetstotasks
Transfer Google sheets to Google tasks in bulk.
Link- https://docs.google.com/spreadsheets/d/1QmVulqVtvbFpQA1UrI6f8dV2q1xZi5gk3Plnw_0eC5o/edit?usp=sharing

## CSV
Please Go to file > Make a copy

Date      | Assignments
DD/MM/YY    Task name

## App Scripts

### code.gs
Change with the sheetname and the tasklist name you want to view in google tasks
line 6 and 7 of the code.gs
  const sheetName = "_____________________"; // Name of your Google Sheet (not the tab name)
  const taskListName = "__________________"; // Change or set to an existing list
### Services
Add the googletasksAPI
