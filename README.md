# 🌐 Local Business Landing Website

A responsive and modern landing page built using **Java Servlets**, **HTML**, **CSS**, and **JavaScript**. This project showcases a simple yet elegant front-end integrated with a basic servlet that handles contact form submissions.

---

## 📌 Features

- Smooth-scrolling navigation
- Hero banner with call-to-action
- Services section with icons
- About section with business description
- Contact form (handled by Java Servlet)
- Responsive design with modern UI
- Font Awesome icon integration

---

## 🚀 Technologies Used

| Technology         | Purpose                       |
|--------------------|-------------------------------|
| Java Servlet (Jakarta API) | Backend for form handling     |
| HTML5 & CSS3       | Page structure and styling    |
| JavaScript         | Smooth scrolling interaction  |
| Apache Tomcat      | Deployment and execution      |
| Maven              | Project build and dependency management |
| Font Awesome CDN   | Icons                         |

---

## 🗂 Project Structure

LocalBusiness/
├── pom.xml
├── src/
│ └── main/
│ ├── java/
│ │ └── com/localbusiness/servlet/
│ │ └── ContactServlet.java
│ └── webapp/
│ ├── index.html
│ ├── css/
│ │ └── style.css
│ ├── js/
│ │ └── main.js
│ └── WEB-INF/
│ └── web.xml (optional)

---

## 🛠️ Setup Instructions

### ✅ Prerequisites

- Java JDK 11+
- Apache Maven
- Apache Tomcat 10+
- IDE (like VS Code or IntelliJ)
- Basic knowledge of Servlets

### ⚙️ Build & Deploy (Using CMD or Terminal)

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/LocalBusiness.git
   cd LocalBusiness
mvn clean package
cd path/to/apache-tomcat/bin
./startup.sh   # On Unix/Linux
startup.bat    # On Windows
http://localhost:8080/LocalBusiness/
Your Name –Rakshith H N
email=hnrakshith4@gmail.com

