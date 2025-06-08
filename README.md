# Feedback Management System

A C++ console application for collecting and analyzing user feedback with separate interfaces for users and administrators.

## 📋 Overview

This feedback system allows users to submit bug reports, feature requests, and general feedback while giving administrators tools to analyze and prioritize this information.

## ✨ Key Features

- **User Dashboard**: Submit, edit, and delete feedback
- **Admin Analytics**: View and filter feedback by type
- **Automatic Prioritization**: Feedback is ranked based on frequency
- **Data Persistence**: All data is saved between sessions
- **Clean UI**: Color-coded console interface

## 🔧 Installation

```bash
# Clone repository
git clone https://github.com/Ahmed465-hub/feedback-system.git

# Compile
g++ main.cpp -o feedback_system

# Run on Windows
feedback_system.exe

```

## 📘 Quick Guide

### For Users
- Register/login with username and password
- Submit up to 10 feedback entries
- Edit or delete your submitted feedback

### For Admins
- Login with admin passkey: `admin`
- View statistics on most common feedback types
- Filter feedback by category

## 💻 Technical Details

- Built using C++ with standard libraries
- Uses custom data structures for user and feedback management
- Implements file I/O for data persistence
- Features dynamic feedback prioritization algorithm

## 📝 Future Plans

- Graphical user interface
- Data encryption for passwords
- Export functionality for reports
- using dynamic array
## 👤 Author

- Ahmed nader - [GitHub](https://github.com/Ahmed465-hub)

## 📄 License

This project is licensed under the MIT License

---

*Developed as an educational project for feedback systems implementation*
