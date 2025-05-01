# 💊 UID_PROJECT_PHARMACETICAL_DATABASE

## 🧪 Pharmaceutical Company Database UI

This project implements a user interface for managing the data of a pharmaceutical company. It has features for secure login, registration, data viewing, and updates.

## 📑  Table of Contents

- [✨ Features](#features)
- [👥 User Roles](#user-roles)
- [🖥️ User Interface](#user-interface)
  - [🔐 Login Page](#login-page)
  - [📝 Company User - Register Page](#company-user---register-page)
  - [🔓 Company User - Login Page](#company-user---login-page)
  - [🏠 Post-Login Home Page](#post-login-home-page)
- [🧭 Navigation Bar](#navigation-bar)
- [🔍 Search Bar](#search-bar)
- [📱 Responsiveness & UX Enhancements](#responsiveness--ux-enhancements)
- [🛠️ Technologies](#technologies)
- [⚙️ Setup & Installation](#setup--installation)
- [🚀 Usage](#usage)
- [🤝 Contributing](#contributing)
- [📝 License](#license)

## ✨ Features

- Secure registration and login flows with client-side validation
- Interactive UI elements with CSS hover effects and JavaScript animations
- Dynamic data filtering via search
- Responsive design for all device sizes


## 👥 User Roles

| Role         | Access                                              |
|--------------|-----------------------------------------------------|
| Company User | Registration, login, view/update medicines, suppliers, dashboards |


## 🖥️ User Interface

### 🔐 Login Page

- *Company User Login* button on the homepage
- CSS hover effects:
  - Color change on hover
  - Cursor changes to pointer
  - Smooth transition animation
- Redirects to a page with *Register* and *Login* buttons

### 📝 Company User - Register Page

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

### 🔓 Company User - Login Page

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

### 🏠 Post-Login Home Page

#### 🖼️ 1. Page Layout & Design

- Background image or gradient for professional look
- Company logo at top-left with hover tooltip (mission, services, location)
  - Implemented via JS event listeners and CSS transitions

#### 🧭 2. Navigation Bar

- Sticky navbar at top
- Menu items:
  - Home
  - Medicine List
  - Dashboards
  - Tables
  - Update
  - Contact Details
- CSS hover effects on links
- Smooth page transitions via JavaScript or routing

## 🔍 Search Bar

- Positioned in header/top section
- Allows search by medicine name
- On search:
  - JavaScript filters list or fetches from database
  - Displays details: name, type, expiry date, availability, stock count
  - Shows “No Results Found” if empty
- Optional auto-suggestions
- Responsive design

## 📱 Responsiveness & UX Enhancements

- Layout via CSS flexbox and grid
- Media queries for mobile/tablet/desktop
- JS for dynamic content (search, tooltips, transitions)
- CSS for hover/active states, animations


## 🛠️ Technologies

### 🧩 Frontend
- React (with JSX)
- HTML5 & CSS3 (can use plain CSS, CSS Modules, or styled-components)
- JavaScript (ES6+)

### ⚙️ Backend 
- Node.js with Express

### 🗃️ Database 
- Postgre SQL

## Setup & Installation

1. Clone the repository
   bash
   git clone https://github.com/nikhilsai550000/UID_PROJECT_PHARMACEUTICAL_DATABASE.git
   
2. Open index.html in your browser or serve via local HTTP server
3. Customize configuration as needed

## Usage

- Navigate to homepage to register or login as company user
- Use navigation bar to access different sections
- Search medicines using the search bar

## Contributing

1. Fork the repository
2. Create a feature branch (git checkout -b feature-name)
3. Commit your changes (git commit -m "Add feature")
4. Push to branch (git push origin feature-name)
5. Open a Pull Request

## License

This project is licensed under the MIT License. Please take a look at the [LICENSE](LICENSE) file for details.
