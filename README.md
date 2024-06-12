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

## Getting Started

### Prerequisites

Ensure you have the following installed on your local machine:
- Node.js
- npm (Node package manager)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/dasha12345-s/Authentication.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Authentication
    ```

3. Install the dependencies for the backend and frontend:
    ```bash
    cd backend
    npm install
    cd ../frontend
    npm install
    ```

### Running the Project

1. Start the backend server:
    ```bash
    cd backend
    npm start
    ```

2. Start the frontend development server:
    ```bash
    cd frontend
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` to see the application in action.

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

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspiration
- References

---

For more details, visit the [repository](https://github.com/dasha12345-s/Authentication).

---

Feel free to modify this README to better fit the specific details and requirements of your project.
