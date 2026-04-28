# EduTrack

A comprehensive education management platform designed for teachers and school administrators. It provides a mobile-first, real-time dashboard to manage all aspects of classroom and student life in one place.

## Features

- **Dashboard**: Live metrics with interactive charts
- **Students**: Manage student profiles, groups/sections, and parent contacts
- **Attendance**: Mark daily attendance (present/absent/late/excused) with optimistic UI
- **Homework**: Assign, track, and grade homework submissions
- **Assessments**: Create quizzes, tests, and exams; track scores by subject
- **Daily Progress**: Log per-student behavior, participation, and effort ratings
- **Student Goals**: Set and track academic, behavioral, and personal goals
- **Progress Reports**: Generate and send term reports to parents
- **Communication**: Real-time group chat by class section with side input panel
- **Announcements**: Post pinned or priority announcements
- **Calendar**: Visual monthly calendar aggregating deadlines
- **Notifications**: Targeted alerts with type breakdown
- **Parents**: Link parent accounts to students
- **Authentication**: User registration and login system
- **Admin Panel**: Administrative controls for user management and system oversight

## Tech Stack

- HTML5
- CSS3 (Bootstrap 5 + Custom Styles)
- JavaScript (ES6+ with localStorage for data persistence)
- Node.js (for serving static files)

## Getting Started

1. Install Node.js from https://nodejs.org/
2. Run `node server.js` to start the server
3. Open http://localhost:3000 in your browser

## User Roles

- **Student**: Access personal dashboard, view assignments, track progress
- **Teacher**: Manage classes, assignments, attendance, and student progress
- **Parent**: View child's progress, communicate with teachers
- **Admin**: System administration, user management, platform oversight

## Project Structure

- `index.html`: Home page
- `login.html`: User login
- `register.html`: User registration
- `admin.html`: Admin panel
- `dashboard.html`: Main dashboard with metrics
- `students.html`: Student management
- `attendance.html`: Attendance tracking
- `homework.html`: Homework assignments
- `assessments.html`: Assessment creation
- `daily-progress.html`: Daily progress logging
- `student-goals.html`: Goal setting
- `progress-reports.html`: Report generation
- `communication.html`: Group chat with side input
- `announcements.html`: Announcements
- `calendar.html`: Calendar view
- `notifications.html`: Notifications
- `parents.html`: Parent management
- `styles.css`: Custom styling
- `server.js`: Simple Node.js server

## Features Overview

- **Responsive Design**: Mobile-first approach with Bootstrap
- **Dark Mode**: Toggle between light and dark themes
- **Interactive Chat**: Side-panel input for messaging
- **Mock Authentication**: localStorage-based user system
- **Admin Controls**: User management and system statistics
- **Professional UI**: Gradient backgrounds, animations, and modern styling

This is a complete static HTML implementation demonstrating a full education management system with user authentication and administrative features.