# TECHIN 510 Lab 5: Frontend Development

## Author: Yifan Wang

## Hosted Link

[AI Fitness Coach](https://techin510-lab5-ai-fitness-coach.streamlit.app/)

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
