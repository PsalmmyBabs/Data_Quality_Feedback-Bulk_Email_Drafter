Data Quality Feedback – Bulk Email Drafter:
After the processing of credit data submissions received from the data providers, data quality feedback is shared with each data provider. This task can be hectic especially when you are sending to multiple institutions at the same time. Hence, the idea behind the script, it streamlines the delivery of the feedback to the data providers via emails.

Objective:
The package streamlines the process of sending data submission feedback emails to multiple recipients.
Main Features
1.	Email connection.
2.	Draft Email Creation
•	Read Email Template: Reads the body content for the email from the embedded HTML code in the overall Python script and creates it in an email draft.
•	Email Subject: Applies the customized subject lines for the email.
•	Data Transformation: Transforms specific content in the "Rejected" and “Un-updated" Accounts Excel files and attaches them to the email draft.
•	Recipients: Adds from a contact list the recipients’ email addresses to the "To" and "Cc" fields of the email item.
3.	Save Drafts: Saves the draft emails in the Outlook “Drafts” folder and iterates the process for others.

Inputs Required:
The user is required to provide the following inputs:
1.	The main folder containing subfolders of worksheet files(‘un-updated records’ and ‘rejected records’) and the filepath that leads to it.
2.	A worksheet containing contact details and the filepath to it.
3.	The signature of the sender and the filepath to it.

Importance:
1. Efficiency: It automates the repetitive tasks of drafting emails, formatting Excel files, and transforming data. This saves time and reduces errors.
2. Consistency: By using a template for the email content and applying consistent formatting to Excel files, the automation ensures that all emails maintain a professional and uniform appearance.
3. Informative and Actionable: The automation simplifies specific contents in the Excel files, making the feedback more explanatory.
4. Scalability: It can handle multiple emails, making it suitable for large-scale data submission feedback.
5. Customization: It can be customized to include additional features or transformations as needed.

Resources Required:
To implement the process, you would need the following resources which are either free or readily available.
1.	Outlook Desktop Application
2.	Python Programming Tool
3.	Text Editor or IDE

Cost Implication:
None to implement or run the program.

In conclusion, the Bulk Email Drafter streamlines the process of providing data submission feedback, making it an essential tool for drafting data quality feedback in batch emails.
