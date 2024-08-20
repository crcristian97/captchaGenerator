CAPTCHA Verification Project

This project is a simple CAPTCHA verification system implemented in JavaScript. It generates a random CAPTCHA string that users need to input correctly to proceed. The CAPTCHA string is a mix of uppercase and lowercase letters, and the user is required to enter it exactly as displayed.

Features
-Random CAPTCHA Generation: Generates a random CAPTCHA string every time the page loads or when the refresh button is clicked.
-User Input Validation: Compares the user's input with the generated CAPTCHA to verify if it matches.
-Real-Time Input Monitoring: Enables or disables the submit button based on the input field's content.
-Responsive Messages: Displays feedback messages indicating whether the CAPTCHA was entered correctly or not.

Technologies Used
-HTML: Structure of the CAPTCHA form and buttons.
-CSS: Basic styling of the form elements and messages.
-JavaScript: Core logic for generating, displaying, and validating the CAPTCHA.

How It Works
-CAPTCHA Generation: On page load, a random string of 5 characters is generated. This string is then randomly converted to a mix of uppercase and lowercase letters, with spaces added between each character for added difficulty.

-Refresh Button: Clicking the refresh button generates a new CAPTCHA string and clears the user's input.

-Real-Time Validation: As the user types in the CAPTCHA input box, the submit button is enabled or disabled based on whether the input box is empty.

-Submission: When the user clicks the submit button, their input is compared to the generated CAPTCHA (ignoring spaces). A message is then displayed indicating if the CAPTCHA was entered correctly.
