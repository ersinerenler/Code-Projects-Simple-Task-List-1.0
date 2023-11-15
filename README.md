# Code-Projects-Simple-Task-List-1.0

Welcome to the Code-Projects Simple Task List 1.0 repository. This project aims to provide efficient inventory management.

## Security Vulnerabilities

### CVE-2023-46023

- **Description:** SQL Injection vulnerability via `addTask.php`, 'status', parameter.
- **Affected Version:** 1.0
- **Affected File:** `/TaskList/addTask.php`
- **Vulnerable Parameter:** 'status'
- **Impact:** Attackers can inject and execute malicious scripts via the 'status' parameter.
- **Solution:** Implement proper input validation and output encoding for the 'status' parameter in `/TaskList/addTask.php`.
