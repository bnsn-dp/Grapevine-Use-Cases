# Universal Users (Use cases available to all users, regardless of whether they are logged in to an account)
## 1. Create Account
- Description: A user can create an account to access the system's full features
- Pre-condition: The user needs to access the system online
- System: Account Creation View of the system's Web App
- Actors: User interacting with the system
- Basic Flow:
  1. The system prompts the user for information including their first and last names, a valid email address, a username, and a password and provides information specifying what defined valid data
  2. The user provides information and attempts to proceed
  3. The system checks for the validity of the email address, username, and password
  4. If the information provided is valid, the system generates a new authenticated session token
- Exception Flow: If the information provided is invalid, the system returns to step 1, notifying the user of what information provided was invalid
- Post-conditions: The system presents the Home View
## 2. Login
- Description: A user, after creating an account, can login to an account
- System: Login View of the system's web app
- Precondition: The user needs to access the system online
- Actors: User with access to the credentials of an account that exists
- Basic Flow:
  1. The system prompts the user for login credentials (username, password)
  2. The user provides information and attempts to proceed
  3. The system checks for the validity of the credentials
  4. If the credentials are valid, the system generates a new authenticated session token
- Exception Flow: If the information provided was invalid, the system returns to step 1, notifying the user of what information provided was invalid
- Post-conditions: The system presents the Home View
## 3. Search Post
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Exception Flow:
- Post-conditions:
## 4. Search Account
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Exception Flow:
- Post-conditions:
## 5. Search Community
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Exception Flow:
- Post-conditions:
## 6. View Posts
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Exception Flow:
- Post-conditions:
## 7. View Account
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Exception Flow:
- Post-conditions:
## 8. View Communities
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Exception Flow:
- Post-conditions:
# Signed-in Users

# Communities
