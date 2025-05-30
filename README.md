# Hi there, I'm Tushar Singh 👋

## 💻 Projects

Here's a highlight of a recent project I've worked on:

---

### 🍽️ SYNERGY - BookTable

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/5Qp4_Wqy)

SYNERGY, also known as BookTable, is a comprehensive online restaurant reservation platform designed to enhance the dining experience for customers, restaurant managers, and administrators. It features location-based search, real-time booking capabilities, personalized user profiles, and an integrated review system.

The project was developed collaboratively with a focus on full-stack feature ownership from design to deployment.

**🔗 Live Project/Repo:** [SYNERGY - BookTable](https://github.com/gopinathsjsu/team-project-20201-synergy)

#### ✨ Key Features:
* **User Authentication:** Secure OTP-based login via AWS Cognito with role-based access control (Customer, RestaurantManager, Admin) managed by Cognito Groups.
* **Restaurant Discovery:** Location-based search using MySQL spatial functions and Google Maps API, including map views and nearby suggestions. Customers can also see the number of bookings for a restaurant on a particular day.
* **Booking Management:** Real-time booking and cancellation with conflict detection, and email confirmations using AWS SES and Thymeleaf templates.
* **User Experience:** Personalized home and profile pages, allowing users to view restaurants and available time slots.
* **Restaurant Manager Portal:** Functionality for managers to add/update restaurant details, upload images via AWS S3 pre-signed URLs, and view a management dashboard.
* **Admin Portal:** An admin dashboard with analytics and capabilities to approve, reject, or remove restaurant listings.
* **Ratings and Reviews:** Users can submit, view, and rate restaurants.

#### 🛠️ Tech Stack:
* **Frontend:** Next.js, React, Material-UI
* **Backend:** Spring Boot (Java 17), Gradle
* **Database:** MySQL
* **Authentication:** AWS Cognito, Spring Security, JWTs
* **Cloud Services:** AWS Elastic Beanstalk, EC2, Docker, ECR, S3, SES, Lambda
* **APIs:** Google Maps GeoAPI
* **CI/CD:** GitHub Actions for automated build, test (JaCoCo), and deployment.

#### 🚀 My Contributions to SYNERGY - BookTable:

As a Full Stack Developer on this project, I took ownership of several key features, focusing on both frontend and backend development to ensure a seamless user experience. My specific contributions included:

* **Frontend Engineering & UI Development:**
    * Spearheaded the **UI Project Setup**, including the **Dockerization of the Next.js/React frontend** to streamline development and deployment processes.
    * Engineered and implemented intuitive UI components for **Login and Registration**.
    * Designed and developed the dynamic **Restaurant Search Functionality UI**, integrating robustly with the **Google Maps API** for effective location-based searching and interactive map displays.
    * Created an engaging **Customer Homepage UI**, which included integrating functionality to access the user's nearby location for personalized restaurant suggestions.
    * Developed a user-centric **Customer Profile Page**.
    * Implemented **Restaurant Cards display** for clear and concise presentation of restaurant information.
    * Enabled users to **View Restaurant Locations directly on Google Maps** from within the UI.

* **Backend Development & API Integration:**
    * Led the end-to-end development of the **Restaurant Booking and Cancellation Flow**, covering both the UI (Next.js/React) and backend (Spring Boot) aspects.
    * Developed a **Fetch All Bookings API endpoint** to allow users to retrieve their comprehensive booking history.
    * Enhanced the restaurant fetching API by adding a **Restaurant Booking Count field**, providing valuable insights into booking volumes, displayed on restaurant detail pages and cards.
    * Engineered the **Restaurant Details View (Full Stack)**, encompassing both UI and backend (Spring Boot) development, and integrated a feature to **View Restaurant Location on Google Maps**.

---
