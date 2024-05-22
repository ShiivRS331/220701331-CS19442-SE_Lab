# Team-12 : REConnect Messaging System
  - 220701301 - Tharun M
  - 220701307 - Umesh Subramanian
  - 220701313 - Veeraraghavan M
  - 220701319 - Vijai T
  - 220701325 - Vishnu Velavan
  - 220701331 - Shiiv R S

## Software Requirements Specifications (SRS)

### Introduction
The purpose of this project is to develop a messaging system website tailored for college use. This system aims to facilitate communication among students, teachers, and administrators by providing features such as messaging, announcement posting, and event creation.

### Functional Requirements
- **User Authentication:** Users must be able to sign up, log in, and log out securely.
- **Messaging/Chat Functionalities:** Enable one-on-one and group messaging.
- **Announcement Posting:** Allow teachers and administrators to post announcements.
- **Event Creation:** Enable users to create and manage events.
- **Profile Management:** Users can update their personal information and preferences.
- **Notification System:** Provide real-time notifications for messages, announcements, and events.

### Non-functional Requirements
- **Performance:** The system should handle up to 500 concurrent users without significant delay.
- **Scalability:** The system must be scalable to accommodate future growth in user numbers.
- **Security:** Implement robust security measures to protect user data and privacy.
- **Usability:** The interface should be intuitive and easy to navigate for both teachers and students.
- **Reliability:** Ensure high availability and minimal downtime.

### System Architecture
- **Database:** Use a relational database to store user data, messages, announcements, and events.
- **Servers:** Implement a multi-tier architecture with separate servers for the database, application logic, and frontend.
- **Communication Protocols:** Use HTTPS for secure data transmission and WebSockets for real-time messaging.

### User Interface
- **Teachers:** Interface should include tools for posting announcements, creating events, and managing classes.
- **Students:** Interface should focus on messaging, viewing announcements, and participating in events.

### External Interfaces
- **Email Services:** Integrate with third-party email services to send notifications and password reset emails.
- **Calendar Integration:** Optionally integrate with calendar services for event reminders.

### Testing Requirements
- **Unit Testing:** Test individual components for correct functionality.
- **Integration Testing:** Ensure that different modules work together seamlessly.
- **User Acceptance Testing (UAT):** Validate the system's functionality with actual users.
- **Performance Testing:** Measure system performance under various conditions.
- **Security Testing:** Identify and fix vulnerabilities.

### Constraints
- **Budget:** The project must be developed within the allocated budget.
- **Time:** The system should be ready for deployment within six months.
- **Compatibility:** Ensure compatibility with major browsers and mobile devices.

### Timeline
1. **Requirement Analysis:** 2 weeks
2. **Design:** 3 weeks
3. **Development:** 3 months
4. **Testing:** 1 month
5. **Deployment:** 2 weeks
6. **Maintenance:** Ongoing

## Agile Scrum

### Product Backlog
- User Authentication
- Messaging System
- Announcement Feature
- Event Management
- Profile Management
- Notification System
- User Interface Design
- Security Implementations
- Performance Optimization
- Integration with Email Services

## Use Case Diagram

![use case diagram](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/image%20(1).png?raw=true)

## Class Diagram
![class diagram](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/class%20diag.png?raw=true)

## Sequence Diagrams
![sequence diagram 1](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/seq%20diag1.png?raw=true)
![sequence diagram 2](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/seq%20diag2.png?raw=true)

## Assignment 4 - Sprints using Devops 
![us1](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/us1.png?raw=true)
![us2](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/us2.png?raw=true)
![us3](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/us3.png?raw=true)
![us4](https://github.com/ShiivRS331/Team-12---REConnect-Messaging-System/blob/main/images/us4.png?raw=true)

## CI/CD Pipelines using Azure DevOps

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
