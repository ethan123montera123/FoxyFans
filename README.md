# FoxyFans Dashboard

This is the admin dashboard for the FoxyFans platform, built using HTML, TailwindCSS, and Firebase. The dashboard allows the admin to manage applicants, view application status, and handle user authentication.

## Features

- **Authentication**: Users are required to sign in to access the dashboard.
- **Applicants Management**: View and manage applicants in real-time.
- **Status Management**: View and update the status of each applicant (Processing, For Interview, Accepted).
- **User Logout**: Users can log out of the dashboard.

## Prerequisites

Before running this project, ensure that you have the following:

- A browser that supports modern web standards (e.g., Google Chrome, Firefox).
- Firebase account with a configured Firebase Realtime Database and Firebase Authentication.
- TailwindCSS installed via CDN.

## Folder Structure

The project consists of several HTML files and scripts.

### `index.html`
This is the login page for the application. The user is required to log in before accessing the dashboard.

### `dashboard.html`
The homepage for the admin dashboard where general information and management options are displayed.

### `applicants.html`
A page where the admin can view and manage the list of applicants.

### `status.html`
A page for managing the application status of each applicant.

### `firebase.js`
A JavaScript module for initializing Firebase and handling Firebase operations like authentication and database access.

## Installation

To get started with the project:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-repo/foxyfans-dashboard.git
   cd foxyfans-dashboard
    ```
2. Open the `bash index.html` file in your browser.

3. Update the Firebase configuration in the `<script type="module">` section in the HTML files. Replace the Firebase API key, authDomain, and other configurations with your own.