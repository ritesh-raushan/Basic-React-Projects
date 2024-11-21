# React Password Generator

This project is a simple React application that generates random passwords based on user preferences. Users can adjust the password length, include numbers, and special characters, and copy the generated password to the clipboard.

## Technologies Used

- **React:** For building the UI and managing state.
- **Tailwind CSS:** For styling and layout design.

## How It Works

- The application uses the `useState` hook to manage the password, its length, and toggle options for numbers and special characters.
- The `useEffect` hook ensures that a new password is generated whenever the user updates the length or toggles options.
- The `useRef` hook is used to reference the password input field for clipboard copy functionality.
- Users can adjust the password length with a slider and enable or disable numbers and special characters using checkboxes.
- The generated password is displayed in a text field, and a "Copy" button allows quick copying to the clipboard.
