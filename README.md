# Passwordless-Login-Solutions-for-iOS-by-Facebook
Passwordless-Login-Solutions-for-iOS-by-Facebook

### Account Kit
Account kit enables users to log in using their phone number or email address and authenticate their identity with no password and no Facebook account.
* Set up your Facebook Developer Account
* Download and configure the Facebook SDK
* Configure the login View Controller
* Initiate the login flow
* Handle the Account Kit Callbacks
* Access Account Information
* Logout
#### 2 ways to authenticate
1. client access token
   * simpler to implement
   * long-lived token
   
2. authorization code
    * requires extra steps server-side
    * authorization code is short-lived
    * client never sees the token

### Facebook Login
Facebook login allows a user to log in with the clock of a button and authenticate their identity using their Facebook credentials.
#### How Facebook Login Works
  * The client requests access and permissions
  * The user authenticates and approves permissions
  * An access token is returned to the client
  * User enters the app
 
### Facebook allows developer to create a test user to test
#### Test plan for Facebook Login
1. Common Flows:
    * A new user logs in with Facebook
    * A returning user logs in with Facebook with and without the facebook app installed
2. Unexpected conditions
    * A new user declines to authenticate permissions once, then tries to log in again
    * A returning user who has changed their password
    * A returning user with an expired token
    * A returning user who logs in after disabling the Facebook platform
#### Test plan for Facebook Login
1. Common Flows:
    * A user logs in with a phone number
    * A user logs in with an email address
2. Unexpected conditions
    * A user tries to log in, but doese not receive the SMS
    * A user types in the wrong code
