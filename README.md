# Universal Users (Use cases available to all users, regardless of whether they are logged in to an account)
## Create Account
- Description: A user can create an account to access the system's full features
- Pre-condition: The user needs to access the system online and have a valid session token
- System: Login View of the system's Web App
- Actors: User interacting with the system
- Basic Flow:
  1. The system prompts the user for information including their first and last names, a valid email address, a username, and a password and provides information specifying what defined valid data
  2. The user provides information and attempts to proceed
  3. The system checks for the validity of the email address, username, and password
  4. If the information provided is valid, the system automatically logs the user in to their account
- Exception Flow: If the information provided is invalid, the system returns to step 1, outlining what information provided was invalid
- Post-conditions: The system presents the Home View
## Login
## View Post
## View Other Account
## View Community
## Search Posts
## Search Accounts
## Search Communities
# Signed-in Users

# Communities
