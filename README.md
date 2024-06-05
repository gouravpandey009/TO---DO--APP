# 📝 Simple React To-Do Application

Welcome to the **Simple React To-Do Application** project! This project is designed to test your understanding of foundational web technologies (HTML, CSS, JavaScript) and essential React concepts.

## 🌐 Live Demo

Check out the live demo of the application here: [Live To-Do App](https://to-do-app-czlp.vercel.app/)


## 🚀 Objective

Develop a basic To-Do application using ReactJS that allows users to add, view, and delete tasks. This application should showcase your understanding of:
- HTML for structuring the application's layout.
- CSS for styling the application.
- JavaScript (ES6 or later) for implementing the application logic.
- React components, hooks, and state management using Redux.

## 📋 Requirements

### Frontend Development:
- Use **HTML** to structure the application's layout.
- Use **CSS** for styling the application. Feel free to use CSS frameworks like Bootstrap or Material-UI for design components.
- Implement the application logic using **JavaScript**.

### React Components:
- Develop the application using functional components and demonstrate the use of React hooks (`useState`, `useEffect`).
- The application should have at least two components:
  - **TaskInput**: A component for adding a new task.
  - **TaskList**: A component for displaying the list of tasks.

### State Management:
- Use **Redux** to manage the application's state. This includes storing the tasks and updating the state when adding or removing tasks.
- Implement actions and reducers to handle the state logic.

### Functionality:
- **Add Task**: Users should be able to input a task into a text field and add it to the list by pressing a button or pressing Enter.
- **View Tasks**: Display all added tasks in a list format.
- **Delete Task**: Each task should have a delete button that, when clicked, removes the task from the list.
- **Edit Task**: Each task should have an edit button that, when clicked, a popup opens to edit the task.

### Bonus (Optional):
- Add the capability to mark tasks as completed without deleting them. This could involve toggling the task's state and styling.
- Implement persistent storage (e.g., saving tasks to local storage) so that tasks are not lost on page reload.

## 📦 Submission Guidelines:
1. Your project should be submitted as a link to a GitHub repository with clear README instructions on how to set up and run the application.
2. Ensure your code is well-commented to describe your logic and approach.
3. Submit your project via this form: [Google Form Submission](https://docs.google.com/forms/d/e/1FAIpQLSeQ-9PffLbFkzTFfNNv6SqmlyKhV8OT5TJVkPiHBOq9G1-YTQ/viewform)

## ✅ Evaluation Criteria:
- **Functionality**: The application works as described without errors.
- **Code Quality**: The code is clean, well-organized, and properly commented.
- **Use of React Concepts**: Demonstrates a good understanding of React components, hooks, and state management.
- **Creativity and Design**: While functionality is key, creative use of CSS for a pleasant UI will be appreciated.

You will be provided with a maximum of 24 hours to complete this task after which your application will automatically be canceled.

Good luck, and happy coding! 🎉

---

## 🛠️ Setup Instructions

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/todo-app.git
   cd todo-app
   ```

2. **Install dependencies**:
   ```sh
   npm install
   ```

3. **Start the development server**:
   ```sh
   npm run dev
   ```

4. **Build the application**:
   ```sh
   npm run build
   ```

5. **Preview the build**:
   ```sh
   npm run preview
   ```

---

## 📂 Project Structure

```
.
├── public
│   └── index.html
├── src
│   ├── components
│   │   ├── TaskInput.js
│   │   ├── TaskList.js
│   │   └── TaskCard.js
│   ├── redux
│   │   ├── store.js
│   │   └── taskSlice.js
│   ├── App.js
│   ├── index.js
│   └── styles.css
├── .gitignore
├── package.json
└── README.md
```

---

Feel free to enhance the design and functionality as you see fit. Your creativity and attention to detail will be taken into consideration during the evaluation. Good luck! 🍀
