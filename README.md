# Studynotion-An Ed-tech Platform [Website Link](https://studynotion-frontend.vercel.app/)

![Main Page](images/mainpage.png)

StudyNotion is a cutting-edge ed-tech platform designed to enhance the learning experience for students and educators. It offers personalized learning paths, interactive course materials, and real-time progress tracking.

# Features
- Personalized learning paths
- Interactive course materials and quizzes
- Real-time progress tracking and performance analytics
- Collaborative study tools (forums, study groups)
- Secure user authentication and data privacy

# Tech Stack
- Frontend: ReactJS
- Backend: NodeJS, ExpressJS
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)

# Frontend
The front-end of the platform is built using ReactJS, which allows for the creation of dynamic and responsive user interfaces, crucial for providing an engaging learning experience to students. The front-end communicates with the back-end using RESTful API calls.

For Students:

- Homepage: A brief introduction to the platform with links to the course list and user details.
- Course List: A list of all the courses available on the platform, along with their descriptions and ratings.
- Wishlist: Displays all the courses that a student has added to their wishlist.
- Cart Checkout: Allows the user to complete course purchases.
- Course Content: Presents the course content for a particular course, including videos and related material.
- User Details: Provides details about the student's account, including their name, email, and other relevant information.
- User Edit Details: Allows students to edit their account details.

For Instructors:

- Dashboard: Offers an overview of the instructor's courses, along with ratings and feedback for each course.
- Insights: Provides detailed insights into the instructor's courses, including the number of views, clicks, and other relevant metrics.
- Course Management Pages: Enables instructors to create, update, and delete courses, as well as manage course content and pricing.
- View and Edit Profile Details: Allows instructors to view and edit their account details.

# Backend
The back-end of the platform is built using NodeJS and ExpressJS, providing APIs for the front-end to consume. These APIs include functionalities such as user authentication, course creation, and course consumption. The back-end also handles the logic for processing and storing the course content and user data.

- User Authentication and Authorization: Students and instructors can sign up and log in to the platform using their email addresses and passwords. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
- Course Management: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
- Payment Integration: Students will purchase and enroll in courses by completing the checkout flow, followed by Razorpay integration for payment handling.
- Cloud-based Media Management: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
- Markdown Formatting: Course content in document format is stored in Markdown format, allowing for easier display and rendering on the front-end.

# Database

The database for the platform is built using MongoDB, which is a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data. The database stores the course content, user data, and other relevant information related to the platform.

# Architectural Design

Here is a high-level diagram that illustrates the architecture of the StudyNotion ed-tech platform:

  
# Getting Started
- Clone this repository: git clone https://github.com/your-username/StudyNotion.git
- Install dependencies: npm install
- Run the development server: npm start


# Contributing
StudyNotion is open-source, and contributions are welcome! Please review the [Contributing Guidelines](https://github.com/github/docs/blob/main/CONTRIBUTING.md) for more details.

