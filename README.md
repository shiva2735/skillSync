# SkillSync

**SkillSync** is a collaborative learning and mentorship platform designed to connect learners and mentors based on skills, interests, and goals. It enables users to explore skills, build learning paths, track their progress, and showcase projects in a dynamic and interactive way.

---

## 🚀 Tech Stack

### Frontend

* **React + TypeScript**
* **Material UI (MUI)** for modern components
* **SASS** for styling and custom themes
* **Axios** for API communication
* **Vite** for lightning-fast development build

### Backend

* **Spring Boot (Java)** — RESTful API backend
* **PostgreSQL** — relational database
* **JWT Authentication** — secure user access
* **Maven/Gradle** — for build management

---

## 🧩 Core Features

### 1. User Management

* Signup & Login (with JWT-based authentication)
* Profile creation with skills, interests, and goals
* Role-based access (Learner, Mentor, Admin)

### 2. Skill Explorer

* Browse and filter skills by domain, difficulty, or popularity
* Follow or bookmark skills for learning
* View curated resources and learning paths

### 3. Learning Paths

* Create personalized learning paths for any skill
* Track completion progress with milestones
* Suggest mentors or peers with similar goals

### 4. Project Showcase

* Users can create and share project portfolios
* Like, comment, and give feedback on peer projects
* Tag projects by skills, tools, or difficulty level

### 5. Dashboard

* Personalized dashboard showing:

  * Learning progress
  * Active mentors/mentees
  * Recent project activities
  * Upcoming learning milestones

### 6. Notifications & Activity Feed

* Real-time updates for new followers, project feedback, or mentorship requests

---

## 🗂️ Project Structure

### Frontend (`/frontend`)

```
src/
 ├── components/
 ├── pages/
 ├── hooks/
 ├── context/
 ├── services/
 ├── assets/
 └── styles/
```

### Backend (`/backend`)

```
src/main/java/com/skillsync/
 ├── controller/
 ├── service/
 ├── repository/
 ├── model/
 ├── dto/
 ├── config/
 └── exception/
```

---

## ⚙️ Setup Instructions

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
mvn spring-boot:run
```

---

## 🧠 Development Workflow

1. Create a new branch for a feature:

   ```bash
   git checkout -b feature/feature-name
   ```

2. Commit changes with a clear message:

   ```bash
   git commit -m "Add: feature description"
   ```

3. Push the branch to GitHub:

   ```bash
   git push origin feature/feature-name
   ```

4. Open a Pull Request (PR) for review.

---

## 📅 Planned Modules

| Phase | Module         | Description                    |
| ----- | -------------- | ------------------------------ |
| 1     | Authentication | JWT-based login & signup       |
| 1     | Skill Explorer | Browse & filter skills         |
| 2     | Learning Paths | Personalized learning tracking |
| 2     | Projects       | Showcase & feedback            |
| 3     | Dashboard      | Unified user view              |
| 3     | Notifications  | Real-time activity updates     |

---

## 🎯 Goals

* Build a **scalable full-stack application** using React + Spring Boot.
* Learn **TypeScript**, **Spring Boot**, and **REST API integration**.
* Develop **production-grade frontend** with reusable MUI components.
* Practice **modular code architecture**, **state management**, and **secure API design**.

---

**Let’s build SkillSync — a platform that empowers learning through collaboration 🚀**
