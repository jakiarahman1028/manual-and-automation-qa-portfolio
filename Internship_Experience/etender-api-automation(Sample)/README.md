# eTender Sample API Tests

This repository demonstrates **API automation and CI/CD skills** using **Postman, Newman, and GitHub Actions**.

The workflow was implemented in the **eTender project** to **automate API testing** of critical endpoints in the QA environment, ensuring faster feedback, consistent test execution, and easier integration into a CI/CD pipeline.

- **Automated API Testing:** Runs the `eTender-API-v1` Postman collection against the QA environment using Newman.  
- **CI/CD Workflow:** GitHub Actions workflow simulates a real CI/CD pipeline:
  - Checks out code
  - Sets up Node.js
  - Installs Newman
  - Runs API tests and generates a JUnit report
  - Uploads test results as artifacts

  ![Workflow Run Output](<Workflow Run Example-1.png>)


- The workflow structure is identical to a production CI/CD pipeline but **does not run automatically** on push, making it safe for public demonstration.



