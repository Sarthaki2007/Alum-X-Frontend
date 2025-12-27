# AlumX-Frontend 🎓📱

Welcome to **AlumX Frontend** — the modern, scalable, and intuitive client application for the **AlumX Alumni–Student Networking Platform**.

This repository contains the **Android frontend** built using **Kotlin** and **Jetpack Compose**, designed to deliver a seamless experience for students, alumni, and professors while interacting with the AlumX backend services.

---

## 📚 Table of Contents

- About AlumX Frontend  
- Core Features  
- Tech Stack  
- App Architecture  
- State Management  
- Networking  
- AI-Powered Features  
- Project Structure  
- Setup Instructions  
- Environment Configuration  
- Contribution Guidelines  
- Future Enhancements  

---

## 🎯 About AlumX Frontend

AlumX is a **college-focused alumni engagement platform** that enables:

- Students to connect with alumni mentors  
- Alumni to share industry experience  
- AI-driven discovery of mentors and skills  
- In-app resume creation using AI  
- Secure, scalable, and clean UI built with modern Android practices  

This frontend is designed to be:

- Composable-first  
- Backend-driven  
- Resume & interview ready  
- Scalable for real-world use  

---

## 🌟 Core Features

### 👤 Authentication & Onboarding
- College Email login  
- Google OAuth  
- LinkedIn OAuth  
- Role-based flows: Student, Alumni, Professor  

### 🧑‍🎓 Student Features
- AI-powered alumni search  
- Mentor requests  
- Blog interaction (like, comment, save)  
- Resume builder with AI suggestions  
- Skill & interest profiling  

### 🧑‍💼 Alumni Features
- Publish experience blogs  
- Manage mentorship requests  
- Professional profile management  
- Skill tagging for AI matching  

### 🧑‍🏫 Professor Features
- Verify users  
- Monitor mentorship quality  
- Moderate content  

### 📰 Blog Feed
- LinkedIn-style feed  
- Likes, comments, timestamps  
- Markdown rendering  

### 🤖 AI Integrations
- RAG-based alumni discovery  
- Resume bullet enhancement  
- Smart skill recommendations  

---

## 🎨 Design

Figma Board:  
https://www.figma.com/board/niVdJzTd0FK75zIqYrNyBx/Untitled

---

## ⚙️ Tech Stack

**Language:** Kotlin  
**UI:** Jetpack Compose (Material 3)  
**Architecture:** MVVM + Clean Architecture  
**Navigation:** Navigation Compose  
**DI:** Hilt  
**Async:** Coroutines + Flow  

**Networking:** Retrofit, OkHttp  
**Storage:** DataStore, Room  
**AI:** Secure backend AI integrations  

---

## 🧱 App Architecture

Presentation → ViewModel → Domain → Data → Remote  

- Unidirectional Data Flow  
- Testable components  
- Scalable structure  

---

## 🔄 State Management

- StateFlow  
- SharedFlow  
- Stateless UI  
- LaunchedEffect  

---

## 🌐 Networking

- JWT authenticated APIs  
- Centralized error handling  
- Interceptor-based requests  

---

## 📁 Project Structure

```text
com.alumx.app
├── data
├── domain
├── presentation
├── di
├── navigation
├── ui
└── utils
