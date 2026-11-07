# 🎬 RAKSHA | Streaming Platform

<p align="center">
  <img src="https://raw.githubusercontent.com/sirinbsandli-code/J-stream-java-project/main/JStream/src/main/resources/assets/images/logo/Raksha.png" alt="Raksha Logo" width="180"/>
</p>

<p align="center">
  <strong>A Netflix-Inspired Desktop Streaming Experience</strong>
  <br/>
  Explore. Discover. Stream.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaFX-UI_Framework-0078D4?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/JDBC-Data_Access-F7931E?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-Build_Tool-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Year-2026-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Architecture-MVC-informational?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-Desktop-E50914?style=flat-square" />
</p>

<p align="center">
  <a href="https://github.com/sirinbsandli-code/J-stream-java-project">🚀 Source Code</a> ·
  <a href="#-application-preview">📸 Application Preview</a> ·
  <a href="#-getting-started">⚙️ Installation</a> ·
  <a href="#-developer">👩‍💻 Developer</a>
</p>

---

## ✨ About Raksha

**Raksha** is a Java-based desktop streaming application inspired by the experience and visual identity of modern streaming platforms such as Netflix.

Developed using **Java 17 and JavaFX**, the application provides an interactive environment where users can explore a multimedia library, discover movies and series, and enjoy video playback directly within the application.

Raksha also integrates a dedicated administrative dashboard, allowing administrators to manage multimedia content, organize categories, and control registered user accounts.

Built around the **Model-View-Controller (MVC)** architectural pattern, the application connects to a MySQL relational database through JDBC, ensuring structured data management and persistent storage.

This collaborative academic project explores important software engineering concepts, including object-oriented programming, database integration, modular development, role-based access control, and desktop interface design.

---

## 📸 Application Preview

| User Experience | Administration Dashboard |
|:---:|:---:|
| 🎬 Browse Movies & Series | 🛠️ Manage Content |
| Integrated Video Player | Full CRUD Operations |
| Dark Streaming Interface | User & Role Management |

<p align="center">
  <em>Application screenshots coming soon.</em>
</p>

<!-- Add your screenshots here:
![User Interface](screenshots/user-interface.png)
![Admin Dashboard](screenshots/admin-dashboard.png)
-->

---

## 🚀 Key Features

### 🔐 Authentication & Role-Based Access

A centralized authentication system supporting two distinct account roles:

- **User:** Access to the streaming interface and multimedia library.
- **Admin:** Access to the administrative dashboard.

Additional capabilities:
- Database-based authentication through JDBC.
- SHA-256 password hashing.
- Role-based interface navigation.
- In-memory session management.
- Prepared SQL statements for database operations.

### 🎬 Content Browsing & Discovery

An interactive media library allowing users to explore movies and television series.

- Dynamic content retrieval from MySQL.
- Horizontally scrollable content rows.
- Organized media categories.
- Database-driven content presentation.
- A browsing experience inspired by modern streaming platforms.

### ▶️ Integrated Video Player

Raksha includes an integrated JavaFX MediaPlayer for video playback.

Custom playback controls include:
- Play and pause.
- Video progress and seeking.
- Volume adjustment.
- Fullscreen mode.
- Integrated playback interface.

### 🛠️ Admin Dashboard

A dedicated administrative environment for managing the platform.

**Content Management**
- Add, edit, and delete movies.
- Manage television series.
- Organize episodes by season.
- Create and rename categories.
- Update multimedia information.

**User Management**
- View registered accounts.
- Modify user roles.
- Deactivate accounts.
- Manage user records through MySQL.

### 🎨 Custom User Interface

A dark interface inspired by the visual identity of Netflix.

- JavaFX and custom CSS styling.
- FXML-based layouts.
- Interactive hover effects.
- Smooth scene transitions.
- Separate user and administrator interfaces.
- Consistent visual hierarchy.

---

## 🏗️ System Architecture

Raksha follows the **Model-View-Controller (MVC)** architectural pattern, with a layered structure separating the interface, application logic, and database operations.

