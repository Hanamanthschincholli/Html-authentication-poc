# User Authentication UI (HTML + Bootstrap 5)

This project is a simple **User Authentication Interface** built using **HTML, CSS, and Bootstrap 5**.  
It contains multiple pages that simulate a basic login system with navigation between pages.

## Technologies Used
- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons

---

# Project Pages

## 1. Login Page
The login page allows existing users to access the system.

### Features
- Email input field
- Password input field
- Show/Hide password using Bootstrap icons
- Login button
- Link to **Register Page**
- Link to **Forgot Password Page**

### Navigation
- Login → Dashboard
- Forgot Password → Forgot Password Page
- Create Account → Register Page

---

## 2. Register Page
The register page allows new users to create an account.

### Features
- Name input
- Email input
- Phone number input
- Password field
- Confirm password field
- Show/Hide password option
- Register button
- Link to Login page

### Navigation
- Register → Login Page

---

## 3. Forgot Password Page
This page allows users to request a password reset.

### Features
- Email input field
- Send reset password link button

### Navigation
- Submit → Login Page

---

## 4. Reset Password Page
This page allows users to create a new password.

### Features
- New password input
- Confirm password input
- Update password button

### Navigation
- Update Password → Login Page

---

## 5. Dashboard Page
The dashboard page is displayed after successful login.

### Features
- Welcome message
- Logout button

### Navigation
- Logout → Login Page

---

# Project Navigation Flow
Login Page
↓
Dashboard Page
↓
Logout → Login Page

Login Page → Register Page
Register Page → Login Page

Login Page → Forgot Password Page
Forgot Password Page → Login Page

Reset Password Page → Login Page


# project-folder
project-folder
│
├── Index(login-form).html
├── register-form.html
├── forgot-form.html
├── reset-form.html
├── dashboard.html
├── style.css
└── README.md

# How to Run:

1. Open the project folder
2. Open Index(login-form).html in any web browser
3. Navigate between pages using buttons and links

# Author
Name: Hanamanthschincholli 
Email: hanamanthschincholli@gmail.com