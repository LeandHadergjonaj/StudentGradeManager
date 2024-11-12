# Student Grade Management System

A Java-based application for managing student grades, developed as part of the CS2800 coursework. This system allows for adding, updating, and viewing student grades for different modules.

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## About the Project
This project is developed as part of the CS2800 coursework to provide a simple and efficient way to manage student grades. It includes functionalities to:
- Add student details and grades.
- Calculate average grades.
- Track the progress of students in various modules.

## Features
- Add student and module details.
- Manage student grades for different modules.
- Calculate and display the average grade.
- Exception handling for invalid grades and students not found.

## Getting Started
To get a local copy of the project up and running, follow these steps.

### Prerequisites
- **Java 17 or later**:
  ```bash
  java -version
  ```
- **Maven**:
  ```bash
  brew install maven
  ```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-grade-management.git
   ```
2. Navigate to the project directory:
   ```bash
   cd student-grade-management
   ```
3. Build the project using Maven:
   ```bash
   mvn clean install
   ```

## Usage
To run the application:
```bash
mvn exec:java -Dexec.mainClass="uk.ac.rhul.cs2800.Main"
```

## Project Structure
- `src/main/java` - Contains the source code.
  - `uk.ac.rhul.cs2800.model` - Core classes for managing students, grades, and modules.
- `src/test/java` - Contains JUnit tests for the project.
- `pom.xml` - Project Object Model file for managing dependencies.

## Contributing
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some amazing feature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Your Name - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/yourusername/student-grade-management](https://github.com/yourusername/student-grade-management)

## Acknowledgments
- [SDKMAN](https://sdkman.io/) for managing Java versions.
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/) for formatting this README.
