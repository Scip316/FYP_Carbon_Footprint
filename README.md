# Overall Project Report

## Declaration
- This FYP (Final Year Project) focuses on DevOps deployment to Azure Services.
- Due to a school account bug, Brayden's account was shared between Richard and Amos.

## About the Project
This project aims to calculate a vehicle's carbon emissions based on the distance travelled.
Since it is a project designed with a DevOps theme, the team decided to make a Web App and deploy it via pipeline.

## Website
- **GitHub Pages (static website):** [Carbon Footprint Calculator](https://scip316.github.io/FYP_Carbon_Footprint/homepage.html)
- **Azure Web App** (**DEPRECATED**): [Previous deployment](https://fypprojectwebapp.azurewebsites.net)

## Services Used
- Platforms and Tools: GitHub, GitHub Actions, GitHub Pages, Docker
- Code Quality and Security: SonarCloud, Snyk
- Azure Deployment: Azure Container Registry, Azure SQL, Azure Web App
- Azure Management: Azure Access Control (IAM), Microsoft Cost Management
-   
## Project Development Flow

### Phase 1: Development
- Without much DevOps or Deployment experience, the team focused on brainstorming what sort of app/service to make.
- Eventually, they settled on an Eco-Friendly theme, and hence developed the Carbon Emission Calculator.

### Phase 2: Pipeline Research
- While waiting for the application to be built, the team tried to explore how to deploy the web application.
- To gain insights into DevOps, they sought Darrel's advice, as he was in a DevOps Internship (I am the author of this).
- The team consulted Darrel (the author of this cleanup) to gain insights into DevOps, as he was doing a DevOps internship at the time.
- Throughout the project phase, they consulted Darrel, who suggested different types of services and gave reference links for deployment.

### Phase 3: Deployment
- After the research and trial and error, the team packaged the web application into a Docker image.
- They originally wanted to deploy to Vercel, but realised that it did not meet one of the FYP requirements.
- Eventually, they settled on Azure Free Trial to host their website.

---

# Contributors and their roles
| Name | Roles |
| --- | --- |
| Brayden | Team lead, infrastructure engineer, and pipeline engineer |
| Amos | Test case developer and SonarCloud integrator |
| Richard | Docker integrator |
| JiChin | Web app developer and Syntax integrator |
| Darrel | Project advisor |

---
# Legacy Project Report before cleanup (Made by the Team)
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
