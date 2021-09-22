# SignUpForm
An android application to collect a user's name, email, password, and a password confirmation. 

## Features
This sign up form application is used to create a new account for the user. All text entries are validated using the built in
TextUtils class. The username field will be checked for an empty condition. The email field will be checked for an empty condition
and will be pattern matched for email address validation. Both passwords are checked for empty conditions and the
confirm password field will be checked for an equals condition to the previous password field.
If all of these fields pass the validation conditions a toast message will be shown "Welcome, UserNameVar, to the SignUpForm App"
after the user presses the register button.

##Screenshot
![login screen screenshot](Screenshot_SignUpForm.jpg)
