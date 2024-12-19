# 🚀 DataWare Community Extension

## 📋 Project Overview

**DataWare** aims to foster collaboration and knowledge sharing within teams by adding a **community section**, inspired by platforms like *Stack Overflow*. This extension allows users to ask, answer, and manage questions associated with specific projects, while offering key features like pagination, tagging, search functionality, and moderation.

---

## 🛠️ Technologies Used

- **Backend**: PHP
- **Database**: SQL (MySQL/PostgreSQL)
- **Frontend**: JavaScript, HTML
- **Styling**: CSS Frameworks (e.g., Bootstrap, Tailwind CSS)
- **AJAX**: For dynamic content loading

---

## 📖 User Stories

### 🔐 Authentication and Navigation
- 💬 As a **user**, I want to **access** the community section after **authentication**.

### 📑 Viewing Questions and Answers
- 💬 As a **user**, I can **browse** questions and answers sorted by **date**.
- 💬 As a **user**, I can **click on a project** to view questions and answers specific to that project.
- 💬 As a **user**, I can view **10 questions per page** with **AJAX-based pagination**.

### 📝 Managing Questions
- 💬 As a **user**, I can **post a question** related to my own projects.
- 💬 As a **user**, I can **edit or delete** my own questions (**cascade delete**).
- 💬 As a **user**, I can add **multiple tags** to my question for easier search (bulk insertion).

### 💡 Managing Answers
- 💬 As a **user**, I can **answer an existing question**.
- 💬 As a **user**, I can **edit or delete** my own answers (**cascade delete**).

### ✅ Moderation and Archiving
- 💬 As a **Scrum Master**, I can **archive** inappropriate questions or answers.

### ⭐ Additional Features
- 💬 As a **user**, I can **mark an answer** as the **solution** to my question.
- 💬 As a **user**, I can **search** questions by title, tags, or content (BONUS).
- 💬 As a **user**, I can **like** or **dislike** questions and answers.
- 💬 As a **user**, I can view the total **likes/dislikes** for each answer.

### 📊 Analytics (Product Owner Features)
- 💬 As a **Product Owner**, I can view:
  - The **number of questions** per project.
  - Projects with the **most questions**.
  - The project with the **fewest answers**.
  - The **user with the most answers**.

---

## 🎨 Features at a Glance

| Feature                       | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| **Authentication**            | Secure access to the community section.                                    |
| **Pagination**                | View 10 questions per page dynamically with AJAX.                         |
| **Tagging System**            | Add multiple tags for efficient search and categorization.                |
| **CRUD Operations**           | Manage questions and answers with edit/delete capabilities.               |
| **Search Functionality**      | Search by title, tags, or content for quick access to relevant questions. |
| **Like/Dislike System**       | Evaluate questions/answers and view total likes/dislikes.                 |
| **Answer Marking**            | Mark an answer as the solution to a question.                             |
| **Moderation**                | Archive inappropriate questions/answers as a Scrum Master.                |
| **Analytics**                 | Gain insights into question and answer trends as a Product Owner.         |
