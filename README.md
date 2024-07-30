This React application allows users to manage their accounts. It includes functionalities for registration, login, and profile management. 
Users can view and update their personal information, which is stored in local storage for persistence. Basic styling is done using Bootstrap.

Features
1. Login Page:
Allows users to log in using their email and password.
Validates credentials against stored registration details in local storage.
Displays error messages if the email or password is incorrect.

2. Registration Page:
Users can register with the following details:
First Name
Last Name
Date of Birth (DOB)
Gender
Email
Password
Stores registration details in local storage upon successful registration.
Displays a success message upon successful registration.
Redirects to the login page after registration.

3. Profile Page:
Accessible after a successful login.
Displays the user's registered details (First Name, Last Name, DOB, Gender, Email).
Allows users to update their profile information.
Updates the information in local storage upon changes.

Technical Details
-React Version: V16+
-Design Framework: Bootstrap (latest version)
-Routing: React Router for navigation between pages (Login, Registration, Profile)
-Local Storage: Used for persisting registration details and profile updates

User Flow
 Registration:
    User fills out the registration form.
    Information is saved in local storage.
    Success message is shown.
    User is redirected to the login page.
    
 Login:
    User enters email and password.
    Application checks credentials against local storage.
    If correct, user is redirected to the profile page.
    If incorrect, an error message is displayed.
 
 Profile Management:
    User views current profile details.
    User can edit and update their profile information.
    Updated information is saved in local storage.
