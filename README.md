# Team-12 : REConnect-Messaging-System
  - 220701301 - Tharun M
  - 220701307 - Umesh Subramaniyam
  - 220701313 - Veeraraghavan M
  - 220701319 - Vijai T
  - 220701325 - Vishnu Velavan
  - 220701331 - Shiiv R S

## Assignment 1 - SRS, Agile sprints and use cases

![use case diagram](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/image%20(1).png?raw=true)

## Assignment 2 - Class Diagram
![class diagram](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/class%20diag.png?raw=true)

## Assignment 3 - Sequence Diagrams
![sequence diagram 1](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/seq%20diag1.png?raw=true)
![sequence diagram 2](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/seq%20diag2.png?raw=true)

## Assignment 4 - Sprints using Devops 
![us1](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/us1.png?raw=true)
![us2](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/us2.png?raw=true)
![us3](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/us3.png?raw=true)
![us4](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/us4.png?raw=true)

## Assignment 5 - CI/CD Pipelines using Azure DevOps

### Continuous Integration (CI)

#### Code Repository
Store your code in repositories like GitHub. Azure DevOps seamlessly integrates with GitHub.

#### Build Pipelines
Create a build pipeline in Azure Pipelines that is triggered whenever the main branch is updated.

#### Build Stages
Define stages for different tasks in the pipeline.

#### Get Sources
Use tasks to fetch the latest code from the Git repository.

#### Build
Use programming language-specific tasks to build the application.

#### Unit Tests
Integrate unit testing into the pipeline to ensure the functionality of the code.

#### Code Coverage
Include tasks to measure code coverage using testing frameworks.

#### Publish Artifacts
After the build is successful, publish the artifacts (output of the build process) for deployment.

### Continuous Deployment (CD)

#### Release Pipeline
Create a release pipeline to deploy the built artifacts to different environments.

#### Environments
Set up environments in Azure DevOps using deployment groups.

#### Deployment Stages
Define different stages in the deployment pipeline such as:

- Pre-deployment (e.g., running additional tests)
- Deployment
- Post-deployment (e.g., monitoring)

#### Approval Gates
Add approval gates before deploying to production environments. This allows for manual approvals before pushing changes to production.