```text
┌─────────────────────────────────────────────────┐
│              PRESENTATION LAYER                 │
│                                                 │
│              JavaFX · FXML · CSS                │
│                                                 │
│       User Interface  |  Admin Dashboard        │
└──────────────────────┬──────────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────────┐
│              APPLICATION LAYER                  │
│                                                 │
│          Controllers · Event Handlers           │
│          Business Logic · SceneManager          │
│               Session Management                │
└──────────────────────┬──────────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────────┐
│               DATA ACCESS LAYER                 │
│                                                 │
│             JDBC · DAO Classes                  │
│          Prepared Statements · SQL             │
└──────────────────────┬──────────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────────┐
│                DATABASE LAYER                   │
│                                                 │
│                  MySQL                          │
│                                                 │
│       Users · Roles · Movies · Series           │
│       Episodes · Categories · History           │
└─────────────────────────────────────────────────┘
```

### Architectural Principles

- **Modularity:** Independent components with clearly defined responsibilities.
- **Separation of Concerns:** Interface, business logic, and database operations are separated.
- **Reusability:** Shared utilities and services reduce code duplication.
- **Maintainability:** MVC and DAO patterns facilitate future development.

---

## 🧰 Technology Stack

| Technology | Role | Implementation |
|---|---|---|
| ☕ Java 17 | Core Language | OOP, business logic, event handling |
| 🎨 JavaFX | UI Framework | Scenes, FXML, CSS, MediaPlayer |
| 🗄️ MySQL | Database | Relational data storage |
| 🔌 JDBC | Data Access | SQL queries, database connectivity |
| 🏗️ Maven | Build Tool | Dependency management |
| 🖼️ Scene Builder | UI Design | FXML interface design |
| 🔧 Git & GitHub | Version Control | Source code management |

---

## ⚙️ Getting Started

Follow these instructions to configure and launch Raksha locally.

### Prerequisites

Make sure the following tools are installed:

- Java Development Kit (JDK) 17 or later.
- MySQL Server 8.0 or later.
- Apache Maven 3.8 or later.
- A Java-compatible IDE (IntelliJ IDEA, Eclipse, or VS Code).

### 1. Clone the Repository

```bash
git clone https://github.com/sirinbsandli-code/J-stream-java-project.git
```

Navigate to the project directory:

```bash
cd J-stream-java-project
```

### 2. Import the Database

Import the provided SQL script into your local MySQL server.

See the Database Configuration section below.

### 3. Configure Database Credentials

Locate the database configuration file:

```text
src/main/resources/db.properties
```

Update it with your local MySQL credentials:

```properties
db.url=jdbc:mysql://localhost:3306/raksha_db
db.username=your_username
db.password=your_password
```

### 4. Build and Run

Build the project:

```bash
mvn clean install
```

Launch the application:

```bash
mvn javafx:run
```

---

## 🗄️ Database Configuration

The project includes an SQL initialization script:

