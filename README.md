# rObotics Website

rOboticskid is an educational platform offering a variety of courses designed to spark the interest and creativity of children in programming, robotics, electronics, and more. This repository contains the codebase for the KiddyPi website, including the main landing page and a contact form integrated with Firebase for data storage and an API for sending email notifications.

## Features

- **Responsive Design**: The website is designed to be responsive and user-friendly across various devices.
- **Course Search and Filtering**: Users can search and filter courses based on age groups.
- **Interactive Course Categories**: Dropdown menu for navigating different course categories.
- **Contact Form**: A fully functional contact form that stores user data in Firebase and sends email notifications.

## Technologies Used

- **HTML5 & CSS3**: For structuring and styling the web pages.
- **JavaScript**: For adding interactivity to the web pages.
- **Font Awesome**: For icons.
- **Firebase**: For storing contact form data.
- **API Integration**: For sending email notifications upon form submission.

## Pages

- **Home Page (`index.html`)**
  - Displays the navigation bar, course search, course categories, and featured courses.
  - Contains sections for news and blogs.

- **Contact Us Page (`contactUs.html`)**
  - Features a contact form for users to get in touch.
  - Form submissions are saved in Firebase and trigger an email notification.

## Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/kiddypi-website.git
    cd kiddypi-website
    ```

2. **Open `index.html` in your browser** to view the main landing page.

3. **Open `contactUs.html` in your browser** to view and test the contact form.

4. **Firebase Integration**:
    - Ensure you have a Firebase project set up and replace the Firebase configuration in the `contactUs.html` with your project details.

5. **Run Locally**:
    - Use a local server (like `Live Server` in VSCode) to run the website locally and ensure all features are working correctly.

## Firebase Configuration

Replace the Firebase configuration in `contactUs.html` with your Firebase project details:

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    databaseURL: "YOUR_DATABASE_URL",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_STORAGE_BUCKET",
    messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
    appId: "YOUR_APP_ID"
};

```
## Contribution
Contributions are welcome! If you have any ideas or improvements, please feel free to open an issue or submit a pull request.
