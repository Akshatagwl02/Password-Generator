# Password-Generator
A simple yet robust password generator built with React and styled using Tailwind CSS. This application provides users with the ability to create secure, customizable passwords with options for length, inclusion of numbers, and special characters.

## Features

- **Customizable Password Length**: Easily adjust the password length using an intuitive range input.
- **Include Numbers**: Toggle the inclusion of numerical digits in your generated password.
- **Include Special Characters**: Add special symbols to enhance password strength.
- **Instant Copy**: A dedicated button to quickly copy the generated password to your clipboard.
- **Targeted Text Selection**: The copy function intelligently selects and copies only the password string, highlighting the text for user feedback.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.

## Hooks Used

- `useState`: Manages the dynamic state of the password, length, and character options.
- `useEffect`: Handles side effects such as re-generating the password when options change.
- `useCallback`: Optimizes performance by memoizing functions, preventing unnecessary re-renders.
- `useRef`: Directly accesses the DOM for features like copying the password and highlighting the selected text.
