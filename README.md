[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15248531&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
It deals with the design, development, testing, and maintenance of software applications.

What is software engineering, and how does it differ from traditional programming?
Software engineering involves a more structured and organized software development process that includes requirements engineering, design, coding, testing, and maintenance whereas traditional programming is less structured and confined to writing and testing code
Software Development Life Cycle (SDLC):
The Software Development Life Cycle (SDLC) is a software development framework that involves a structured process used by software engineers and developers to design, develop, test, deploy, and maintain high-quality software systems. It consists of several phases, each with its own set of activities and deliverables

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Requirements Gathering: During this initial phase, stakeholders' needs and requirements are identified and documented. This involves gathering input from end-users, clients, and other stakeholders to understand the desired features, functionalities, and constraints of the software.

Analysis: Once the requirements are gathered, they are analyzed to ensure they are clear, complete, and feasible. Any ambiguities or inconsistencies are addressed, and a detailed understanding of the system's scope is established.

Design: In this phase, the software architecture and design are developed based on the requirements gathered during the previous phases. This involves creating detailed technical specifications, defining the system's structure, components, interfaces, and data models.

Implementation: The actual coding and programming of the software are done in this phase. Developers write the source code according to the design specifications, using appropriate programming languages, frameworks, and development tools.

Testing: Once the code is written, it undergoes rigorous testing to identify and fix defects, ensure that it meets the specified requirements, and verify its overall quality. Testing can include various techniques such as unit testing, integration testing, system testing, and acceptance testing.

Deployment: After the software has been thoroughly tested and validated, it is prepared for deployment to end-users. This involves packaging the software, creating installation packages, and configuring the necessary hardware and software environments for deployment.

Maintenance: Once the software is deployed, it enters the maintenance phase, where it is continuously monitored, supported, and updated as needed. This includes fixing bugs, addressing user feedback, implementing enhancements, and adapting the software to changes in the environment or requirements.
Agile vs. Waterfall Models:
 Waterfall methodology is a well-established project management workflow where each process phase cascades downward sequentially through five stages while agile methodology prioritizes cross-functional collaboration and continuous improvement.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
The waterfall method is designed for long-term projects with predetermined timelines. The project is completed linearly, with each phase dependent on the previous one. Agile, however, uses short iterations to deliver value rapidly, allowing teams to adjust plans over time and achieve shorter time frames.
Requirements Engineering:
Requirements Engineering is the process of identifying, eliciting, analyzing, specifying, validating, and managing the needs and expectations of stakeholders for a software system.

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
1. Feasibility Study
The feasibility study mainly concentrates on below five mentioned areas below. Among these Economic Feasibility Study is the most important part of the feasibility analysis and the Legal Feasibility Study is less considered feasibility analysis. 


2. Requirements Elicitation
It is related to the various ways used to gain knowledge about the project domain and requirements. The various sources of domain knowledge include customers, business manuals, the existing software of the same type, standards, and other stakeholders of the project. The techniques used for requirements elicitation include interviews, brainstorming, task analysis, Delphi technique, prototyping, etc. Some of these are discussed here. Elicitation does not produce formal models of the requirements understood. Instead, it widens the domain knowledge of the analyst and thus helps in providing input to the next stage. 


3. Requirements Specification
This activity is used to produce formal software requirement models. All the requirements including the functional as well as the non-functional requirements and the constraints are specified by these models in totality. During specification, more knowledge about the problem may be required which can again trigger the elicitation process. The models used at this stage include ER diagrams, data flow diagrams(DFDs), function decomposition diagrams(FDDs), data dictionaries, etc. 



4. Requirements Verification and Validation
Verification: It refers to the set of tasks that ensures that the software correctly implements a specific function. 

Validation: It refers to a different set of tasks that ensures that the software that has been built is traceable to customer requirements. If requirements are not validated, errors in the requirement definitions would propagate to the successive stages resulting in a lot of modification and rework. The main steps for this process include:

5. Requirements Management
Requirement management is the process of analyzing, documenting, tracking, prioritizing, and agreeing on the requirement and controlling the communication with relevant stakeholders. This stage takes care of the changing nature of requirements. It should be ensured that the SRS is as modifiable as possible to incorporate changes in requirements specified by the end users at later stages too. Modifying the software as per requirements in a systematic and controlled manner is an extremely important part of the requirements engineering process.
Software Design Principles:
1. Maintainability: By adhering to design principles, developers can create software that is easier to maintain, modify, and troubleshoot. This reduces the time and effort required for bug fixes, updates, and enhancements.
2. Scalability: Good architecture design ensures that software can accommodate growth and increased demand without significant rework or performance degradation. This allows the software to serve more users and handle more data efficiently.
3. Reusability: Design principles encourage the creation of modular and reusable components. This promotes efficiency by allowing developers to leverage existing code, reducing the need to write redundant or duplicate functionality.
4. Flexibility: A well-designed software architecture allows for easy adaptation to changing requirements, technologies, or business needs. This enables developers to quickly respond to market changes and stay competitive.
5. Readability: By following design principles, code is more organized, coherent, and easier to understand. This not only benefits the original developers but also makes it easier for new team members to contribute to the project.
6. Collaboration: A well-structured software architecture facilitates teamwork by providing clear boundaries and responsibilities for different components. This promotes parallel work and efficient communication among team members.

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity in computing and programming refers to dividing a system into separate modules or components.
It simplifies design, development, testing, and maintenance by allowing you to focus on one part at a time without affecting the rest of the system.
Testing in Software Engineering:
software testing is a process of analyzing an application's functionality as per the customer prerequisite

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
Unit Testing: In this type of testing, errors are detected individually from every component or unit by individually testing the components or units of software to ensure that they are fit for use by the developers. It is the smallest testable part of the software.
Integration Testing: In this testing, two or more modules which are unit tested are integrated to test i.e., technique interacting components, and are then verified if these integrated modules work as per the expectation or not, and interface errors are also detected.
System Testing: In system testing, complete and integrated Softwares are tested i.e., all the system elements forming the system are tested as a whole to meet the requirements of the system.
Acceptance Testing: This is a kind of testing conducted to ensure that the requirements of the users are fulfilled before its delivery and that the software works correctly in the user’s working environment.

Version Control Systems:
Version control systems are software tools that help software teams manage changes to source code over time.
What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Version control systems are software tools that help software teams manage changes to source code over time.
Git.
Popular features on Git; Tracks history.
Free and open source.
Supports non-linear development.
Creates backups.
Scalable.
Supports collaboration.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Preparing project proposals and discussing potential projects with clients and stakeholders
Facilitating project initiation by defining project scope and requirements, and preparing the necessary documents and requirements
Developing project plans and timelines to ensure the timely submission of project deliverables
Managing project budgets and resources to ensure the timely completion of milestones
Tracking and documenting progress and communicating project status updates to key stakeholders

Ensuring software quality standards are met and requirements are submitted within budget and on time
Closing the project and ensuring proper documentation
Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Software Maintenance refers to the process of modifying and updating a software system after it has been delivered to the customer.
The importances are;
Increased data security. Thanks to software maintenance, reengineering data, bug fixing, and encoding constraints become easier, preventing the solution from being vulnerable. ...
Improved performance and efficiency. ...
Seamless project continuity. ...
Lower long-term total cost of ownership
Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
1. Wrong Priorities
A lot of software engineering teams devote too much time to creating new features and improving the functionality of their products. However, they typically make the mistake of neglecting to customize and improve the existing functions
2. Weak security
The software industry is prone to security issues. Developers need further education to learn and implement proper security practices
3. Unethical data collection
With the shift to digital marketing, companies are exponentially valuing user data. It’s an important source to use in development.

WORKS CITED
“Springer - International Publisher Science, Technology, Medicine.” Www.springer.com, www.springer.com.
“Geeksforgeeks.com.” Geeksforgeeks.com, 2020, www.geeksforgeeks.com.
W3Schools. “W3Schools Online Web Tutorials.” W3schools.com, 2019, www.w3schools.com.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
