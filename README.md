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
