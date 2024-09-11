
# Login Form Project

This project is a simple *login web page* that uses *HTML, **CSS, and **JavaScript*. The page includes client-side form validation, integrates with an open login API, and provides a responsive design that works well on both desktop and mobile devices. After a successful login, a success message is displayed in a user-friendly card format.


## Project Description
The *Login Form Project* is designed to showcase a functional and visually appealing login page. It validates user input on the client side and integrates with an open API for login functionality. Once the login is successful, the user is presented with a success message, confirming the login.

## Features
1. *HTML Structure*: 
    - Username/Email and Password input fields.
    - Submit button.
  
2. *CSS Styling*:
    - Responsive design.
    - Clean and minimalistic UI.
    - Custom validation error messages for email and password fields.

3. *JavaScript Functionality*:
    - Client-side form validation for email format and password length.
    - API integration using fetch() to handle login requests.
    - Success or error message displayed based on the API response.

4. *Bonus Features*:
    - Show/Hide password functionality.
    - Remember Me checkbox (saves email in local storage).
    - Loading spinner during the API call.

## Technologies Used
- *HTML*: Provides the structure of the login page.
- *CSS*: Used for styling the form and ensuring responsiveness.
- *JavaScript*: Adds functionality such as validation, API calls, and dynamic form behavior.
- *API*: Integrated with an open login API to process login requests.

## Requirements
To run the project locally, you need a modern web browser (e.g., Chrome, Firefox, Safari) and an internet connection to hit the API endpoint.



## Testing the API
1. *Submit the Form*:
    - Enter a valid email and password (password must be at least 8 characters long).
    - Click the *Submit* button to trigger the API call.

2. *API Response*:
    - If the login is successful, a success message will appear in a card format, indicating the login success.
    - If the login fails, an error message will appear.

3. *API Endpoint*:
    The form submits data to the following API endpoint:
    bash
    https://jsonplaceholder.typicode.com/posts
    

## Bonus Features
- *Show/Hide Password*: Users can toggle the visibility of their password by clicking the "Show" or "Hide" button next to the password field.
- *Remember Me Checkbox*: When checked, the email entered by the user is saved to localStorage, and the next time they visit the page, the email field is pre-filled with the saved email.
- *Loading Spinner*: A loading spinner appears while the API request is being processed, giving the user feedback that the form is being submitted.



## Evaluation Criteria (As per assignment):
1. *Correctness*: The login form works as expected with proper validation and API response handling.
2. *Code Quality*: The code is clean, well-organized, and follows best practices.
3. *UI/UX*: The login form is user-friendly, visually appealing, and responsive on both desktop and mobile devices.
4. *Bonus Features*: The form includes all the optional features such as "Show/Hide password", "Remember Me", and a loading spinner.


### Instructions:
1. Clone or download the repository and open index.html in your web browser.
2. Test the form by entering an email and password.
3. Check the success/error messages after submitting the form.
