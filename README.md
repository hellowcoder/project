# Login System

This project implements a basic login system using C++ that allows users to register, log in, and retrieve their password if they forget it. User data is stored in a text file, and the system checks credentials based on that data.

## Features

- **Sign-Up**: Allows new users to create an account with a username, email, and password.
- **Login**: Allows users to log in by verifying their username and password.
- **Forgot Password**: Users can retrieve their password by providing their username and email address.
- **Data Storage**: User data is stored in a simple text file `loginData.txt` where each entry contains the username, email, and password.

## Prerequisites

To run this project, you’ll need:
- A C++ compiler (e.g., GCC, MinGW, or an IDE like Code::Blocks or Visual Studio).
- A basic understanding of file I/O in C++.

## Setup Instructions

### 1. Clone or Download the Repository

If you are using Git:

```bash
git clone https://github.com/yourusername/login-system.git
cd login-system
