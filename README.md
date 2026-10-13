# SkillSwap - Skill Exchange Platform for Students

A web application where college students can exchange skills with each other.
For example: "I can teach Guitar, and I want to learn Python" — find a match and start swapping!

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## Project Structure
```text
WP-SkillSwap/
├── index.html          # Home / Landing page
├── login.html          # Login page
├── register.html       # Registration page
├── browse.html         # Browse all skills
├── post-skill.html     # Post a new skill
├── profile.html        # User profile
├── my-swaps.html       # Manage swap requests
├── css/
│   └── style.css       # All styles
├── js/
│   └── app.js          # All JavaScript
├── php/
│   ├── config.php      # Database connection
│   ├── register.php    # Register API
│   ├── login.php       # Login API
│   ├── get-skills.php  # Get skills API
│   ├── post-skill.php  # Post skill API
│   ├── delete-skill.php# Delete skill API
│   ├── swap-request.php# Create swap request API
│   ├── get-swaps.php   # Get swaps API
│   └── update-swap.php # Update swap status API
├── db/
│   └── skillswap.sql   # Database schema + sample data
└── README.md           # This file
```

## How to Run

### Option 1: Frontend Only (localStorage demo)
1. Open `index.html` in your browser
2. All data is stored in browser's localStorage
3. No server needed!

### Option 2: Full Stack (PHP + MySQL)
1. Install XAMPP
2. Start Apache and MySQL from XAMPP Control Panel
3. Open phpMyAdmin (`http://localhost/phpmyadmin`)
4. Create database `skillswap_db` or import `db/skillswap.sql`
5. Copy the project folder to `C:\xampp\htdocs\SkillSwap`
6. Open `http://localhost/SkillSwap` in your browser

## Features
- User registration and login with secure password hashing (bcrypt)
- Post skills you can teach and want to learn
- Browse and search skills by keyword and category
- Send swap requests to other students
- Accept or decline incoming requests
- View your profile and manage your posted skills

## Test Login
- Register a new account or use the demo (localStorage version - just sign up through the form)
- For MySQL / Full Stack testing, sample users are preloaded:
  - **Email:** `aarav@dtu.edu` | **Password:** `password123`
  - **Email:** `priya@xaviers.edu` | **Password:** `password123`
  - **Email:** `rohan@bits.edu` | **Password:** `password123`
  - **Email:** `sneha@iitm.edu` | **Password:** `password123`

## Made By
College Web Programming Course Project - 2026
