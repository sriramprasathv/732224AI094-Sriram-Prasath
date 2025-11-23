- First, create a new workflow inside n8n.
- A form submission is used to trigger the first workflow.
- After the user submits the form, the submitted data is inserted as a new row into Google Sheets.
- When this new row is added, the Google Sheets Trigger automatically activates.
- The triggered workflow then uses the Gmail node to send an email, using the information stored in the newly added row.
# Screenshot
<img width="1549" height="518" alt="4" src="https://github.com/user-attachments/assets/070ec5d0-8f7d-4515-8fac-47eb453871cc" />
