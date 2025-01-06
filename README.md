# Pet-Adoption-Platform-Maven-Review-3-4

# 🐾 Pet Adoption Platform  

Welcome to the **Pet Adoption Platform**, a web application designed to help users adopt pets, manage shelters, and streamline the adoption process with an easy-to-use interface.  

---

## ✨ **Features**  

### 🏠 Home Page  
- Welcoming, user-friendly interface.  
- Quick navigation to all features.  

### 🐕 Pet Adoption  
- Browse pets by category: Dogs, Cats, etc.  
- Filter pets by **Breed**, **Age**, **Gender**, **Vaccination Status**, and more.  

### 🏢 Shelter Management  
- Add and manage pet shelters.  
- Update shelter details and manage requirements.  

### 👤 User Management  
- Login and Registration forms.  
- Separate dashboards for Admin, Shelter Managers, and Adopters.  

---

## 🛠️ **Technology Stack**  

- **Frontend:** JSP, HTML5, CSS3, JavaScript (with Bootstrap for responsiveness).  
- **Backend:** Java Servlets with Maven.  
- **Database:** MySQL for storing user, shelter, and pet data.  
- **Server:** Apache Tomcat.  

---

## 🗂️ **Project Structure**  

```plaintext
pet-adoption-platform/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com.adoptionplatform/
│   │   │   │   ├── Main.java
│   │   │   │   ├── AdopterServlet.java
│   │   │   │   ├── ShelterServlet.java
│   │   │   │   ├── UserDAO.java
│   │   │   │   ├── AdoptionApplicationDAO.java
│   │   │   │   ├── AdoptionService.java
│   │   │   │   └── Pet.java
│   │   ├── resources/
│   │   │   └── application.properties
│   │   ├── webapp/
│   │       ├── WEB-INF/
│   │       │   └── web.xml
│   │       ├── index.jsp
│   │       ├── login.jsp
│   │       ├── registration.jsp
│   │       ├── adopter.jsp
│   │       ├── shelter.jsp
│   │       ├── pet-list.jsp
│   │       ├── styles.css
│   │       └── script.js
│   └── test/
│       └── java/
│           └── com.adoptionplatform/
│               └── MainTest.java
│
├── pom.xml
└── README.md
