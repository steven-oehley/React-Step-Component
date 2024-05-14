# React Stepper ⚛︎
This is a simple React-based stepper component that demonstrates basic state management and UI updates. The stepper consists of numbered steps with previous and next buttons to navigate through the steps dynamically.

## Installation
To use this React stepper component in your project, follow these steps:

Clone the repository:

```
git clone <repository-url>
```
Navigate to the project directory:
```
cd <project-directory>
```
Install dependencies:
```
npm install
```
Start the development server:
```
npm start
```

## Usage
Once the development server is running, you can access the React stepper component in your browser at http://localhost:3000 by default.

## Component Overview
The React stepper consists of the following elements:

- Numbered Steps: Displayed as 1, 2, 3 inside the .numbers container.
- Message Display: A paragraph (<p>) element with class .message to display step-related messages.
- Navigation Buttons:
-- Previous Button: Moves to the previous step when clicked.
-- Next Button: Moves to the next step when clicked.

## How It Works

- State Management: The stepper component uses React's state (useState) to manage the current step (step).
- UI Updates: The updateUIValues function is responsible for updating the UI based on the current step state:
- Updates the message text based on the current step.
- Adds/removes the active class to the numbered steps (step-1, step-2, step-3) to visually indicate the active step.
- Event Handling: Event listeners are attached to the previous and next buttons (btnPrevious, btnNext) to handle step navigation:
- Decrements the step when the previous button is clicked (if not at the first step).
- Increments the step when the next button is clicked (if not at the last step).
