# A Formik Form

## Description 
[Formik](https://formik.org/) is the world's most popular open source form library for React and React Native. It is a small library that can help with the three most annoying aspects of creating forms in React:
- Getting values in and out of the form state
- Validation and error messages
- Handling form submission

## Purpose 
This was done as an assignment in the MIT course - Full Stack Development with Mern

---------

## Technologies Used 
- HTML
- Javascript

---------

## Installation 
- Clone this repository to your local machine
- Open a command line on your computer and run the command cd path-to-project-root (this should be the actual directory where the repository is located on your local machine)
- Within the same command-line window, run npm install to install all dependencies
- Once the command completes successfully, run npm start to start the application in your browser.

## How to Run 
- When the page is loaded in your browser, fill out the information and click Submit
- If a non-email entry is added under Username, you will see a red error under the username input field
- If the password entry is blank, you will see a red error under the password input field
- If you try to click the submit button without an email and password, nothing occurs
- If an email and password is entered and validates (see above) and the submit button is clicked, an alert telling you 'Login Successful!' is displayed

---------

## Files 
- **/public/index.html** - Start-up file to be opened by browse 
- **/src/App.js** - Build Form and code for validation and submit
- **/src/index.css** -  Stylesheet file that positions objects, controls text, colors, and layout
- **/src/index.js** - Render ReactDOM
- **package-lock.json | package.json** - packages used/required for page

---------

## Contributing 
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[The MIT License (MIT)](https://github.com/slumpbuster/Formik/blob/main/LICENSE)
