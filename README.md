# PG Life 🏠 – Full Stack Web Application

**PG Life** is a full-stack web application built as part of my **Internshala Full Stack Web Development Internship Training**. While I received initial guidance, the entire project is developed with my own understanding, customizations, and features from a user-centric perspective.

🌐 **Live Demo**: [PG Life Web App](Give link here)

📱 The application is fully responsive and functions seamlessly across devices.

---

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, Bootstrap 5, JavaScript, AJAX  
- **Backend**: PHP  
- **Database**: MySQL

---

## ✨ Key Features

### 🔍 Home Page
- Search bar to find PGs by city name (case-insensitive).
- Quick-access circular icons for major cities that list relevant PGs.

### 🏘 PG Listings Page
- Displays PGs in selected cities using responsive cards.
- **Filters**: Sort PGs by rent or rating (ascending/descending).
- Shows popularity (number of users who marked PG as "interested").
- Logged-in users can mark/unmark PGs as interested using a heart icon with dynamic toggling.
- Interest count updates live without refreshing.

### 📋 PG Details Page
- Accessed via the “View” button on listing cards.
- Image carousel of the PG at the top.
- Detailed information: amenities, testimonials, and address.
- Logged-in users can interact with the interest feature here as well.

### 👤 Dashboard
- Available only to **logged-in users**.
- Shows account/profile information.
- Displays a personalized list of "interested" PGs.
- Users can remove PGs from their list dynamically by un-clicking the heart icon.

### 📌 Navbar
- Brand name always visible.
- If not logged in: shows **Signup** and **Login** options.
- If logged in: shows **Dashboard**, **Logout**, and user's first name (via `SESSION`).
- Fully responsive toggle-enabled navbar.

### 🧭 Breadcrumbs
- Displays user's current location in the web app.
- Includes clickable links for easy navigation.

### 🦶 Footer
- Quick links to popular city PG listings.
- Copyright.

---

## 🔐 User Access & Experience

- All pages can be browsed **without logging in**.
- However, features like Dashboard and Interest marking require authentication.
- Custom error handling with user-friendly messages and UI feedback is implemented throughout the app.
