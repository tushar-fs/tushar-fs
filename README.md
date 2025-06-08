# Hi there, I'm Tushar Singh 👋

## 💻 The following projects showcase my skills and experience.

---

### 🍽️ BookTable Web Application  
**SYNERGY**, also known as BookTable, is a comprehensive online restaurant reservation platform designed to enhance the dining experience for customers, restaurant managers, and administrators. It features location-based search, real-time booking capabilities, personalized user profiles, and an integrated review system.  

The project was developed collaboratively with a focus on full-stack feature ownership from design to deployment.

🔗 **Live Project/Repo:** SYNERGY - BookTable

#### 🚀 My Contributions:  
As a Full Stack Developer on this project, I took ownership of several key features, focusing on both frontend and backend development to ensure a seamless user experience.

**Frontend Engineering & UI Development:**
- Spearheaded the UI Project Setup, including the Dockerization of the Next.js/React frontend to streamline development and deployment.
- Engineered and implemented intuitive UI components for Login and Registration.
- Designed the dynamic Restaurant Search Functionality UI, integrating with the Google Maps API for location-based searching.
- Created an engaging Customer Homepage UI with personalized restaurant suggestions based on the user's location.
- Developed a user-centric Customer Profile Page and Restaurant Cards display.

**Backend Development & API Integration:**
- Led the end-to-end development of the Restaurant Booking and Cancellation Flow (UI and Spring Boot backend).
- Developed a Fetch All Bookings API endpoint for users to retrieve their booking history.
- Engineered the Restaurant Details View (Full Stack), encompassing both UI and backend development.
- Enhanced the restaurant fetching API by adding a Restaurant Booking Count field to provide valuable insights.

---

### 🤖 Customer Support Analyzer (RAG) 
A full-stack application that leverages a **Retrieval-Augmented Generation (RAG)** architecture to provide intelligent answers from a knowledge base of historical support tickets. This allows support staff to quickly find solutions to customer problems by asking questions in natural language.

> **Status:** Currently undergoing active development and feature enhancement.🧑‍💻

#### Key Features:
- **Natural Language Queries:** Users can ask questions in plain English through a clean, modern UI.
- **AI-Generated Answers:** Utilizes Google's gemini-1.5-flash-latest model to generate concise and relevant answers.
- **Source-Backed Responses:** Returns the original source tickets from the knowledge base for verification.
- **Efficient Vector Search:** Employs ChromaDB for fast and accurate similarity search.

#### Technology Stack:
- **Backend:** Python, FastAPI, Vector database(ChromaDB), google-generativeai, sentence-transformers (hugging face model)  
- **Frontend:** Next.js, React, Tailwind CSS, lucide-react

---

### ⚙️ Log Processing Application (CLI)  
This command-line tool parses diverse log files (.txt), categorizing and aggregating entries into structured JSON files to make log data more accessible and analyzable.

It efficiently handles various log types, including:
- 📊 APM (Application Performance Metrics) Logs  
- 🖥️ Application Logs (Errors, Warnings, Info)  
- 🌐 Request Logs

The application leverages robust design patterns for extensibility and maintainability:
- 🔗 **Chain of Responsibility:** For sequential log processing by type.
- 🎯 **Strategy Pattern:** To encapsulate distinct log aggregation logic.

#### Technologies Used:
- Java  
- Gradle  
- Gson (JSON serialization)
