# Auto Reply Gmail Bot using Node.js 

Description
-This is a repository for Auto_reply_gmail_api_app App Developed using Node.js and Google APIs.
-This app  is able to respond to emails sent to your Gmail mailbox while you’re out on a vacation.

 Features
- Node.js clusters support.
- Checks for new emails in a given Gmail ID.
- Sends replies to emails that have no prior replies.
- Adds a label to the email and moves the email to the label.
- This app checks above steps every 45 to 120 in b/w sec  random time interval. 

 Libraries  
-1.googleapis:This package is imported from the googleapis module and provides the necessary functionality to interact
   with various Google APIs, including the Gmail API.
-2.OAuth2:The OAuth2 class from the google.auth module is used to authenticate the application and obtain an access
   token for making requests to the Gmail API. It handles token refresh and retrying requests if necessary. 


