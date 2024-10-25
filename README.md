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
- Precondition: The user needs to be accessing the Home View
- Actors: A user wanting to view a specific post
- Basic Flow:
  1. The user clicks or otherwise selects a post
  2. The system displays the Post View pop-up
- Alternate Flow: The user can be accessing a search result, Account view or Community view, which automatically filters what posts are visible
- Exception Flow: If the user clicks an X icon, the pop-up closes
- Post-conditions: The user can view and make comments and engage with a post.
## 7. View Account
- Description: The user can select an account to view it in more detail
- System: The account view of the system's web app
- Precondition: The user needs to be accessing a Home view
- Actors: A user wanting to view a specific account
- Basic Flow:
  1. The user clicks or selects an account link
  2. The system presents the account view
- Alternate Flow: The user can be accessing a search result, a Post View or a Community View. If the user is logged in and viewing their own account, they have the additional option to change their bio
- Exception Flow: N/A
- Post-conditions: The user can view all of the account's posts
## 8. View Community
- Description: The user can select a community to view all posts that are part of it
- System: The community view of the system's web app
- Precondition: The user needs to be accessing the Home View
- Actors: A user wanting to view a specific community
- Basic Flow:
  1. The user clicks or selects a community link
  2. The system presents the community view 
- Alternate Flow: The user can be accessing a search result or a post view. If they are logged in, they are presented with additional options to join or leave the community based on their existing status with the community 
- Exception Flow: N/A
- Post-conditions: The user can view all posts that reference the community
# Signed-in Users
## 9. Account, Set Profile Picture
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 10. Account, Set Bio
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 11. Account, Logout
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 12. Account, Delete
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 13. Post, Make
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 14. Post, Delete
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 15. Post, Share
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 16. Post, Upvote
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 17. Post, Downvote
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 18. Comment, Make
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 19. Comment, Delete
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 20. Comment, Share
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 21. Comment, Upvote
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 22. Comment, Downvote
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 23. Community, Make
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 24. Community, Delete
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 25. Community, Join
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 26. Community, Leave
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 27. Friend, Request
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 28. Friend, Accept
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 29. Friend, Reject
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 30. Friend, Message
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
## 31. Block User
- Description:
- System:
- Precondition:
- Actors:
- Basic Flow:
- Alternate Flow:
- Exception Flow:
- Post-condition:
