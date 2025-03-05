# User Stories for Login/Registration

## 1. Application Registration
**As** an unregistered user,  
**I want** to register by entering my username, email, and password and clicking the "Sign Up" button,  
**So that** I can create an account and access the application.  

### Acceptance Criteria:
- The app must display fields for username, email, and password.
- The "Sign Up" button must be enabled only when all fields are filled.
- After clicking "Sign Up," the system must validate the data and successfully create the account.
- User data must be saved in local storage.

---

## 2. Application Login
**As** a registered user,  
**I want** to log in by entering my email and password and clicking the "Login" button,  
**So that** I can access my account in the application.  

### Acceptance Criteria:
- The app must display fields for email and password on the login screen.
- The "Login" button must be enabled only when both fields are filled.
- After clicking "Login," the system must verify the credentials and grant access if they are correct.
- If credentials are saved locally, login should be facilitated in future sessions.

---

## 3. Error Feedback on Signup and Login
**As** a user attempting to sign up or log in,  
**I want** to receive clear error messages when something goes wrong,  
**So that** I can correct the issues and proceed with signup or login.  

### Acceptance Criteria:
- If the user clicks "Sign Up" without filling all fields, a message must appear: "Please fill in all fields."
- If the user clicks "Login" with an incorrect email or password, a message must appear: "Invalid email or password."
- Error messages must be displayed in the interface without crashing the app.

---

## 4. Store User Data
**As** an app user,  
**I want** my data to be saved locally,  
**So that** I don’t have to re-enter it every time I open the app.  

### Acceptance Criteria:
- After successful registration, user data (username, email, and password) must be saved in the device’s local storage.
- When reopening the app, saved data must be available to facilitate login.
- Data must persist between sessions until the user chooses to log out or clear the data.