[`jstreamdb (8) (2).sql`](https://github.com/sirinbsandli-code/J-stream-java-project/blob/main/jstreamdb%20%288%29%20%282%29.sql)

It contains the database schema, relationships, constraints, and sample data required to initialize the application.

### Database Contents

The database includes seven main tables:

| Table | Description |
|---|---|
| `users` | Registered user accounts |
| `roles` | User and administrator roles |
| `movies` | Movie information |
| `series` | Television series |
| `episodes` | Series episodes |
| `categories` | Media categories |
| `watch_history` | User viewing history |

### Import Instructions

**Option A — Command Line**

```bash
mysql -u root -p < "jstreamdb (8) (2).sql"
```

**Option B — MySQL Workbench**

1. Open MySQL Workbench.
2. Connect to your MySQL server.
3. Select File → Open SQL Script.
4. Choose `jstreamdb (8) (2).sql`.
5. Execute the script using the lightning icon.

**Option C — phpMyAdmin**

1. Open `http://localhost/phpmyadmin`.
2. Navigate to Import.
3. Select the SQL initialization file.
4. Click Go.

### Default Test Accounts

| Role | Username | Password |
|---|---|---|
| 👑 Admin | `admin` | `admin123` |
| 👤 User | `demo_user` | `user123` |

> ⚠️ These are demonstration credentials. Change them before using the application in a real environment.

---

## 📖 Application Manual

A user and administrator guide is available to explain the application's main functionalities.

[`📖 Open Application Manual (PDF)`](https://github.com/sirinbsandli-code/J-stream-java-project/blob/main/manuel%20%281%29%20%282%29.pdf)

### User Guide

- Logging in and navigating the home screen.
- Browsing movies and series.
- Watching content through the integrated video player.
- Using playback controls.
- Exploring episodes by season.
- Viewing watch history.
- Logging out.

### Administrator Guide

- Accessing the Admin Dashboard.
- Adding, editing, and deleting movies.
- Managing series and episodes.
- Creating and renaming categories.
- Viewing registered users.
- Modifying user roles.
- Deactivating accounts.

### Troubleshooting

The manual also provides solutions for common issues, including authentication errors, missing database connections, playback problems, and empty content sections.

---

## 🧠 Technical Challenges & Solutions

### 01 — Role-Based Scene Management

**Challenge:** JavaFX does not provide a built-in routing mechanism for switching between multiple application interfaces.

**Solution:** A centralized `SceneManager` utility manages scene transitions. After authentication, the user's role determines which FXML interface is loaded into the primary Stage.

### 02 — Password Handling

**Challenge:** Storing plain-text passwords creates significant security risks.

**Solution:** Java's `MessageDigest` API was used to hash passwords using SHA-256 before database storage.

```java
MessageDigest md = MessageDigest.getInstance("SHA-256");

byte[] hash = md.digest(
    password.getBytes(StandardCharsets.UTF_8)
);
```

*Security note: SHA-256 is the implemented demonstration approach. Production authentication should use a dedicated salted password-hashing algorithm such as Argon2id or bcrypt.*

### 03 — Database Operations Without UI Freezes

**Challenge:** JavaFX runs on a single UI thread. Performing long database operations directly on this thread can make the application unresponsive.

**Solution:** JavaFX `Task` objects execute database queries in background threads. Results are then applied to the interface through JavaFX's UI-thread mechanisms.

```java
Task<List<Movie>> loadMovies = new Task<>() {
    @Override
    protected List<Movie> call() {
        return movieDAO.findAll();
    }
};

loadMovies.setOnSucceeded(event -> {
    updateUI(loadMovies.getValue());
});

new Thread(loadMovies).start();
```

---

## 📁 Project Structure

The application is organized into modular packages following MVC and DAO architectural principles.

```text
Raksha/
│
├── jstreamdb (8) (2).sql
├── manuel (1) (2).pdf
├── pom.xml
│
└── src/
    └── main/
        ├── java/
        │   ├── controllers/
        │   ├── dao/
        │   ├── models/
        │   ├── services/
        │   └── utils/
        │
        └── resources/
            ├── fxml/
            ├── css/
            └── db.properties
```

---

## 👩‍💻 Developer

<p align="center">
  <strong>Sirin Sandli</strong>
  <br/>
  Software Engineering Student
  <br/><br/>
  <a href="https://github.com/sirinbsandli-code">
    <img src="https://img.shields.io/badge/GitHub-Visit_Profile-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

This repository presents my work and contribution to **Raksha**, a collaborative academic software project focused on desktop application development, database integration, and JavaFX technologies.

### Areas of Interest

- Software Engineering
- Object-Oriented Programming
- Desktop Application Development
- Database Design and Management
- User Interface Development

---

<p align="center">
  <strong>RAKSHA — Bringing the Streaming Experience to Desktop.</strong>
  <br/><br/>
  Built with ☕ Java · 🎨 JavaFX · 🗄️ MySQL
  <br/><br/>
  © 2026 — Sirin Sandli
</p>
