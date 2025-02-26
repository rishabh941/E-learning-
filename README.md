# Thinkly

Thinkly is a comprehensive educational platform designed to provide a seamless learning experience for students and educators. It facilitates learning, collaboration, and resource sharing through an intuitive and feature-rich interface.

## Technology Stack

### Frontend:

- **Figma**: UI/UX design tool for interface prototyping.
- **React.js**: JavaScript library for building dynamic UIs.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Redux**: State management for efficient application control.
- **Chart.js**: Library for data visualization.

### Backend:

- **Node.js**: JavaScript runtime for backend operations.
- **Express.js**: Framework for building RESTful APIs.
- **MongoDB**: NoSQL database for scalable data storage.
- **Cloudinary**: Cloud-based media management solution.

## Features

- **User Authentication & Authorization**: OTP verification, login, and password reset.
- **Course Management**: Create, update, and delete courses.
- **Payment Integration**: Razorpay-based payment handling.
- **Cloud-Based Media Management**: Secure storage for images, videos, and documents.
- **Markdown Support**: Content formatting for seamless display.

## API Routes

### Authentication

- `/api/v1/auth/signup` - User Registration
- `/api/v1/auth/login` - User Login

### Profile

- `/api/v1/profile/getUserDetails` - Fetch User Details
- `/api/v1/profile/updateProfile` - Update Profile

### Course

- `/api/v1/course/getAllCourses` - List All Courses
- `/api/v1/course/createCourse` - Create a New Course
- `/api/v1/course/deleteCourse` - Remove Course

### Payment

- `/api/v1/payment/capturePayment` - Payment Handling
- `/api/v1/payment/verifyPayment` - Verify Payment

## Frontend Pages

### Student

- **Homepage**: Introduction to the platform.
- **Course List**: Browse available courses.
- **Wishlist**: Save favorite courses.
- **Checkout**: Complete course purchases.
- **User Profile**: Manage account details.

### Instructor

- **Dashboard**: View insights and manage courses.
- **Course Management**: Create and modify course content.
- **Profile Management**: Update instructor details.

### Admin (Future Scope)

- **Dashboard**: Manage users, courses, and revenue.
- **Instructor & Course Management**: Oversee platform activities.

## Installation

Clone the repository: 
```
git clone https://github.com/username/repo.git
```

Navigate to the project directory:
```
cd Thinkly
```

Install dependencies:
```
npm install
```

## Configuration

Set up a MongoDB database and obtain the connection URL.

Create a `.env` file in the root directory with the following environment variables:
```
MONGODB_URI=<your-mongodb-connection-url>
JWT_SECRET=<your-jwt-secret-key>
```

## Usage

Start the server:
```
npm start
```

Open a new terminal and navigate to the client directory:
```
cd client
```

Start the React development server:
```
npm start
```

Access the application in your browser at:
```
http://localhost:3000
```


