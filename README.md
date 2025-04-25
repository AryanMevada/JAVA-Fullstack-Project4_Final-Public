# Student Management System (Frontend + Backend )

This is the Angular frontend for the **Student Management System**, designed to allow users to manage student records through a user-friendly interface. It integrates with a Spring Boot backend and uses PostgreSQL as the database.

## 🧩 Features

- Add, update, and delete student records
- View all students in a tabular format
- Form validation and clean UI
- Responsive design using Angular components
- RESTful API backend with Spring Boot
- PostgreSQL database integration

## 🛠️ Tech Stack

- **Frontend:** Angular 15+
- **Backend:** Spring Boot (Java)
- **Database:** PostgreSQL
- **Languages:** TypeScript, Java, HTML, CSS
- **Package Manager:** npm
- **Build Tool:** Angular CLI, Maven

## 🚀 Getting Started

### Prerequisites

Make sure the following tools are installed on your system:

- [Node.js](https://nodejs.org/) (v16+)
- [Angular CLI](https://angular.io/cli) (v15+)
- npm (comes with Node.js)
- [Java JDK 17+](https://adoptopenjdk.net/)
- Maven
- PostgreSQL

---

## ⚙️ Backend Configuration (Spring Boot)

### PostgreSQL Setup

Make sure PostgreSQL is installed and running. Then create a database:

```sql
CREATE DATABASE student_data;
```

### `application.properties`

In your Spring Boot project, configure the following:

```properties
spring.application.name=studentmanagement
spring.datasource.url=jdbc:postgresql://localhost:5432/student_data
spring.datasource.username=postgres
spring.datasource.password=1234

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.database-platform=org.hibernate.dialect.PostgreSQLDialect
spring.jpa.properties.hibernate.format_sql=true

logging.level.org.springframework.security=DEBUG
```

### Running the Backend

```bash
# Navigate to the backend project folder
cd student-management-backend

# Run the Spring Boot application
mvn spring-boot:run
```

By default, the backend runs at `http://localhost:8080`.

---

## 🌐 Frontend Setup (Angular)

```bash
# Clone the repository
git clone https://github.com/your-username/student-management-frontend.git
cd student-management-frontend

# Install dependencies
npm install

# Run the development server
ng serve
```

Open your browser at 👉 `http://localhost:4200`

---

## 📁 Project Structure

```
student-management-frontend/
├── src/
│   ├── app/
│   │   ├── components/       # Angular components
│   │   ├── services/         # HTTP services
│   │   └── app.module.ts     # Root module
├── angular.json
├── package.json
└── tsconfig.json
```

## 📦 Build (Frontend)

```bash
ng build
```

Artifacts are stored in the `dist/` directory.


## 🤝 Contributing

Contributions are welcome and appreciated!

1. Fork this repo
2. Create a branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push (`git push origin feature/YourFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the [MIT License](LICENSE).


## SnapShot of project

![Image Alt]([https://github.com/AryanMevada/JAVA-Fullstack-Project4_Final/blob/main/Screenshot%202025-04-25%20153228.png](https://github.com/AryanMevada/JAVA-Fullstack-Project4_Final-Public/blob/main/project%20folder/student-management-frontend/Screenshot%202025-04-25%20153155.png))

![Image Alt](https://github.com/AryanMevada/JAVA-Fullstack-Project4_Final-Public/blob/main/project%20folder/student-management-frontend/Screenshot%202025-04-25%20153228.png)

Made with  using Angular, Spring Boot & PostgreSQL.

