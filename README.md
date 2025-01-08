# Online Group Study Web Application

Welcome to the Online Group Study web application project. This application allows users to create, submit, and grade assignments collaboratively. It is designed to foster a group study environment where all registered users are connected as friends. Project Name: AssignMate

## Purpose

The purpose of this project is to demonstrate the ability to develop a full-stack MERN application with modern web development practices, including secure authentication, responsive design, and a user-friendly interface.

## Live URL

[AssignMate: ](https://assign-mate-f36ad.web.app/)

## Key Features

### General Features

- **Responsive Design:** Fully responsive across mobile, tablet, and desktop devices.
- **Dynamic Theming:** Users can toggle between light and dark themes.
- **User-Friendly Design:** A pleasing and accessible UI/UX with proper alignment and spacing.

### Authentication System

- Email/password-based authentication.
- Social login option (Google or GitHub).
- Secure storage of Firebase configuration keys using environment variables.
- Password validation with error messages for incomplete requirements.
- JWT authentication for secure access to private routes.

### Assignment Features

- Create assignments with a title, description, marks, thumbnail, difficulty level, and due date.
- View, update, and delete assignments.
- Submit assignments with Google Docs links and notes.
- Grade and provide feedback for assignments submitted by others.
- Filter and search assignments by difficulty level.

### Pages

- **Home Page:** Public page with a banner, features section, and FAQ.
- **Assignments Page:** Displays all assignments with filter and search functionalities.
- **Create Assignment Page:** Private page for creating assignments.
- **Submitted Assignments Page:** View assignments submitted by the logged-in user.
- **Pending Assignments Page:** Displays ungraded assignments submitted by all users.

## Deployment Guidelines

- Client-side hosted on Firebase.
- Server-side hosted on Vercel.
- Error-free deployment ensuring proper handling of CORS and routing.
- Authorization configured for Firebase hosting.

## Technologies Used

### Frontend

- **React.js**: Frontend library for building the UI.
- **React Router**: For managing routes.
- **React Datepicker**: For date selection in assignment creation.
- **Tailwind CSS**: For styling and responsiveness.
- **SweetAlert/Toast**: For notifications.

### Backend

- **Node.js**: Backend runtime environment.
- **Express.js**: Web framework for the server.
- **MongoDB**: Database for storing data.
- **JWT**: For secure authentication.
- **Dotenv**: For managing environment variables.

## NPM Packages

- `react-datepicker`
- `jsonwebtoken`
- `bcrypt`
- `cors`
- `dotenv`
- `mongoose`
- `tailwindcss`

## Folder Structure

```
project-root/
├── client/
│   ├── src/
│   ├── public/
│   ├── .env
│   ├── package.json
│   └── README.md
└── server/
    ├── routes/
    ├── controllers/
    ├── models/
    ├── config/
    ├── .env
    ├── package.json
    └── server.js
```

## Commit Guidelines

### Client-Side

- Minimum of 15 meaningful commits with descriptive messages.
- Example: `feat: added theme toggle button for light/dark mode`

### Server-Side

- Minimum of 8 meaningful commits with descriptive messages.
- Example: `fix: resolved CORS issue during assignment creation`

## Optional Features

- Spinner for loading states.
- Framer Motion animations.
- Pagination on the Assignments page.
- Integration of Tanstack query mutations.

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone [repo-link]
   ```
2. Navigate to client and server directories and install dependencies:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```
3. Add `.env` files for both client and server with required configurations.
4. Start the server:
   ```bash
   npm start
   ```
5. Start the client:
   ```bash
   npm start
   ```
6. Visit the application at `https://assign-mate-f36ad.web.app/`.

## Author

Developed by ASM Shad
