# Requirement-analysis
A detailed requirement analysis for a booking management system. This project simulates a real-world scenario by documenting and structuring software requirements to lay a clear foundation for successful development.
# What is Requirement Analysis?
Requirement analysis is the first step of the software development process and software development life cycle (SDLC).
It's all about understanding what software is supposed to do and the constraints it must operate within.
It is usually a technical process and a team effort where stakeholders and software developers determine the needs and conditions that a new or altered software product must meet. This process involves identifying, documenting, and analyzing these business requirements to ensure that they are clearly understood and feasible.
# Why is Requirement Analysis Important?
✅ Ensures Clear Understanding of Project Goals
Requirement analysis helps developers and stakeholders gain a shared understanding of what the software must do. It translates vague ideas into specific, actionable goals, reducing the risk of miscommunication or unmet expectations later in the project.

🛠 Guides Design and Development
It acts as a blueprint for the system's architecture and functionality. By clearly defining inputs, outputs, processes, and constraints, requirement analysis ensures that design decisions align with business needs and technical feasibility.

💰 Minimizes Costly Rework and Delays
Identifying and addressing issues early in the requirements phase is far less expensive than fixing them later during development or after deployment. A thorough analysis helps prevent scope creep, missed functionality, and project overruns.
#  Key Activities in Requirement Analysis.
1. Requirement Gathering
* Engage with stakeholders to collect initial requirements.
* Use various techniques like interviews, surveys, and workshops.
2. Requirement Elicitation
* Refine and elaborate on the gathered requirements.
* Use techniques like brainstorming, focus groups, and prototyping.
3. Requirement Documentation
* Document the requirements in a detailed and structured format.
* Use requirement specification documents, user stories, and use cases.
4. Requirement Analysis and Modeling
* Analyze and prioritize the requirements.
* Create models to visualize and understand the requirements.
5. Requirement Validation
* Review and validate the requirements with stakeholders.
* Define acceptance criteria and ensure traceability.
# Types of Requirements.
## Functional requirements.
1. Managers have a separate portal to access the data and update it.
2. Customers can search and book a hotel.
3. The Customer/Manager app sends the request to the load balancer and it distributes the request to booking management servers.
## Non-functional requirements.
1. Hotel service interacts with the Hotel DB cluster which follows the master-slave architecture to reduce the load in the database.
2. Whenever any data is updated in the database API sends the data to the CDN and to a Messaging Queue System for further processing.
3. Ensure data encryption, secure login, and protect against common vulnerabilities.
# Use Case Diagrams
* Use case diagrams show how different users (actors) interact with the system to achieve specific goals (use cases).
 ## Benefits of Use Case Diagrams:
- Provide a clear visual representation of system functionalities.
- Help in identifying and organizing system requirements.
- Facilitate communication among stakeholders and development team.


# Acceptance Criteria.
## Benefits of Acceptance Criteria:
Ensure all parties have a clear understanding of feature requirements.
Provide a basis for testing and validation.
Help in maintaining quality and meeting user expectations.
