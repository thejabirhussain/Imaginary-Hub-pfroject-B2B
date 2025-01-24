**B2B EdTech Platform - Imaginary Hub**  
A comprehensive B2B e-learning platform developed for both creators and learners, similar to Udemy and Coursera. The platform allows creators to upload, manage, and analyze their courses, while learners can browse, enroll, and track their progress through a personalized dashboard.

**Demo Video Link**  
[Demo Video](https://drive.google.com/file/d/1qkQtHCuZ3VWsMDmBpcbviK3TCDLgz9WA/view?usp=sharing)

**Flowcharts**  
![382560965-37bd4949-a6f0-43e2-9f79-1c0444de2d72](https://github.com/user-attachments/assets/13c7e48d-8c4d-4595-a13e-49b5021e8d26)
![382560950-58727d61-2aa8-4b5c-8493-f3a802e93362](https://github.com/user-attachments/assets/15757e66-7bfa-49a8-9cd8-46cebebbe2a5)

**Hosted Link**  
[Hosted Link](https://imaginaryhubb2b.onrender.com)  
(Note: Currently, AWS services are down due to the free plan expiration, so the platform may not work properly.)

---

**Table of Contents**  
- Features  
- Tech Stack  
- Usage  
- Deployment  
- License  

---

**Features**  

**For Creators**  
- **Profile Creation**: Creators can create profiles to showcase their courses.  
- **Course Upload**: Upload course content as a .zip file.  
- **Publishing**: Published courses appear on the "All Courses" page, categorized accordingly.  
- **Analytics**: Real-time analytics for monthly watch time, views, and student enrollments, similar to YouTube analytics.  
- **Course Management**: Edit courses by adding or removing videos at any time.

**For Learners**  
- **Profile Creation**: Learners can create personalized profiles to enhance their learning experience.  
- **Course Browsing**: Browse and explore courses by category and creator profiles.  
- **Enrollment and Tracking**: Enroll in courses, access a personalized dashboard, and track progress and completion.

**General Platform Features**  
- **Secure User Authentication**: Managed via **Passport.js**, including password reset functionality.  
- **AWS Integration**:  
  - **S3**: Storage for course content.  
  - **CloudFront**: Optimized video streaming and content delivery.  
  - **Zip Handling**: Course uploads managed with **adm-zip** for unzipping and storing content.  
- **Deployment**: Deployed using **Render** and **Elastic Beanstalk** for scalability and performance.

---

**Tech Stack**  

**Frontend**  
- **EJS**: Template engine for dynamic content rendering.  
- **Bootstrap & Tailwind CSS**: For responsive and modern UI design.

**Backend**  
- **Node.js & Express.js**: For server and routing management.  
- **MongoDB**: Database for managing user profiles, courses, and analytics.  
- **Passport.js**: User authentication and session management.  
- **NPM Packages**: Various utilities for handling zip files, AWS SDK, and other functionalities.

**Cloud Services**  
- **AWS S3**: Secure storage for course content.  
- **AWS CloudFront**: Efficient video streaming and content delivery.  
- **Elastic Beanstalk**: Deployed for web server management and scalability.  
- **Render**: Alternative deployment platform.

---

**Usage**  
- **Creators**: Can log in, upload and manage courses, view analytics, and edit content.  
- **Learners**: Can create profiles, browse courses, enroll, and monitor learning progress on their personalized dashboard.

---

**Deployment**  

- **AWS Elastic Beanstalk**: Deploy the application by creating an Elastic Beanstalk environment and configuring the environment variables on AWS.  
- **Render**: Alternatively, deploy the platform on Render for continuous integration and ease of scaling.
