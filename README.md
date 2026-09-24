# Name-function-


Here is a clear, professional README.md file designed specifically for your project. You can copy and paste this directly into your repository.
# Name Function Project

A simple web application that prompts the user for their first name and surname, then displays a personalized welcome message for **Business News Hub**.

## 🚀 Features

* **Interactive Prompt:** Collects user input using standard browser prompt dialogs.
* **Dynamic String Concatenation:** Combines first name and surname seamlessly.
* **Alert Welcome:** Generates a custom alert greeting the user to the Business News Hub platform.
* **Styled UI:** Includes a clean gold-themed HTML interface.

---

## 📂 Project Structure

```text
├── index.html       # Main HTML document containing CSS, structure, and JavaScript
└── README.md        # Project documentation

🛠️ How to Run
 * Clone or download this repository.
 * Open index.html in any modern web browser (Google Chrome, Firefox, Safari, Edge, etc.).
 * Click the "What is your name?" button.
 * Follow the on-screen prompts to enter your name and surname.
💻 JavaScript Functionality
The main function user() handles the input and greeting process:
function user() {
    let user1 = window.prompt("Enter your name : ");
    let user2 = window.prompt("Enter your surname : ");
    
    let user3 = user1 + " " + user2;
    
    window.alert("Hello " + user3 + " and Welcome to Business News Hub.");
}

💡 Code Improvements & Recommendations
If you plan to expand this script, consider these potential enhancements:
 * Empty Input Handling: Add validation to check if the user cancels or leaves the input blank.
 * Modern Template Literals: Use ES6 template strings for cleaner code formatting:
   const fullName = `${user1} ${user2}`;
window.alert(`Hello ${fullName} and Welcome to Business News Hub.`);

 * DOM Manipulation: Display the welcome message directly on the web page instead of using window.alert().

