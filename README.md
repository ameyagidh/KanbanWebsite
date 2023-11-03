# MERN Stack Kanban Website

Certainly, here's the updated GitHub README template with your provided repository link:

# Full-Stack Kanban App using MERN Stack

A full-stack Kanban application built with the MERN (MongoDB, Express.js, React, Node.js) stack. This app allows users to manage tasks and projects using the Kanban board methodology.




## Features

- **Kanban Boards:** Organize tasks into Kanban boards with columns like "To-Do," "In Progress," and "Done."

- **Task Management:** Create, edit, and delete tasks. Drag and drop tasks between columns.

- **Project Management:** Group tasks into projects and manage project details.

- **User Authentication:** User registration and login for secure access to boards and tasks.

## Technologies

- **Frontend:** React, Redux, React-Router, Material-UI, Axios.

- **Backend:** Node.js, Express.js, MongoDB (with Mongoose), Passport.js for authentication.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ameyagidh/KanbanApp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd KanbanApp
   ```

3. Install dependencies for both the client and server:

   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

4. Create a `.env` file in the server directory and set the following environment variables:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. Start the development server:

   ```bash
   cd ../client
   npm start
   cd ../server
   npm start
   ```

6. Access the application in your web browser at `http://localhost:3000`.

## Usage

- Register an account or log in to an existing one.
- Create a project and add tasks to it.
- Manage your tasks by dragging and dropping them between columns.
- Collaborate with others on the same project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- This project was inspired by the Kanban methodology and the need for a flexible and customizable Kanban app.
- Thanks to the open-source community for the tools and libraries used in this project.

