# Form Validation

An interactive client-side form validation application built with vanilla HTML5, CSS3, and JavaScript.

## 🚀 Features

- **Real-Time & Submission Validation:** Checks user inputs when the form is submitted.
- **Fields Validated:**
  - **Full Name:** Required, minimum 5 characters.
  - **Email:** Required, validated with standard email regex pattern.
  - **Phone Number:** Required, minimum 10 digits, dummy sequence validation.
  - **Password:** Required, minimum 8 characters, checks against weak common passwords and username matches.
  - **Confirm Password:** Required, validates that it matches the entered password.
- **Visual Feedback:** Dynamic success (green) and error (red) indicator states with descriptive feedback messages.
- **Clean UI:** Responsive card layout with modern typography.

## 📁 Project Structure

```
├── index.html       # Form markup and structure
├── style.css        # Layout, styling, and validation status indicators
└── script.js        # Form validation logic and helper functions
```

## 🛠️ Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Andru6/form-validation.git
   ```
2. Open `index.html` in your web browser, or use a local static server like Live Server.
