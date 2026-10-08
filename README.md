#  Password Generator

A simple and user-friendly **Password Generator** built using **React.js**.  
It allows users to generate random passwords based on their preferred length and whether they want to include numbers and symbols.

## Features

- Generate random passwords
- Adjust password length from **6 to 25 characters**
- Include numbers in the password
- Include symbols in the password
- Copy the generated password to the clipboard
- Automatically generate a new password when options are changed

## 📌 How It Works

The application uses React's `useState` hook to manage:

- Password length
- Generated password
- Numbers option
- Symbols option
- Copy status

The `useEffect` hook automatically generates a new password whenever the password length, numbers, or symbols options are changed.

## 👩‍💻 Author

**Shivi Mishra**

Built as a beginner React project to practice **React Hooks, state management, event handling, and the Clipboard API**.
