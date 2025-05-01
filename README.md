# UID_PROJECT_PHARMACETICAL_DATABASE

## Pharmaceutical Company Database UI

This project implements a user interface for managing the data of a pharmaceutical company. It provides role-based access for company users and general users, with features for secure login, registration, data viewing, and updates.

## Table of Contents

- [Features](#features)
- [User Roles](#user-roles)
- [User Interface](#user-interface)
  - [Login Page](#login-page)
  - [Company User - Register Page](#company-user---register-page)
  - [Company User - Login Page](#company-user---login-page)
  - [Post-Login Home Page](#post-login-home-page)
- [Navigation Bar](#navigation-bar)
- [Search Bar](#search-bar)
- [Responsiveness & UX Enhancements](#responsiveness--ux-enhancements)
- [Technologies](#technologies)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Role-based access control for company and general users
- Secure registration and login flows with client-side validation
- Interactive UI elements with CSS hover effects and JavaScript animations
- Dynamic data filtering via search
- Responsive design for all device sizes


## User Roles

| Role         | Access                                              |
|--------------|-----------------------------------------------------|
| Company User | Registration, login, view/update medicines, suppliers, dashboards |
| General User | View-only access to public sections                 |

## User Interface

### Login Page

- *Company User Login* button on the homepage
- CSS hover effects:
  - Color change on hover
  - Cursor changes to pointer
  - Smooth transition animation
- Redirects to a page with *Register* and *Login* buttons

### Company User - Register Page

- *Registration Form* fields:
  - Employee ID (text input)
  - Password (password input)
  - Retype Password (password input)
  - Register (submit button)
- *JavaScript validation*:
  - All fields required
  - Password and retype must match
  - Visual feedback for errors (red borders, alert messages)
- *CSS styling*:
  - Button hover effects
  - Styled error messages
  - Input focus outlines for accessibility

### Company User - Login Page

- *Login Form* fields:
  - Employee ID
  - Password
  - Reset Password link/button
- *JavaScript functionality*:
  - Non-empty input validation
  - Error messages on invalid login
  - Password recovery modal or section
- *CSS styling*:
  - Consistent layout with register page
  - Responsive design with flexbox/grid
  - Animated show/hide transitions
