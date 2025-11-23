# Populating Sheet
- create a new work flow in n8n
- Trigger: The workflow starts when the "Execute workflow" button is clicked.
- Get Data: The next step involves retrieving data from a specific Google Sheet with the "Get row(s) in sheet" action.
- Conditional Check: An If condition is used to check a specific condition (likely based on the data retrieved).
- True Path: If the condition is true, a row is appended to "Append row in sheet" (likely one sheet).
- False Path: If the condition is false, a different row is appended to "Append row in sheet1" (likely another sheet).
# Screenshot
<img width="1398" height="747" alt="image" src="https://github.com/user-attachments/assets/a115f0cc-64fe-4f84-a589-1adef5fb6204" />
