# TECHIN 510 Lab 5: Frontend Development

## Author: Yifan Wang

## Hosted Link

[AI Fitness Coach](https://techin510-lab5-ai-fitness-coach.streamlit.app/)

[To-do App](https://yifanwang16.github.io/TECHIN510-LAB5/todo%20app/index.html)

## Overview

This lab focuses on creating an AI-powered fitness coach using Streamlit, a Python web application framework, and the Google Gemini API. The app allows users to input their personal information, fitness goals, and available equipment, and generates a personalized workout plan based on the provided details.

## Features

- User Input: The app collects user information such as gender, age, weight, height, fitness experience, goals, workout days, workout minutes, and available equipment through interactive input fields.

- Equipment Selection: Users can select from a comprehensive list of 20 different equipment options, including dumbbells, barbells, resistance bands, and various machines. If no equipment is selected, the app assumes the user has no access to equipment.

- Personalized Workout Plan: Upon submitting the user's information, the app sends a request to the Google Gemini API, which generates a personalized workout plan based on the provided details. The plan includes the user's information, the number of workout days and minutes, the available equipment (if any), and a detailed workout routine.

- Loading Indication: While waiting for the API response, the app displays a spinning animation and a message to indicate that the workout plan is being generated. Once the response is received, a success message is shown, followed by the generated workout plan.

- Error Handling: The app gracefully handles errors related to API requests and displays appropriate error messages to the user.

## Reflections

Developing the AI Fitness Coach app provided valuable insights into integrating Streamlit with the Google Gemini API for generating personalized workout plans. The project showcased the importance of user-friendly interfaces, allowing users to input their personal information and fitness goals seamlessly. Implementing a comprehensive equipment selection feature, with the ability to handle cases where no equipment is available, demonstrated the significance of adaptability in fitness applications. Integrating with the Gemini API highlighted the power of AI in generating customized workout plans based on user-specific data. Adding loading indications and error handling enhanced the user experience by providing visual feedback and graceful error management. Throughout the development process, I gained a deeper understanding of API integration, data formatting, and creating interactive web applications using Streamlit. This project emphasized the potential of AI in the fitness domain and the importance of user-centric design in developing engaging and personalized fitness solutions.

## Bonus: Todo App

In addition to the AI Fitness Coach app, I have also developed a simple Todo app using HTML, CSS, and JavaScript. This app allows users to manage their tasks efficiently by providing the following features:

### Features

- **Task Addition**: Users can easily add new tasks to their todo list by entering the task description in the input field and clicking the "Add" button. The app instantly updates the list to include the newly added task.

- **Task Deletion**: Each task in the list is accompanied by a delete button (❌) that allows users to remove the task from the list with a single click. This feature enables users to keep their todo list clean and up to date.

- **Firebase Integration**: The app is integrated with Firebase Firestore, a cloud-based NoSQL database. This integration enables real-time synchronization of the todo list across multiple devices and ensures data persistence. Any changes made to the todo list, such as adding or deleting tasks, are instantly reflected in the Firebase database.

- **GitHub Pages Deployment**: The Todo app is deployed using GitHub Pages, making it accessible via a web browser. The app's source code is hosted in a separate folder within the repository, and GitHub Pages is configured to serve the app from that specific folder.

### Technologies Used

- **HTML**: The structure and layout of the Todo app are built using HTML, providing a clean and intuitive user interface.

- **CSS**: Custom CSS styles are applied to enhance the visual appearance of the app, making it visually appealing and user-friendly.

- **JavaScript**: The app's functionality, such as adding and deleting tasks, is implemented using JavaScript. It also handles the integration with Firebase Firestore for data storage and retrieval.

- **Firebase Firestore**: The app utilizes Firebase Firestore, a NoSQL document database, to store and sync the todo list data in real-time. Firestore provides a scalable and efficient solution for data persistence and synchronization.

### Deployment

The Todo app is deployed using GitHub Pages and can be accessed via the following URL:

The source code for the Todo app is located in the `todo` folder within the repository.
