#  AI-Powered Hospital Management System

An advanced **AI-driven hospital management system** designed to streamline patient interaction, automate doctor assignment, and manage appointments efficiently.
This system simulates a **real-world hospital reception desk** using an intelligent chatbot.

---

##  Overview

The AI Hospital System acts as a **virtual medical receptionist** that interacts with patients, collects their details, understands symptoms, and assigns the most suitable doctor automatically using AI.

It also provides a **complete dashboard** where patients can view:

* Appointment details
* Doctor information
* Symptoms history
* Medical precautions

---

##  Key Objectives

* Reduce manual workload at hospital reception
* Improve patient experience with instant responses
* Automate doctor assignment based on symptoms
* Maintain structured patient records
* Provide a modern, interactive UI

---

##  Core Features

###  1. AI Medical Chatbot

* Conversational interface for patients
* Collects:

  * Name
  * Age
  * Gender
  * Symptoms
* Asks intelligent follow-up questions
* Detects emergency conditions 
* Provides basic precautions

---

###  2. Smart Doctor Assignment

* Uses AI to analyze symptoms
* Matches with best available doctor
* Handles:

  * Specialty mapping
  * Doctor availability
* Assigns **priority level**:

  * 🔴 High
  * 🟡 Medium
  * 🟢 Normal

---

###  3. Appointment Booking System

* Displays real-time available slots
* Filters only **future slots**
* One-click booking system
* Confirmation with:

  * Doctor name
  * Room number
  * Time slot
* Auto-stores in database

---

### 4. Patient Dashboard (My Health Portal)

* Displays all visit records
* Shows:

  * Doctor details
  * Appointment status
  * Symptoms
  * Precautions
* Includes:

  * Search functionality 
  * Priority indicators
  * Clean UI cards

---

###  5. Authentication System

* Secure login/signup
* Role-based access:

  * Admin
  * Staff/User
* Session management

---

###  6. Database Management

* SQLite database
* Stores:

  * Patient details
  * Symptoms
  * Doctor assigned
  * Appointment slot
  * Precautions
  * Visit timestamp

---

###  7. Modern UI/UX

* Clean and responsive design
* Mobile-friendly layout 
* Interactive chat interface
* Real-time updates

---

##  Tech Stack

###  Frontend

* HTML5
* CSS3 (Modern UI styling)
* JavaScript (Vanilla JS)

###  Backend

* Python
* Flask (Web framework)

###  Database

* SQLite

###  AI Integration

* Groq API
* LLaMA 3.3 (70B versatile model)

---

## System Workflow

1. User opens chat interface
2. AI collects patient details
3. User describes symptoms
4. AI asks follow-up questions
5. System assigns best doctor
6. Available slots are displayed
7. User selects slot
8. Appointment is booked
9. Data saved to database
10. Dashboard shows records

##  Application Modules

###  Counter Page

* AI chat interface
* Patient interaction
* Doctor assignment

###  Dashboard

* Patient records
* Appointment tracking
* Search/filter system

###  My Health Portal

* Personal visit history
* Doctor & appointment details
* Precautions display

---

##  Security Best Practices

* API keys stored in `.env`
* `.env` excluded using `.gitignore`
* No sensitive data in code
* Session-based authentication

---

##  Future Enhancements

*  Email/SMS notifications
*  Online payment integration
*  Multi-hospital support
*  Analytics dashboard
*  Cloud deployment (AWS/Render)
*  Mobile app version

###  Skills

* Python, Flask, Django
* HTML, CSS, JavaScript
* MySQL, SQLite
* AI Integration

---

## Learning Outcomes

This project demonstrates:

* Full-stack web development
* API integration (AI systems)
* Database design
* Real-world problem solving
* UI/UX design principles


