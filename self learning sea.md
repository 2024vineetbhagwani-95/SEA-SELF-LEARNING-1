## **Self Learning Summary – Software Engineering and DevOps** 

## **1\. Introduction to DevOps**

DevOps is a software engineering approach that brings development and operations activities closer together. It focuses on collaboration, automation, continuous feedback, and faster delivery of reliable software.

In a conventional software environment, developers and operations teams may work independently, which can create delays and communication gaps. DevOps promotes shared responsibility throughout the software lifecycle.

### Major Advantages of DevOps

* Faster development: Changes can be developed and delivered more quickly.  
* Frequent releases: New features and bug fixes can reach users regularly.  
* Better reliability: Automated testing and standardized processes reduce errors.  
* Improved teamwork: Development, testing, operations and security teams collaborate closely.  
* Scalability: Automated infrastructure and deployment processes make it easier to handle growth.  
* Continuous security: Security checks can be incorporated into development and deployment activities.

DevOps commonly makes use of Continuous Integration (CI), Continuous Delivery (CD), automated testing, Infrastructure as Code, monitoring and logging.

# **2\. Agile and DevOps Comparison**

Although Agile and DevOps are closely related, they address different parts of the software delivery process.

| Aspect | Agile | DevOps |
| ----- | ----- | ----- |
| Main purpose | Manage iterative software development | Improve software delivery and operation |
| Main emphasis | Requirements, development and customer feedback | Automation, deployment and system reliability |
| Work pattern | Sprints and iterations | Continuous delivery |
| Important activities | Sprint planning, reviews and retrospectives | CI/CD, automated testing and monitoring |
| Team involvement | Developers, Product Owner and Scrum Master | Developers, Operations, QA and Security |
| Feedback | Usually obtained during or after iterations | Continuously through testing and monitoring |
| Common tools | Jira, Asana, Trello | Docker, Jenkins, GitHub Actions, Kubernetes |

### How Agile and DevOps Work Together

Agile provides a framework for developing software incrementally, whereas DevOps helps the organization deliver, deploy and maintain that software efficiently.

For example, an Agile team may complete a feature during a sprint. DevOps practices can then automatically build, test and deploy that feature.

Therefore, Agile and DevOps are complementary approaches rather than competing methodologies.

# **3\. JIRA and Asana – Case Study**

JIRA and Asana are both project management applications, but they are commonly used for different types of work.

### JIRA in Software Development

Consider a software company developing a mobile banking application. The development team can use JIRA to:

* Maintain the product backlog  
* Create user stories  
* Assign tasks to developers  
* Plan sprints  
* Track bugs  
* Monitor the progress of issues  
* Generate Agile reports

For instance, a requirement such as "The customer should be able to reset their password" can be entered as a user story. Developers and testers can then track the work through different stages.

### Asana in Business Projects

Consider a company organizing the launch of a new product. Its marketing team can use Asana to manage:

* Advertising campaigns  
* Content creation  
* Team responsibilities  
* Deadlines  
* Product launch activities  
* Marketing approvals

Tasks can be organized using lists, boards and timeline-based views.

| Parameter | JIRA | Asana |
| ----- | ----- | ----- |
| Primary usage | Software development | General project management |
| Agile features | Extensive | Available |
| Bug management | Strong | More task-oriented |
| Sprint management | Strong | Limited compared with JIRA |
| Cross-functional projects | Supported | Strong |
| Learning curve | Relatively higher | Generally easier |
| Best suited for | Development teams | Business and cross-functional teams |

# **4\. DevOps Lifecycle and JIRA Workflow**

## DevOps Lifecycle

DevOps follows a continuous cycle, where information from one stage is used to improve subsequent development activities.

### **Lifecycle**

**Plan → Develop → Build → Test → Release → Deploy → Operate → Monitor**

### Explanation

**Plan:**  Requirements are collected, analyzed and prioritized.

**Develop :** Programmers implement the required functionality and maintain the source code.

**Build :** The source code is converted into a deployable software package.

**Test** : The application is checked using automated and manual testing techniques.

**Release**: A stable version is approved for deployment.

**Deploy**: The application is moved to the required environment.

**Operate**: The deployed application is maintained and kept available to users.

**Monitor**: System performance, logs and errors are observed continuously.

The information obtained during monitoring can be used during the next planning cycle, making DevOps a continuous improvement process.

## **JIRA Issue Workflow**

A JIRA issue normally moves through a sequence of statuses as work progresses.

**Backlog → Selected → In Progress → Code Review → Testing → Completed**

For example:

* Backlog: Requirement has been identified but is not yet selected.  
* Selected: Work has been planned for execution.  
* In Progress: Developer is currently working on it.  
* Code Review: The implementation is being reviewed.  
* Testing: Testers verify whether the requirement works correctly.  
* Completed: The work has satisfied the required conditions.

JIRA workflows can be modified according to the needs of a particular project.

# **5\. User Stories and Acceptance Criteria**

A user story expresses a requirement from the viewpoint of the person who will use the system.

### Standard Format

As a \[type of user\], I want \[requirement\], so that \[reason/benefit\].

