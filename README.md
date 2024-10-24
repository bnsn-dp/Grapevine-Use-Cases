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
- Description: The user can search for specific posts using the description
- System: The search bar component
- Precondition: The user needs to access the system online
- Actors: A user wanting to find a specific post
- Basic Flow:
  1. The system presents an input field
  2. The user provides a search term
  3. The system returns a list of posts that contain the search term
- Exception Flow: If the user clicks outside of the pop-up, the pop-up closes and empties the input field
- Post-conditions: The user can select a return result to view it
## 4. Search Account
- Description: The user can search for specific accounts using their username
- System: The search bar component
- Precondition: The user needs to access the system online
- Actors: A user wanting to find a specific account
- Basic Flow:
  1. The system presents an input field
  2. The user provides a search term
  3. The system returns a list of accounts that contain the search term in their username
- Exception Flow: If the user clicks outside of the pop-up, the pop-up closes and empties the input field
- Post-conditions: The user can select a return result to view it
## 5. Search Community
- Description: The user can search for specific communities using their name 
- System: The search bar component
- Precondition: The user needs to access the system online
- Actors: A user wanting to find a specific community
- Basic Flow:
  1. The system presents an input field
  2. The user provides a search term
  3. The system returns a list of communities that contain the search term in their bio
- Exception Flow: If the user clicks outside of the pop-up, the pop-up closes and empties the input field
- Post-conditions: The user can select a return result to view it
## 6. View Post
- Description: The user can select a post to view it in more detail
- System: The post view of the system's web app
- Precondition: The user is on the Home View
- Actors: A user wanting to view a specific post
- Basic Flow:
  1. The user clicks or otherwise selects a post
  2. The system displays the Post View pop-up
- Alternate Flow: The user can be on an Account view or Community view, which automatically filters what posts are visible
- Exception Flow: If the user clicks an X icon, the pop-up closes
- Post-conditions: The user can view and make comments and engage with a post.
## 7. View Account
- Description: The user can select an account to view it in more detail
- System: The account view of the system's web app
- Precondition: The user needs to access the system online
- Actors: A user wanting to view a specific account
- Basic Flow:
- Exception Flow:
- Post-conditions:
## 8. View Community
- Description: The user can select a community to view all posts that are part of it
- System: The community view of the system's web app
- Precondition: The user needs to access the system online
- Actors: A user wanting to view a specific community
- Basic Flow:
- Exception Flow:
- Post-conditions:
# Signed-in Users

# Communities
