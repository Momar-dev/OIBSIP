# OIBSIP — Android App Development Internship

A collection of three native Android applications developed as part of the **Oasis Infobyte (OIBSIP) Android App Development Internship**.

The repository demonstrates practical Android development skills through utility tools, an interactive quiz application, and a task management app with local authentication and data storage.

## 📱 Projects

### 1. Unit Converter — Task 1

A simple and intuitive Android application for converting values between different measurement units.

**Features**
- Length and weight conversions.
- Temperature conversions.
- Input validation and error handling.
- Swap units and reset inputs.
- Copy conversion results.
- Dark-themed user interface.

**Technologies:** Java, XML, Android SDK.

### 2. Quiz Master — Task 2

An interactive quiz application designed to test knowledge and provide immediate feedback.

**Features**
- Multiple-choice questions.
- Instant answer feedback and explanations.
- Score tracking and progress indicators.
- Results summary and answer review.
- Replay quizzes.
- Local best-score storage.
- Offline functionality.

**Technologies:** Java, XML, Android SDK, SharedPreferences.

### 3. TaskFlow — Task 3

A task management application with a local login system and personalized task organization.

**Features**
- User registration and login.
- Password hashing.
- User-specific task management.
- Create, view, update, and delete tasks.
- Task filtering and progress tracking.
- Local SQLite database.
- Logout and session management.
- Offline functionality.

**Technologies:** Java, XML, Android SDK, SQLite, SharedPreferences.

## 🛠️ Tech Stack

- **Language:** Java
- **UI:** XML layouts and Android Views
- **Platform:** Native Android
- **Local storage:** SQLite and SharedPreferences, where applicable
- **Development tools:** Android Studio and Android SDK

## 📂 Repository Structure

```text
OIBSIP/
├── Task1_UnitConverter/
│   ├── app/
│   └── README.md
├── Task2_QuizMaster/
│   ├── app/
│   └── README.md
├── Task3_TaskFlow/
│   ├── app/
│   └── README.md
└── README.md
```

Each project directory contains its own Android application source code and project documentation.

## 🚀 Getting Started

### Prerequisites

- Android Studio
- Android SDK compatible with the project's Gradle configuration
- JDK version required by the project
- An Android emulator or a physical Android device

### Run a project

1. Clone this repository:

   ```bash
   git clone https://github.com/Momar-dev/OIBSIP.git
   ```

2. Open Android Studio.
3. Select **Open** and choose one of the project directories:
   - `Task1_UnitConverter`
   - `Task2_QuizMaster`
   - `Task3_TaskFlow`
4. Allow Gradle synchronization to complete.
5. Connect an Android device or start an emulator.
6. Build and run the selected application.

**Note:** Open each project directory separately if it contains its own Gradle project files. If the root directory does not contain a Gradle configuration, do not open the repository root as a single Android Studio project.

## 🧪 Testing

Testing should cover the main features of each application:

- **Unit Converter:** conversion accuracy, input validation, unit swapping, and reset behavior.
- **Quiz Master:** answer selection, scoring, progress tracking, result review, and best-score persistence.
- **TaskFlow:** registration, login, task CRUD operations, filtering, data persistence, and user-data isolation.

Test results should be documented once the relevant checks have been run successfully in the actual Android build or on an emulator/device.

## 🎥 Demo Videos

Demonstration videos will be added here when available.

- **Unit Converter:** Coming soon
- **Quiz Master:** Coming soon
- **TaskFlow:** Coming soon

## 🎯 Internship Objectives

This project collection focuses on:

- Building native Android applications.
- Designing user-friendly interfaces with XML.
- Implementing application logic in Java.
- Managing local data and user preferences.
- Handling user input and application state.
- Organizing and documenting Android projects with Git and GitHub.

## 👨‍💻 Author

**Momar**  
GitHub: [@Momar-dev](https://github.com/Momar-dev)

## 📄 License

No license has been specified yet. Unless a license is added, the repository should not be assumed to grant others permission to reuse, distribute, or modify its code.
