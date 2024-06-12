# Event Management System

## Introduction

Event Management System is a comprehensive web application that allows users to manage events efficiently. This full-stack project is built using React for the frontend and Node.js for the backend. It incorporates user authentication to ensure secure access and features a range of functionalities for event creation, viewing, editing, and deletion.

## Features

- **User Authentication**: Secure login and signup processes, token-based session management.
- **Event Management**: Create, view, edit, and delete events with a user-friendly interface.
- **Navigation**: Intuitive navigation for easy access to different sections of the application.
- **Error Handling**: Robust error handling to provide meaningful feedback to users.

## Technologies Used

- **Frontend**: React, React Router, CSS
- **Backend**: Node.js, Express
- **Other Tools**: Fetch API for HTTP requests, Local Storage for session management

## Usage

### Authentication

- **Login**: Users can log in to access their accounts and manage events.
- **Signup**: New users can create an account.
- **Logout**: Logged-in users can log out of their account.

### Event Management

- **Create Event**: Users can create new events.
- **View Events**: Users can view a list of all events.
- **Edit Event**: Users can edit their existing events.
- **Delete Event**: Users can delete their events.

### Error Handling

- **Error Pages**: Displays appropriate error messages for different error statuses.

## Code Overview

### Authentication.js

Handles user authentication actions such as login, signup, and token management.

### EventForm.js

Provides a form for creating and editing events.

### EventItem.js

Displays individual event details and provides options for editing and deleting events.

### Events.js

Displays a list of events, handling loading states and errors.

### MainNavigation.js

Provides navigation links to different sections of the application, including home, events, and newsletter.

### Error.js

Handles error display based on the error status and message.
