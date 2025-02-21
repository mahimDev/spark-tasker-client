# Task Management Application

## 📌 Short Description

The **Task Management Application** is a powerful and user-friendly tool designed to help users efficiently organize and manage their tasks. Users can add, edit, delete, and reorder tasks using a drag-and-drop interface. Tasks are categorized into **To-Do, In Progress, and Done**, ensuring seamless workflow management. The application supports real-time updates and provides a responsive, minimalistic UI.

## 🌐 Live Link

[Task Management App](https://task-management-applicat-b67ac.web.app/)

## 📦 Dependencies

The project uses the following dependencies:

```json
"dependencies": {
    "@hello-pangea/dnd": "^18.0.1",
    "@tanstack/react-query": "^5.14.2",
    "aos": "^2.3.4",
    "axios": "^1.6.2",
    "firebase": "^10.7.1",
    "localforage": "^1.10.0",
    "match-sorter": "^6.3.1",
    "moment": "^2.29.4",
    "react": "^18.2.0",
    "react-beautiful-dnd": "^13.1.1",
    "react-dom": "^18.2.0",
    "react-hook-form": "^7.49.2",
    "react-hot-toast": "^2.4.1",
    "react-icons": "^4.12.0",
    "react-router-dom": "^6.21.0",
    "sort-by": "^1.2.0",
    "sweetalert2": "^11.10.1"
}
```

## 🛠 Installation Steps

Follow these steps to set up the project locally:

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/task-management-app.git
   ```

2. **Navigate to the project directory:**

   ```sh
   cd task-management-app
   ```

3. **Install dependencies:**

   ```sh
   npm install
   ```

4. **Set up Firebase:**

   - Create a Firebase project.
   - Enable Google Authentication.
   - Get your Firebase config and add it to `firebase.js`.

5. **Start the development server:**
   ```sh
   npm run dev
   ```

## 🚀 Technologies Used

The application is built using the following technologies:

- **Frontend:** React, Tailwind CSS
- **State Management:** React Query
- **Drag & Drop:** react-beautiful-dnd
- **Authentication:** Firebase Authentication
- **Backend:** Express.js, MongoDB (via MongoDB Atlas)
- **Notifications & Alerts:** SweetAlert2, React Hot Toast
