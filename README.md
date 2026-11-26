# Overall Project Report

## Declaration: 
  - This FYP (Final Year Project) focuses on DevOps deplyment to Azure Services.
  - Due to school account bug, Brayden's account was shared between Richard and Amos.

## Services used: 
  - Platform: Github, Github Actions, Docker
  - Security: Sonar Cloud, Syntax
  - Azure Deployment: Azure Access Control (IAM), Azure Cost Analysis, Azure Container Registry, Azure SQL and Azure Web App, 

## About the Project:
This project aims to calculate a vehicle's carbon emissions based on the distance travelled.
Since it is a project design with a DevOps theme, the team decided to make a Web App.

### Project Planning and deficuties:


## Website
- **GitHub Pages (static website):** [Carbon Footprint Calculator](https://scip316.github.io/FYP_Carbon_Footprint/homepage.html)
- **Azure Web App** (**DEPRECATED**): [Previous deployment](https://fypprojectwebapp.azurewebsites.net)

# Contributors and their role

| Name | Roles |
| Brayden | Team lead, infrastructure and pipeline engineer |
| Amos | Test cases developer and Sonarcloud intergrations |
| Richard | Docker intergration  |
| JiChi | Web app developer, Syntax intergration
| Darrel | Project advior |

---
# Legacy Project Report before cleanup
This was the comments before project submission

## Planning and Setup
- Initial Setup
  - Set up GitHub repository.
  - Configure Visual Studio Code (VSCode) as your primary IDE.
  - Integrate CoPilot for AI-based code completion in VSCode.

- Environment Configuration
  - Configure Docker on your local machine.
  - Set up a Kubernetes cluster on Microsoft Azure or other preferred cloud service.
  - Install necessary CI/CD tools (GitHub Actions, SonarCloud).

- Development Phase
  - Feature Development
  - Implement the core features of the Sustainability Full Stack Application.
  - Utilize Feature-Driven Development practices to streamline the development process.
  - Develop individual features in separate branches and use GitHub pull requests for code reviews.

- Static Code Analysis
  - Integrate static code analysis tools with VSCode.
  - Configure SonarCloud for code inspection and quality gate checks.

- Testing Phase
  - Test Plan and Test Cases
  - Define test plans and test cases using Cucumber & Gherkin.
  - Add test cases to specific Jira stories.

- Automated Testing
  - Implement automated unit tests.
  - Configure GitHub Actions to run tests automatically on each commit.
  - Upload test results to Jira for Requirement Traceability Matrix.


## CI/CD Pipeline
- CI/CD Workflow Design
  - Design the End-to-End CI/CD workflow.
  - Implement GitHub Actions workflows for continuous integration and deployment.
  
- Containerization and Deployment
  - Containerize the application using Docker.
  - Push the Docker image to Docker Hub.
  - Deploy the application to a Kubernetes cluster.
  - Automate the deployment process using GitHub Actions.

- Security and Quality Assurance
  - Security Scanning
  - Integrate SAST (Static Application Security Testing) into the pipeline.
  - Automate security scans during the commit phase.
  
- Vulnerability Management
  - Analyze and report identified vulnerabilities.
  - Provide remediation steps and implement fixes.


## Documentation

- Technical Documentation
  - Prepare detailed technical documentation for the project.
  - Include workflow diagrams, release management processes, and CI/CD pipeline details.
  - Document how to use the application, CI/CD pipeline, and other relevant information.


## Final Review and Submission
- Final Review
  - Review all project deliverables.
  - Ensure all documentation is complete and accurate.
  - Perform final testing and quality checks.

Project Submission
- Submit the completed project, including the application, documentation, and all required deliverables.

---

Last check before Presentation Day
