# CS-305 Software Security

## Client: Artemis Financial

Artemis Financial is a financial services company seeking to enhance the security of its public-facing website. Their primary objective was to implement effective encryption methods to protect user data transmitted between clients and servers. Ensuring the confidentiality and integrity of this information was critical for maintaining trust and compliance with security best practices.

## Project Overview

This project focused on assessing and mitigating security vulnerabilities in Artemis Financial’s software infrastructure. Our key goals included:

- Conducting a **dependency analysis** to identify and address security risks.
- Implementing **SHA-256 encryption** to secure data transmission.
- Utilizing **self-signed certificates** for controlled access to critical systems.
- Enhancing software security to prevent unauthorized access and data breaches.

## Key Achievements

### 1. **Vulnerability Assessment & Dependency Checks**

One of the major challenges was analyzing the **Dependency Check Report** and distinguishing between **false positives** and actual security threats. By conducting multiple assessments, we prioritized vulnerabilities that required immediate action and mitigated risks effectively.

### 2. **Secure Coding Practices & Risk Mitigation**

- Implemented **SHA-256 encryption** to ensure the integrity of data transmission.
- Applied **dependency management techniques** to address security risks in third-party libraries.
- Introduced **suppressions for false positives**, refining the accuracy of security reports.

### 3. **Testing & Validation**

After implementing security measures, rigorous testing was conducted:

- **Checksum validation** ensured proper SHA-256 encryption functionality.
- **Dependency checker reports** verified that suppressed vulnerabilities were handled correctly.
- **Local environment testing** confirmed secure communication between the test site and the server.

## Challenges & Learnings

### **Understanding Dependency Reports**

Initially, interpreting dependency reports and identifying true security threats posed a challenge. However, repeated testing and analysis helped refine the process, making it easier to differentiate between benign alerts and critical vulnerabilities.

### **Enhancing Layered Security**

By securing dependencies and implementing encryption mechanisms, we strengthened security at multiple levels. In future projects, similar tools, such as the **Maven Dependency Checker**, will be used to proactively assess vulnerabilities and apply appropriate mitigation strategies.

## Tools & Techniques Used

- **Maven Dependency Checker** – Automated security assessment for third-party dependencies.
- **SHA-256 Encryption** – Ensured secure data transmission.
- **Self-Signed Certificates** – Enhanced controlled access to secure domains.
- **False Positive Suppression** – Improved accuracy of security reports.

## Future Applications & Employer Showcase

This project provided valuable hands-on experience with **software security best practices**. Future employers may find the following skills and accomplishments relevant:

- **Dependency Analysis** – Proficiency in identifying and mitigating software vulnerabilities.
- **Encryption & Secure Data Handling** – Implementing SHA-256 and SSL/TLS techniques.
- **Software Security Audits** – Conducting vulnerability assessments and refining security reports.

## Conclusion

Software security is a crucial aspect of software development, ensuring that sensitive data remains protected from potential threats. This project reinforced the importance of **secure coding**, **regular vulnerability assessments**, and **proactive mitigation strategies** in safeguarding critical systems.
