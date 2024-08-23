# Study Notion

Study Notion is an ED Tech (Education Technology) web application developed using the MERN stack.

## Note

This project is intended as a learning tool and can be used as a sample project for educational or personal purposes.

***

## Features

- **User Authentication**: Provides secure user registration and authentication using JWT (JSON Web Tokens). Users can sign up, log in, and manage their profiles with ease.
  
- **Courses and Lessons**: Instructors can create and manage courses. Students can enroll in courses, access course materials, and track their progress.
  
- **Progress Tracking**: Allows students to track their progress in enrolled courses. They can view completed lessons, scores on quizzes and assignments, and overall course progress.
  
- **Payment Integration**: Integrates with Razorpay for secure payment processing. Users can make payments for course enrollment and other services using various payment methods supported by Razorpay.
  
- **Search Functionality**: Features a search tool to help users easily find courses, lessons, and resources quickly.
  
- **Instructor Dashboard**: Provides a comprehensive dashboard for instructors to view information about their courses, students, and income. Includes charts and visualizations to present data clearly and intuitively.

***

## Screenshots
![Screenshot 2024-08-12 153647](https://github.com/user-attachments/assets/21875440-8369-4ff1-b2f5-53f124115366)
![Screenshot 2024-08-12 153725](https://github.com/user-attachments/assets/fa25c935-88c6-48bd-8e2d-79e99491e202)
![SN-1](https://github.com/user-attachments/assets/09b811c2-27a2-45d4-bf92-373bb7819581)
***

## Important

- The backend is located in the `server` folder.
- Before uploading courses, create the necessary categories (e.g., Web Development, Python). To create categories, create an Admin account and access the admin panel via the dashboard.
- To create an Admin account, first sign up with a student or instructor account, then go to your database under the users model and change `accountType` to `Admin`.

## Installation

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/Laukik-Vashistha/Edtech_Platform
    ```

2. **Install Required Packages:**
    ```sh
    cd Study-Notion-master
    npm install
    
    cd server
    npm install
    ```

3. **Set Up Environment Variables:**

   Create a `.env` file in the root directory and the `/server` folder. Add the required environment variables such as database connection details, JWT secret, and any other necessary configurations. Check the `.env.example` files for more information.

4. **Start the Development Server:**
    ```sh
    npm run dev
    ```

5. **Open the Project:**

   Open your browser and go to (http://localhost:3000) to view your project.

The project uses `postcss-cli` to process CSS files. You can add your own `tailwind.config.js` file to customize your Tailwind setup.

