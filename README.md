# Intro-to-Software-Development-Life-Cycle

## Table of Contents

- [SDLC Overview and Introduction](#SDLC-Overview-and-Introduction)
- [Popular SDLC models](#Popular-SDLC-models)
- [SDLC models](#SDLC-models)
- [What is Software Prototyping in SDLC?](#What-is-Software-Prototyping-in-SDLC?)


## SDLC-Overview-and-Introduction
•	Software Development Life Cycle (SDLC) is a process used by the software industry to design, develop and test high quality software.
•	The SDLC aims to produce a high-quality software that meets or exceeds customer expectations, reaches completion within times and cost estimates.
•	It is also called as Software Development Process.


### The Seven Phases of the SDLC
1. Requirements Analysis/Planning
The planning phase involves aspects of project and product management. This may include:
Resource allocation (both human and materials)
•	Capacity planning
•	Project scheduling
•	Cost estimation
•	Provisioning
The outputs of the planning phase include: project plans, schedules, cost estimations, and procurement requirements. Ideally, Project Managers and Development staff collaborate with Operations and Security teams to ensure all perspectives are represented.

2. Defining/Feasibility
The business must communicate with IT teams to convey their requirements for new development and enhancement. The requirements phase gathers these requirements from business stakeholders and Subject Matter Experts (SMEs.)
There are mainly five types of feasibility checks:
•	Economic: Can we complete the project within the budget or not?
•	Legal: Can we handle this project as cyber law and other regulatory framework/compliance.
•	Operation feasibility: Can we create operations which is expected by the client?
•	Technical: Need to check whether the current computer system can support the software
•	Schedule: Decide that the project can be completed within the given schedule or not.

3. Design and prototyping
Once the requirements are understood, software architects and developers can begin to design the software. The design process uses established patterns for application architecture and software development. Architects may use an architecture framework such as TOGAF to compose an application from existing components, promoting reuse and standardization.
Developers use proven Design Patterns to solve algorithmic problems in a consistent way. This phase may also include some rapid prototyping, also known as a spike, to compare solutions to find the best fit. The output of this phase includes:
•	Design documents that list the patterns and components selected for the project.
•	Code produced by spikes, used as a starting point for development.

4. Coding/Software development
This phase produces the software under development. Depending on the methodology, this phase may be conducted in time-boxed “sprints,” (Agile) or may proceed as a single block of effort (Waterfall.) Regardless of methodology, development teams should produce working software as quickly as possible.

5. Testing
The testing phase of the SDLC is arguably one of the most important. It is impossible to deliver quality software without testing. There is a wide variety of testing necessary to measure quality:
•	Code quality
•	Unit testing (functional tests)
•	Integration testing
•	Performance testing
•	Security testing
The best way to ensure that tests are run regularly, and never skipped for expediency, is to automate them. Tests can be automated using Continuous Integration tools, like Codeship, for example. The output of the testing phase is functional software, ready for deployment to a production environment.

6. Deployment
The deployment phase is, ideally, a highly automated phase. In high-maturity enterprises, this phase is almost invisible; software is deployed the instant it is ready. Enterprises with lower maturity, or in some highly regulated industries, the process involves some manual approvals. However, even in those cases it is best for the deployment itself to be fully automated in a continuous deployment model. Application Release Automation (ARA) tools are used in medium and large-size enterprises to automate the deployment of applications to Production environments.

7. Operations and maintenance
The operations and maintenance phase are the “end of the beginning,” so to speak. The Software Development Life Cycle doesn’t end here. Software must be monitored constantly to ensure proper operation. Bugs and defects discovered in Production must be reported and responded to, which often feeds work back into the process.


## Popular-SDLC-models
SDLC Models
This SDLC model is documentation-intensive, with earlier phases documenting what need be performed in the subsequent phases.

1. V-Model
The V-model is an SDLC model where execution of processes happens in a sequential manner in a V-shape. It is also known as Verification and Validation model.
•	The V-Model is an extension of the waterfall model and is based on the association of a testing phase for each corresponding development stage. This means that for every single phase in the development cycle, there is a directly associated testing phase. This is a highly-disciplined model and the next phase starts only after completion of the previous phase.

### V-Model - Design
Under the V-Model, the corresponding testing phase of the development phase is planned in parallel. So, there are Verification phases on one side of the ‘V’ and Validation phases on the other side.

### There are several Verification phases in the V-Model, each of these are explained in detail below.

•	Business Requirement Analysis
This is the first phase in the development cycle where the product requirements are understood from the customer’s perspective. This phase involves detailed communication with the customer to understand his expectations and exact requirement. This is a very important activity and needs to be managed well, as most of the customers are not sure about what exactly they need. The acceptance test design planning is done at this stage as business requirements can be used as an input for acceptance testing.

•	System Design
Once you have the clear and detailed product requirements, it is time to design the complete system. The system design will have the understanding and detailing the complete hardware and communication setup for the product under development. The system test plan is developed based on the system design. Doing this at an earlier stage leaves more time for the actual test execution later.

•	Architectural Design
Architectural specifications are understood and designed in this phase. Usually more than one technical approach is proposed and based on the technical and financial feasibility the final decision is taken. The system design is broken down further into modules taking up different functionality. This is also referred to as High Level Design (HLD).
The data transfer and communication between the internal modules and with the outside world (other systems) is clearly understood and defined in this stage. With this information, integration tests can be designed and documented during this stage.

•	Module Design
In this phase, the detailed internal design for all the system modules is specified, referred to as Low Level Design (LLD). It is important that the design is compatible with the other modules in the system architecture and the other external systems. The unit tests are an essential part of any development process and helps eliminate the maximum faults and errors at a very early stage. These unit tests can be designed at this stage based on the internal module designs.

2. Spiral Model
The spiral model is a risk-driven process model. This SDLC model helps the team to adopt elements of one or more process models like a waterfall, incremental, waterfall, etc. This model adopts the best features of the prototyping model and the waterfall model. The spiral methodology is a combination of rapid prototyping and concurrency in design and development activities.
The spiral model has four phases. A software project repeatedly passes through these phases in iterations called Spirals.
•	Identification
This phase starts with gathering the business requirements in the baseline spiral. In the subsequent spirals as the product matures, identification of system requirements, subsystem requirements and unit requirements are all done in this phase. This phase also includes understanding the system requirements by continuous communication between the customer and the system analyst. At the end of the spiral, the product is deployed in the identified market.
•	Design
The Design phase starts with the conceptual design in the baseline spiral and involves architectural design, logical design of modules, physical product design and the final design in the subsequent spirals.
•	Construct or Build
The Construct phase refers to production of the actual software product at every spiral. In the baseline spiral, when the product is just thought of and the design is being developed a POC (Proof of Concept) is developed in this phase to get customer feedback. Then in the subsequent spirals with higher clarity on requirements and design details a working model of the software called build is produced with a version number. These builds are sent to the customer for feedback.
•	Evaluation and Risk Analysis
Risk Analysis includes identifying, estimating and monitoring the technical feasibility and management risks, such as schedule slippage and cost overrun. After testing the build, at the end of first iteration, the customer evaluates the software and provides feedback.


3. Big bang model
Big bang model is focusing on all types of resources in software development and coding, with no or very little planning. The requirements are understood and implemented when they come. This model works best for small projects with smaller size development team which are working together. It is also useful for academic software development projects. It is an ideal model where requirements are either unknown or final release date is not given.

### Big Bang Model - Pros and Cons
The advantage of this Big Bang Model is that it is very simple and requires very little or no planning. Easy to manage and no formal procedure are required. However, the Big Bang Model is a very high-risk model and changes in the requirements or misunderstood requirements may even lead to complete reversal or scraping of the project. It is ideal for repetitive or small projects with minimum risks.

### The advantages of the Big Bang Model are as follows:
•	This is a very simple model
•	Little or no planning required
•	Easy to manage
•	Very few resources required
•	Gives flexibility to developers
•	It is a good learning aid for new comers or students.

### The disadvantages of the Big Bang Model are as follows:
•	Very High risk and uncertainty.
•	Not a good model for complex and object-oriented projects.
•	Poor model for long and ongoing projects.
•	Can turn out to be very expensive if requirements are misunderstood

4. Waterfall model
The waterfall is a widely accepted SDLC model. In this approach, the whole process of the software development is divided into various phases. In this SDLC model, the outcome of one phase acts as the input for the next phase.
Waterfall methodology begins with long planning and design phases. Once developed, the software then goes through phases of testing, and is finally deployed for use. Waterfall is considered by many to be too rigid to adapt to changing requirements. It does not support feedback throughout the process, leading to the implementation of requirements that may have changed during the development effort. This weakness in Waterfall led to the development of more flexible methodologies, such as Agile.



### Waterfall Model - Advantages
•	The advantages of waterfall development are that it allows for departmentalization and control. A schedule can be set with deadlines for each stage of development and a product can proceed through the development process model phases one by one.
•	Development moves from concept, through design, implementation, testing, installation, troubleshooting, and ends up at operation and maintenance. Each phase of development proceeds in strict order.
•	Some of the major advantages of the Waterfall Model are as follows −
•	Simple and easy to understand and use
•	Easy to manage due to the rigidity of the model. Each phase has specific deliverables and a review process.
•	Phases are processed and completed one at a time.
•	Works well for smaller projects where requirements are very well understood.
•	Clearly defined stages.
•	Well understood milestones.
•	Easy to arrange tasks.
•	Process and results are well documented.



## SDLC-models
Popular SDLC Models continued
5. Agile Model
Agile methodology is a practice which promotes continue interaction of development and testing during the SDLC process of any project. In the Agile method, the entire project is divided into small incremental builds. All of these builds are provided in iterations, and each iteration lasts from one to three weeks. The Manifesto for Agile Software Development was drafted and signed by a group of software developers in 2001. Reading the manifesto, you can see clearly the contrast between Waterfall, then the de-facto standard for development methods, and Agile, the newer method.

### Following are the Agile Manifesto principles
•	Individuals and interactions − In Agile development, self-organization and motivation are important, as are interactions like co-location and pair programming.
•	Working software − Demo working software is considered the best means of communication with the customers to understand their requirements, instead of just depending on documentation.
•	Customer collaboration − As the requirements cannot be gathered completely in the beginning of the project due to various factors, continuous customer interaction is very important to get proper product requirements.

•	Responding to change − Agile Development is focused on quick responses to change and continuous development.

### Agile Model - Pros and Cons
Agile methods are being widely accepted in the software world recently. However, this method may not always be suitable for all products. Here are some pros and cons of the Agile model.

### The advantages of the Agile Model are as follows:
•	Is a very realistic approach to software development.
•	Promotes teamwork and cross training.
•	Functionality can be developed rapidly and demonstrated.
•	Resource requirements are minimum.
•	Suitable for fixed or changing requirements
•	Delivers early partial working solutions.
•	Good model for environments that change steadily.
•	Minimal rules, documentation easily employed.
•	Enables concurrent development and delivery within an overall planned context.
•	Little or no planning required.
•	Easy to manage.
•	Gives flexibility to developers.

### The disadvantages of the Agile Model are as follows:
•	Not suitable for handling complex dependencies.
•	More risk of sustainability, maintainability and extensibility.
•	An overall plan, an agile leader and agile PM practice is a must without which it will not work.
•	Strict delivery management dictates the scope, functionality to be delivered, and adjustments to meet the deadlines.
•	Depends heavily on customer interaction, so if customer is not clear, team can be driven in the wrong direction.
•	There is a very high individual dependency, since there is minimum documentation generated.
•	Transfer of technology to new team members may be quite challenging due to lack of documentation.


## What-is-Software-Prototyping-in-SDLC?
What is Software Prototyping?
Prototype is a working model of software with some limited functionality. The prototype does not always hold the exact logic used in the actual software application and is an extra effort to be considered under effort estimation.
Prototyping is used to allow the users evaluate developer proposals and try them out before implementation. It also helps understand the requirements which are user specific and may not have been considered by the developer during product design.

### Following is a stepwise approach explained to design a software prototype.
•	Basic Requirement Identification
This step involves understanding the very basics product requirements especially in terms of user interface. The more intricate details of the internal design and external aspects like performance and security can be ignored at this stage.

•	Developing the initial Prototype
The initial Prototype is developed in this stage, where the very basic requirements are showcased and user interfaces are provided. These features may not exactly work in the same manner internally in the actual software developed. While, the workarounds are used to give the same look and feel to the customer in the prototype developed.

•	Review of the Prototype
The prototype developed is then presented to the customer and the other important stakeholders in the project. The feedback is collected in an organized manner and used for further enhancements in the product under development.

•	Revise and Enhance the Prototype
The feedback and the review comments are discussed during this stage and some negotiations happen with the customer based on factors like – time and budget constraints and technical feasibility of the actual implementation. The changes accepted are again incorporated in the new Prototype developed and the cycle repeats until the customer expectations are met.
Prototypes can have horizontal or vertical dimensions. A Horizontal prototype displays the user interface for the product and gives a broader view of the entire system, without concentrating on internal functions. A Vertical prototype on the other side is a detailed elaboration of a specific function or a sub system in the product.

### Software Prototyping - Types
•	Throwaway/Rapid Prototyping
Throwaway prototyping is also called as rapid or close ended prototyping. This type of prototyping uses very little efforts with minimum requirement analysis to build a prototype. Once the actual requirements are understood, the prototype is discarded and the actual system is developed with a much clear understanding of user requirements.
•	Evolutionary Prototyping
Evolutionary prototyping also called as breadboard prototyping is based on building actual functional prototypes with minimal functionality in the beginning. The prototype developed forms the heart of the future prototypes on top of which the entire system is built. By using evolutionary prototyping, the well-understood requirements are included in the prototype and the requirements are added as and when they are understood.
•	Incremental Prototyping
Incremental prototyping refers to building multiple functional prototypes of the various sub-systems and then integrating all the available prototypes to form a complete system.
•	Extreme Prototyping
Extreme prototyping is used in the web development domain. It consists of three sequential phases. First, a basic prototype with all the existing pages is presented in the HTML format. Then the data processing is simulated using a prototype services layer. Finally, the services are implemented and integrated to the final prototype. This process is called Extreme Prototyping used to draw attention to the second phase of the process, where a fully functional UI is developed with very little regard to the actual services.

•	Software Prototyping - Application
Software Prototyping is most useful in development of systems having high level of user interactions such as online systems. Systems which need users to fill out forms or go through various screens before data is processed can use prototyping very effectively to give the exact look and feel even before the actual software is developed.
Software that involves too much of data processing and most of the functionality is internal with very little user interface does not usually benefit from prototyping. Prototype development could be an extra overhead in such projects and may need lot of extra efforts.

### Best practices of Prototyping
•	You should use Prototyping when the requirements are unclear
•	It is important to perform planned and controlled Prototyping.
•	Regular meetings are vital to keep the project on time and avoid costly delays.
•	The users and the designers should be aware of the prototyping issues and pitfalls.
•	At a very early stage, you need to approve a prototype and only then allow the team to move to the next step.
•	In software prototyping method, you should never be afraid to change earlier decisions if new ideas need to be deployed.
•	You should select the appropriate step size for each version.
•	Implement important features early on so that if you run out of the time, you still have a worthwhile system.

### Advantages of the Prototyping Model
Here, are important pros/benefits of using Prototyping models:
•	Users are actively involved in development. Therefore, errors can be detected in the initial stage of the software development process.
•	Missing functionality can be identified, which helps to reduce the risk of failure as Prototyping is also considered as a risk reduction activity.
•	Helps team member to communicate effectively
•	Customer satisfaction exists because the customer can feel the product at a very early stage.
•	There will be hardly any chance of software rejection.
•	Quicker user feedback helps you to achieve better software development solutions.
•	Allows the client to compare if the software code matches the software specification.
•	It helps you to find out the missing functionality in the system.
•	It also identifies the complex or difficult functions.
•	Encourages innovation and flexible designing.
•	It is a straightforward model, so it is easy to understand.
•	No need for specialized experts to build the model
•	The prototype serves as a basis for deriving a system specification.
•	The prototype helps to gain a better understanding of the customer's needs.
•	Prototypes can be changed and even discarded.
•	A prototype also serves as the basis for operational specifications.
•	Prototypes may offer early training for future users of the software system.

### Disadvantages of the Prototyping Model
Here, are important cons/drawbacks of prototyping model:
•	Prototyping is a slow and time taking process.
•	The cost of developing a prototype is a total waste as the prototype is ultimately thrown away.
•	Prototyping may encourage excessive change requests.
•	Sometimes customers may not be willing to participate in the iteration cycle for the longer time duration.
•	There may be far too many variations in software requirements when each time the prototype is evaluated by the customer.
•	Poor documentation because the requirements of the customers are changing.
•	It is very difficult for software developers to accommodate all the changes demanded by the clients.
•	After seeing an early prototype model, the customers may think that the actual product will be delivered to him soon.
•	The client may lose interest in the final product when he or she is not happy with the initial prototype.
•	Developers who want to build prototypes quickly may end up building sub-standard development solutions.