### Example:

### As a student, I want to download my examination timetable so that I can plan my preparation accordingly.

A well-written user story should provide clear value to the user and should be small enough to be developed and tested.

### INVEST Model

The quality of a user story can be evaluated using the INVEST principles:

* I – Independent  
* N – Negotiable  
* V – Valuable  
* E – Estimable  
* S – Small  
* T – Testable

## **Acceptance Criteria**

Acceptance criteria specify the conditions that must be satisfied before a user story can be considered successfully completed.

### Example

User Story:

> As a student, I want to receive my examination results online so that I do not have to visit the college office.

Acceptance Criteria:

1. The student must log in using valid credentials.  
2. The system should display the student's result after successful authentication.  
3. The result should contain marks and grades.  
4. Students with invalid credentials should receive an appropriate error message.  
5. The result should not be visible to unauthorized users.

# **6\. Advanced Requirement Elicitation Techniques**

Requirement elicitation is the process of identifying and understanding the requirements of stakeholders before and during software development.

Two useful advanced techniques are interviews and ethnographic observation.

## **A. Interviews**

Interviews involve directly communicating with stakeholders to discover their expectations and problems.

They can be:

* Structured: Fixed set of questions  
* Semi-structured: Planned questions with scope for discussion  
* Unstructured: Open-ended conversation

### Example

For a college management system, a requirements analyst may interview:

* Students  
* Faculty members  
* Administrative staff  
* Examination department personnel

This can reveal requirements related to attendance, examinations, notices and academic records.

### Advantages

* Direct interaction with stakeholders  
* Allows immediate clarification  
* Provides detailed information  
* Helps identify user expectations

### Disadvantages

* Can consume significant time  
* Stakeholders may provide incomplete information  
* Responses may be influenced by personal opinions

## **B. Ethnography**

Ethnography involves observing users while they perform their actual tasks in their normal environment.

For example, while developing software for a hospital, an analyst could observe how nurses:

* Record patient information  
* Check patient schedules  
* Update medical records  
* Communicate with doctors  
* Handle emergency situations

This may reveal practical requirements that users might not mention during a formal interview.

### Advantages

* Reveals actual user behaviour  
* Identifies hidden requirements  
* Helps understand real workflows  
* Detects manual workarounds

### Limitations

* Requires considerable time  
* Users may behave differently when being observed  
* Interpretation of observations can be subjective

A combination of interviews and observation generally gives a more complete understanding of requirements

# **7\. Requirement Traceability Matrix (RTM)**

A Requirement Traceability Matrix (RTM) is a document that connects software requirements with their corresponding design elements and test cases.

| Requirement ID | Requirement | Design Component | Test Case | Current Status |
| ----- | ----- | ----- | ----- | ----- |
| R-101 | Student registration | Registration Module | T-101 | Passed |
| R-102 | Student login | Authentication Module | T-102 | Passed |
| R-103 | View attendance | Attendance Module | T-103 | Passed |
| R-104 | Download timetable | Timetable Module | T-104 | In Testing |
| R-105 | Generate result | Result Module | T-105 | Planned |

# **8\. Requirement Management Tools**

Requirement management tools assist teams in documenting, organizing, tracking and controlling requirements throughout the software lifecycle.

Some examples are:

* IBM DOORS  
* JIRA  
* Jama Connect  
* Helix ALM  
* Siemens Polarion  
* Strictdoc

## **IBM DOORS**

IBM DOORS (Dynamic Object-Oriented Requirements System) is an enterprise-level requirements management solution designed for projects where requirements need to be carefully documented and traced.

It is particularly useful in complex and highly regulated domains such as:

* Automotive  
* Aerospace  
* Defense  
* Medical systems  
* Transportation

### **Important Capabilities**

* Requirements documentation  
* Hierarchical organization  
* Version management  
* Requirement relationships  
* Traceability  
* Change management  
* Impact analysis  
* Coverage reporting

For example, in an automotive project, a safety requirement can be linked to its system design, implementation and corresponding verification tests.

### **Limitations**

DOORS can involve:

* Higher complexity  
* Greater configuration effort  
* A steeper learning curve  
* Higher cost compared with simpler project management tools

# **Conclusion**

Software engineering requires proper coordination between requirements, development, testing and deployment. Agile provides an iterative method for developing software and responding to changing requirements, while DevOps extends collaboration into deployment and operations.

Tools such as JIRA and Asana help teams organize and monitor project work. Techniques such as interviews and ethnography help analysts understand stakeholder needs. User stories and acceptance criteria convert these needs into clear and testable requirements. Finally, RTM and requirement management systems such as IBM DOORS provide traceability and help ensure that requirements are properly implemented and verified.

Thus, effective requirement management combined with Agile and DevOps practices can improve software quality, collaboration, traceability and delivery speed.

### **References**

1. Amazon Web Services — *What is DevOps?*  
2. Atlassian — *Introduction to Jira*  
3. Atlassian — *Jira Software Documentation*  
4. Asana — *Getting Started with Asana*  
5. IBM — *Engineering Requirements Management DOORS Next Documentation*

