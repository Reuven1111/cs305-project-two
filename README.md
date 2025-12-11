# CS 305 – Secure Software Development  
## Project Two: Practices for Secure Software

This repository contains my completed work for **Project Two**, focused on strengthening an existing Java Spring Boot application through secure coding practices, HTTPS configuration, and formal security testing.

---

## Project Overview
The goal of this project was to refactor the application to meet secure software development standards. The work included:

### • Enforcing Secure Communications
- Implemented HTTPS using a self-signed certificate.
- Updated `application.properties` to route all traffic through **port 8443**.
- Verified the secure connection by accessing the application through  
  **https://localhost:8443/profile**.

### • Secondary (Security) Testing
- Executed **OWASP Dependency-Check** to identify vulnerabilities in third-party libraries.
- Reviewed results to ensure no new risks were introduced during refactoring.

### • Functional Testing
- Executed the refactored code and validated that application logic runs without errors.
- Confirmed stable operation of the secure configuration.

---

## Repository Contents
- **CS 305 Project Two.docx** – Full written report and analysis  
- **Project Two Code.zip** – Refactored Spring Boot HTTPS application  
- **README.md** – Repository overview

---

## Running the Application
1. Extract the zip file.  
2. Open the project in Eclipse or any Java-compatible IDE.  
3. Run `SslServerApplication.java`.  
4. In your browser, navigate to:  
   **https://localhost:8443/profile**

---

## Instructor Access
This repository includes the course instructor as a collaborator to allow review and verification for assessment.

---

## Contact
For any issues accessing project files, please reach out via SNHU messages or at Reuven.attias@snhu.edu

