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
- **README.md** – Repository overview and portfolio reflection

---

## Running the Application
1. Extract the zip file  
2. Open the project in Eclipse or any Java-compatible IDE  
3. Run `SslServerApplication.java`  
4. In your browser, navigate to:  
   **https://localhost:8443/profile**

---

## Instructor Access
This repository includes the course instructor as a collaborator to allow review and verification for assessment.

---

## Contact
For any issues accessing project files, please reach out via SNHU messages or at  
**Reuven.attias@snhu.edu**

---

# Portfolio Reflection – Module Eight

## Client Summary and Software Requirements
The client for this course was **Artemis Financial**, a financial consulting company that provides personalized financial plans for its customers, including savings, retirement, investments, and insurance. Artemis Financial required a secure public-facing web application capable of protecting sensitive client data. The primary objective was to identify existing security risks and refactor the application using secure coding and secure communication practices.

## Software Security and Vulnerability Assessment
One area I performed well in was identifying security risks related to insecure communication and third-party dependencies. Coding securely is essential because vulnerabilities can lead to data breaches, financial loss, and loss of client trust. Strong software security adds value to an organization by protecting data, ensuring application reliability, and supporting long-term business stability.

## Challenges and Insights
The most challenging part of the vulnerability assessment was reviewing dependency-check results and determining which findings posed real risk versus those that were low-impact or false positives. This process strengthened my ability to critically evaluate security reports rather than relying solely on automated tools.

## Layers of Security and Future Assessments
I increased layers of security by enforcing HTTPS, refactoring insecure configurations, and validating third-party dependencies using security analysis tools. In the future, I would continue using secure SDLC practices, static analysis tools, and vulnerability scanners to assess risks and determine appropriate mitigation strategies.

## Ensuring Functionality and Security
To ensure the application remained functional and secure, I executed and tested the refactored application after implementing security changes. I then ran secondary testing using OWASP Dependency-Check to confirm that no new vulnerabilities were introduced as a result of the refactoring.

## Tools, Resources, and Practices
The tools and practices used in this project that will be valuable in future work include Maven dependency-check, secure coding standards, HTTPS configuration, encryption practices, and vulnerability assessment documentation.

## Employer Value
This project demonstrates my ability to assess software vulnerabilities, implement secure coding practices, perform security testing, and document findings clearly. It serves as a strong example of my experience with secure software development for future employers.
