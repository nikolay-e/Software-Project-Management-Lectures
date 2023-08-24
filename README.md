# Software Project Management

## Foundations & Processes

### Foundations of Project Management

Why do only 2% of great projects succeed? Analyzing Success and Failure Factors:

- **Success Factors**
  - User Involvement: It is crucial to have continuous engagement with users to understand their needs and expectations.
  - Executive Management Support: Upper management's involvement is pivotal to allocate necessary resources and aid decision-making processes.
  - Clear Statement of Requirements: Detailed and explicit project requirements minimize misunderstanding and ensure everyone is on the same page.
- **Failure Factors**
  - Lack of User Involvement: Without user feedback, the final product might not meet expectations or solve the right problems.
  - Lack of Executive Support: Without leadership backing, projects often face resource shortages and decision-making issues.
  - Incomplete Requirements: Ambiguous or incomplete requirements often lead to incorrect solutions and unnecessary revisions.

A Project is:

- Temporary: having a defined start and end date.
- Unique: resulting in a distinctive product or service.
- Constrained: operates under limited resources, such as budget, time, or staff.
- Planned, executed, and controlled.
- Each project has its unique organization.
- Performed by people.

Kinds of projects (note that these categories often overlap):

- Order project: Development is done by an external client; conflicts are usually resolved in court.
- Internal development project: The client and developers belong to the same organization; conflicts are resolved by a top-level manager.
- Product development project: The client is often the internal marketing division. The product is offered and sold by the company, and the funds are drawn from a **global development budget**.

Project management is: The application of knowledge, skills, tools, and techniques to project activities to meet project requirements.

- Project management applies process management.
- Project management creates product management.
- Process management influences product management.

**Tasks of Project Management:**

- **Project Planning: Outlining project goals, defining tasks, allocating resources, and creating timelines.**
- **Project Monitoring and Controlling: Ensuring the project stays on course and adjusting as necessary.**
- **Stakeholder Management: Maintaining strong relationships with all stakeholders and managing their expectations.**
- **Risk Management: Identifying, assessing, and managing potential risks.**
- **Project Organization: Structuring project teams and defining roles and responsibilities.**
- **Team Management: Leading and guiding the team to meet project goals.**

Knowledge Areas of project management:

- Risk Management
- Cost Management
- Communications Management
- Time Management
- Human Resource Management

Skills of a Project Manager:

- Project Management Abilities: Planning, estimating, negotiating, and time management.
- Leadership Abilities: Communication, delegation, motivation, and moderation.
- Personal Abilities: Responsibility, patience, and fairness.
- Technical Abilities: Economical understanding, application knowledge, and software-engineering proficiency.

### Software Development Process Models

#### Definitions

**Process: A sequence of actions that together accomplish a particular outcome or result.**

**Software Development Process: A methodology for transforming user needs into a functional software product.**

**It typically consists of the following stages:**

    1. **Identifying and understanding user needs.**
    2. **Translating these needs into software requirements.**
    3. **Transforming the software requirements into a detailed design.**
    4. **Implementing this design into code.**
    5. **Testing the code to ensure that it meets the requirements.**

**Software Process Model: An abstract representation of a software process that serves as a template for conducting software development activities. Key components of a software process model include phases, activities, artifacts, and roles.**

#### Fundamental Development Approaches

##### Code and Fix

This approach involves writing code and fixing errors iteratively, with ad-hoc testing being the primary method of error detection.

Drawbacks include potential deviations from intended functionality, high costs associated with frequent corrections, and lack of documentation for crucial concepts and decisions.

##### Waterfall Model

The waterfall model describes a linear approach to software development where activities are performed in sequence with little to no iteration. If errors are detected, the process returns to the corresponding activity to rectify the issue.

Assumptions of the waterfall model include:

- Requirements are fully defined before design begins.
- Requirements are stable and unlikely to change significantly.
- Users have a clear understanding of what they want and don't need iterative visualization of the system.
- The system's complexity is manageable.

Potential pitfalls:

- Users may struggle to define all requirements upfront.
- A functional version of the system is not available until late in the project, making late detection of significant issues potentially catastrophic.

##### Spiral Model

- The spiral model emphasizes risk management throughout the software development process.
- The primary goal is to identify and manage development risks as early as possible. 
- The process repeats the following cycles until the project is completed or fails:
  1. Identify all potential risks (e.g., are all requirements defined?). If there are no risks, the project is considered complete.
  2. Prioritize these risks to focus on the most critical ones.
  3. Develop and implement a strategy to mitigate the highest priority risk. If the risk cannot be mitigated, the project may be deemed a failure.

##### Incremental Development

Incremental development is a methodology that breaks the software development process into smaller, manageable chunks, also known as increments. In this approach, we don't strive to develop the entire system at once, but rather, we implement increments, with each increment meeting a defined set of requirements. This allows the software to evolve, as opposed to being produced in one large, overwhelming effort.

Key points of Incremental Development include:

- Software evolution: Given enough time for the evolutionary process, the software has the potential to improve continually.
- Stability focus: This approach ensures attention to stability since only a stable foundation can support the continuous addition of increments.

##### Iterative Development

Iterative development is a controlled, cyclic process involving continuous revisions of the software. This aims at early error correction and integration of improvements. It works on several assumptions, which challenge traditional project management paradigms:

- Requirements are not completely definable or consistent from the start.
- The usage of the software, over time, alters the requirements of the software.
- Maintenance activities are not separate but are integrated into the development process.

Key benefits of an Iterative Development process include:

- Flexibility to changing requirements: Recognizes that as much as 40% of final requirements may arise after the analysis phase, even when development has already begun.
- Early risk mitigation: By dividing the system into smaller projects and addressing riskier elements first, it mitigates potential risks.
- Incremental progress: Promotes the "plan a little, design a little, and code a little" strategy, aiding in effective project management.
- Early involvement: Encourages all participants, including testers, integrators, and technical writers, to be involved earlier in the process.
- Early error correction: By revisiting each segment of the project, it allows for the identification and rectification of errors at earlier stages.

##### Prototyping

**A prototype is a preliminary version of a system that serves as a model for later stages or the final version. Prototyping, in turn, is a development technique that helps gather user feedback, assess feasibility, or investigate timing and other critical issues.**

**Prototyping is a methodology that relies on the creation of a preliminary model (or prototype) of the software. This facilitates user feedback, feasibility checks, and other important considerations in support of the development process.**

Key aspects of Prototyping include:

- Core Idea: It's often easier to refine a system's design based on a similar, existing system than to specify its requirements abstractly. The insights gained from building a prototype can greatly aid the final system's development.
- Types of prototypes: 
  - Presentation Prototype: Supports project initiation, convincing clients of feasibility and alignment with user requirements.
  - Functional Prototype: Illustrates specific user interface aspects or part of the functionality, aiding in problem clarification.
  - Breadboard: Models a critical technical aspect of the final system, evaluated by developers.
- Approaches to Prototyping: 
  - Exploratory Prototyping: Ideal when the problem is unclear, as initial ideas can be used to clarify user and management requirements.
  - Experimental Prototyping: Focuses on the technical implementation of a development goal, allowing users to refine their ideas about the required computer support through experimentation.
  - Evolutionary Prototyping: An ongoing process for adapting an application system to rapidly changing organizational constraints.

## Traditional and Agile Development Models

### Rational Unified Process (RUP)

RUP, a software development process framework, forms the backbone of our lecture today. It delineates the different development stages and disciplines, which are executed across each phase in an iterative and incremental approach.

- **Features:**
  - It promotes iterative and incremental software development.
  - Primarily assumes an object-oriented architecture and implementation, utilizing Unified Modelling Language (UML) wherever applicable.

- **Phases:**
  1. **Inception:** The initial phase dedicated to defining the scope and business case of the project.
     - *Tasks:* Identifying all major use cases, conducting risk analysis, defining success criteria (final project deliverables), determining required resources, and setting milestones.
     - *Results:* Scope definition, the formulation of important requirements, initial project plan (including milestones, cost estimation, project deliverables), and a glossary.
  
  2. **Elaboration:** This phase revolves around project planning, understanding the domain, and setting the architecture.
     - *Tasks:* Detailing use cases, identifying and articulating non-functional requirements, designing top-level architecture, creating initial prototypes, and refining the project plan.
     - *Results:* Extended use case model (which includes 80% of the documented and reviewed use cases, 80% complete model with non-functional requirements), top-level architecture, prototypes, revised project plan, and selected development technology.
  
  3. **Construction:** The phase dedicated to building the product.
     - *Tasks (Iteratively performed):* Selecting and implementing use cases (reformulate use case and architecture if needed), testing the resulting system.
     - *Results:* Tested system release, user documentation, system documentation of the release.
  
  4. **Transition:** This phase involves deploying the system in its operational environment.
     - *Tasks:* Transferring the system to the user (may involve installation, support, maintenance, integration with existing systems).
     - *Results:* The final, fully operational system.

- **Benefits:**
  - It is well-known, facilitating experience exchange.
  - Promotes clearer and more accurate requirements.
  - Enhances predictability.
  - Excellent documentation of the process (including individual tasks, results of each phase).

- **Challenges:**
  - Being a large model, it may be difficult to apply and customize onto specific projects.
  - Might lead to over-documentation due to the multitude of created artifacts that need documenting.
  - The definition of the process is subject to change as RUP continues to evolve.
  - The process suggests that software can be successfully developed by performing activities in a prescribed order, which may not always be the case.

### Agile Development

**Agile development is a contemporary approach to software development, characterized by its focus on frequent inspection and adaptation, iterative development, and incremental deliveries. The agile development process encourages the evolution of requirements and solutions through consistent collaboration within cross-functional teams and through continuous stakeholder feedback.**

Key Agile principles include:

- Continuous Delivery: Agile teams focus on frequent and regular release of usable software to end-users.
- Measure of Progress: In Agile, progress is mainly evaluated by the working software rather than traditional methods such as Gantt charts.
- Welcome Changing Requirements: Agile methods embrace changes, even late in development, to provide the customer with a competitive advantage.
- Self-Organizing Teams: Agile methodology encourages teams to self-organize and decide how best to accomplish their work, rather than being directed by others.

### Extreme Programming (XP)

Extreme Programming (XP) is a type of Agile methodology that emphasizes customer satisfaction and enhances software quality and responsiveness to changing customer requirements.

XP involves practices such as:

- **Planning Game**: Customers decide the scope and timing of releases based on estimates made by programmers. Only functionality demanded by the current iteration's stories is implemented by programmers.
- **Small Releases and Short Release Cycles**: Releases occur frequently, ranging from daily to monthly cycles.
- **Metaphor**: This practice encourages the use of clear and consistent naming conventions for classes, making it easier for customers, programmers, and managers to understand the system.
- **Simple Design**: Emphasizes the removal of code duplication and the minimization of classes and methods.
- **Test-Driven Development**: Programmers write unit tests while customers write functional tests.
- **Refactoring**: This involves making changes that do not alter system behavior but enhance code quality. It is necessary as the system evolves over time.
- **Pair Programming**: All code is written by two people at one screen, promoting knowledge sharing and code quality.
- **Continuous Integration**: The code is integrated frequently, ideally daily.
- **On-Site Customer**: A customer sits with the team full-time, facilitating quick feedback and decisions.
- **Collective Ownership**: Every programmer can improve any code anywhere in the system at any time.
- **Coding Standards**: All team members adhere to agreed coding practices.
- **40-Hour Weeks**: The team avoids overworking by restricting to a maximum of 40 hours a week.

XP roles include:

- **Customer**: The customer takes business decisions and is actively engaged in the project as part of the team.
- **Developer**: All team members who realize stories identified by the customer.
- **Tracker**: The tracker collects relevant metrics necessary to monitor project progress.
- **Coach**: An outside consultant who has previous XP experience and helps mentor the team members.

Prerequisites for implementing XP:

- The development team is co-located.
- All developers can communicate with each other, ideally limiting the team size to 10-15 persons.
- The chosen programming language should facilitate the writing of readable code.
- The customer should be available throughout the project's duration.
- Developers, managers, and customers must be convinced of the benefits of using XP.

Benefits of Extreme Programming:

- It accommodates changing requirements effectively.
- A usable version of the system is developed very early in the project lifecycle, allowing for early feedback and corrections.

### Scrum

**Scrum is an iterative project management framework commonly used in agile development. In this model, a team selects development tasks from a product backlog and aims to complete them within a predetermined time frame, usually a few weeks (known as a 'Sprint').**

##### Scrum Values

- **Commitment**: Every team member is personally dedicated to achieving the goals set for the team.
- **Courage**: Team members should be brave enough to tackle challenging issues and always strive to do what's right.
- **Focus**: Members should concentrate on the work allocated for the sprint and align their efforts towards team goals.
- **Openness**: Transparency is crucial. Team members and stakeholders should be open about the work being done and the challenges encountered.
- **Respect**: Every team member should respect each other's abilities and independence.

##### Scrum Principles

- **Transparency**: Each team member should be aware of their colleagues' work and progress.
- **Inspection**: Regular check-ins allow the team to reflect on progress and make necessary adjustments.
- **Adaption**: The team should continually assess their methods and revise elements that do not seem to be working effectively.

##### Scrum Events

- **Sprint Planning**: A negotiation session where the product owner and team agree on the set of features to be developed in the next sprint. The team estimates the effort required.
- **Daily Scrum**: A quick, 15-minute meeting where team members recap their work, discuss any problems, and share their tasks for the day.
- **Sprint Review**: After each sprint, the team presents the completed features to the product owner, who then accepts or rejects them based on their alignment with the initial sprint backlog.
- **Sprint Retrospective**: A post-sprint meeting where the team discusses potential improvements for future sprints.

##### Scrum Roles

- **Product Owner**: Represents all stakeholders and understands both technical and business requirements. The product owner maintains the product backlog, determines what features should be developed next, and decides whether to accept or reject the completed features.
- **Scrum Master**: Ensures that the scrum process is performed correctly. The Scrum Master supports both the team and the product owner and helps the team improve their processes and skills.
- **Development Team**: This self-organized, interdisciplinary team estimates the development effort for each feature. There is no designated team leader.

##### Scrum Artifacts

- **Product Backlog**: A comprehensive list of all product features and changes, estimated in terms of story points or person-hours/days.
- **Sprint Backlog**: Contains features to be developed in one sprint, agreed upon in the sprint planning meeting. This list is more detailed than the product backlog.
- **Product & Sprint Burndown Charts**: These visual aids help monitor the progress of the sprint and the overall project.
- **Release Plan**: Defines the number of sprints and the deliverables for each working release.

##### Scaling Scrum

To scale Scrum for larger teams, the larger group is divided into agile teams, each performing their own Scrum lifecycle. Each team selects a representative who participates in a 'Scrum of Scrums' meeting with representatives from other teams. The Scrum of Scrums has its own backlog.

##### Common Scrum Pitfalls

- The Scrum Master acting as a traditional project manager, planning and controlling tasks, and making decisions for the team.
- The Scrum Master acting as a mediator rather than a facilitator.
- One team member dominating the group.
- The Product Owner dictating activities and being frequently unavailable.
- User stories being too vague or large, making them difficult to estimate and complete within a sprint.

### Kanban

**Kanban is another Agile framework which focuses on visualizing the workflow, limiting work-in-progress (WIP), and improving efficiency through continuous incremental updates.**

- **Visual Workflow**: This involves dividing the work into manageable pieces, with each piece represented on a card and placed on a Kanban board. The board has columns, each representing a stage of the work process. This visual system makes it easy to understand what work needs to be done, who is doing what, and where bottlenecks are occurring.

- **Limit Work in Progress**: An integral part of Kanban is limiting the amount of work in progress. This limitation encourages focus and reduces the time spent on task-switching. If a work item is large or complex, it can be broken down into smaller, manageable tasks.

- **Measure Lead Time**: Lead time, the time it takes for a task to move from start to finish, is a key metric in Kanban. By measuring and optimizing lead time, teams can better predict delivery and improve their overall efficiency.

- **Manage Flow**: In Kanban, the goal is to create a steady and sustainable workflow that delivers maximum value. By identifying and addressing bottlenecks, teams can ensure that work flows smoothly and efficiently across the system.

Kanban is applicable in a variety of settings, particularly in environments where work arrives in an unpredictable manner or where it is desirable to deploy work items as soon as they are ready. Like other Agile methodologies, Kanban promotes continuous improvement and adaptability, making it a valuable tool in the ever-evolving field of software project management.

## Starting a Project

### Project Preparation & Initiation

#### The Project Preparation Phase

The Project Preparation phase precedes the actual project commencement, focusing on the critical decision of whether to initiate the project or not.

Tasks of the Project Preparation phase include:

- Definition of project goals, objectives, and expected deliverables.
- Identification of potential risks, underlying assumptions, and existing constraints.
- Preliminary estimation of project costs and time requirements.
- Creation of the project definition document.
- Making the crucial go/no-go decision.

Key aspects of the preparation phase are:

- Scope: Defines what is and what is not included in the project.
- Assumptions: These are factors considered to be true, real, or certain.
- Constraints: These are factors that limit the project team’s options.
- Completion Criteria: These are explicit deliverables (defined by the customer) that must be attained. They act as a communication tool between stakeholders, establishing a mutual agreement on when a deliverable is considered complete.

**The project definition includes elements such as:**
- **Completion Criteria**
- **Goals and Objectives**
- **Budget and schedule**
- **Project definition charter**
- **Defined roles and responsibilities**
- **Identified constraints, assumptions, and risks**
- **Project scope and deliverables**

#### (Project) Goals

A project goal encapsulates everything the project aims to produce and deliver. It represents an abstract or high-level statement that aligns with the broader business goals. All stakeholders must participate in the goal-setting process. Given that stakeholders' expectations and needs can vary significantly, goal contradictions may occur. It's essential for the project manager to detect and resolve these contradictions to ensure all goals are achievable.

Key points about project goals:

- Goals must be documented in the project definition.
- Goals can be defined following the SMART criteria - Specific, Measurable, Achievable, Relevant, and Time-bound.
- Goals can also be clarified through non-goals, e.g., "We do not maintain reusable components!".

An objective represents a more granular, lower-level statement describing specific deliverables included in the project.

A deliverable, whether tangible (like a product or component) or intangible (such as increased reputation or recognition), represents an outcome the project is expected to achieve.

### Principles of Planning

**Project planning is a continual activity from the initial concept to system delivery, is likely the most time-consuming project management activity. This involves frequent plan revisions as new information becomes available.**

**A project plan is a document that outlines the technical and managerial approach for a project. It represents a projection of future actions, implying that while plans might not always be accurate, they form a sound basis for estimating project duration and budget, and for controlling completed and remaining tasks. A project plan becomes particularly crucial in a dynamic environment where many aspects are unclear.**

A well-crafted project plan comprises various elements: 

- Deliverables: This guides the setting up of a quality assurance process.
- Dates: This marks when to deliver results.
- Resources: This includes people and budget allocation.
- Work: This defines the tasks to be done, and their order of execution.

The purposes of a project plan may include: guiding project execution, providing a baseline for progress measurement and project control, and enhancing operational efficiency, among others.

**A baseline, in project management, is the original plan (adjusted for approved changes). It's used to compare actual performance and make project forecasts against the initial plan.**

**An activity is a component of work performed during a project, generally having an expected duration, cost, and resource requirements. Activities are often broken down into sub-activities. Atomic activities are the most granular level, conducted by a few people over a short period, with well-defined inputs and outputs**.

**A work package is an executable activity that can be carried out by an individual or a small group within a short time, delivering a clear result that can be checked against its requirements.**

**Milestones represent defined points in a project timeline where specific results must be available. External milestones serve as gates with go/no-go decisions, where the customer evaluates and decides based on the results. On the other hand, internal milestones, which exist between external ones, are used for internal control purposes.**

**A work breakdown structure (WBS) is a deliverable-oriented, hierarchical grouping of project elements that organizes and defines the total work scope of the project. Each subsequent level presents an increasingly detailed definition of the project.**

A WBS can be validated through the following rules:

- Disjunction rule: All activities of a level must be completely distinct.
- Completion rule: If an activity is decomposed into sub-activities, the entire scope of the activity must be covered, and nothing should be left out.

## Scheduling and Effort Estimation

Efficient scheduling and effort estimation is key to managing and successfully completing any software project. 

### Precedence Planning and Scheduling

**Precedence Planning: This aspect involves defining the logical sequence in which the work packages (or tasks) need to be completed. It's all about understanding and outlining the order of operations.**

**Scheduling: Scheduling is the process of defining the temporal sequence or timeline for the work packages. It's about when the tasks will be done.**

### Activity Planning Techniques

There are various activity planning techniques used in project management, including:

- **Milestone Chart**: This is a graphic representation that showcases the most significant events or 'milestones' within a project. It serves as an effective communication tool between customers and developers, highlighting the progress of the project.

- **Bar Chart**: Also known as a Gantt chart, it visualizes the scheduled tasks or work packages over time. While it doesn't explicitly show dependencies between tasks, it makes the temporal overlap between work packages immediately recognizable.

- **Activity Network Diagram**: This diagram represents work packages and their dependencies. The process to create an activity network diagram involves:
    1. Identifying the work packages.
    2. Identifying dependencies between these work packages.
    3. Estimating the duration for each work package.
    4. Creating the network diagram.
    5. Calculating the early start and early finish, as well as the late start and late finish times for each work package. This information can be crucial in identifying the critical path and managing project timelines.

#### Precedence Relationships

Understanding the dependencies between tasks is essential for both planning and scheduling. Here are the four types of task dependencies or precedence relationships:

- **Finish-to-Start (FS)**: Work Package 2 (WP2) can only start after Work Package 1 (WP1) has been completed.
  
- **Start-to-Start (SS)**: WP2 can only begin after WP1 has started. They can proceed in parallel, but WP2 can't start until WP1 has kicked off.
  
- **Finish-to-Finish (FF)**: WP2 can only be completed after WP1 has been finished. This means that WP1's completion directly influences WP2's completion.
  
- **Start-to-Finish (SF)**: An unusual but sometimes necessary relationship, where WP2 can only be completed after WP1 has started. This implies WP2 may have started before WP1, but it can't finish until after WP1 begins.

#### Computing a Schedule

In project management, the schedule outlines the planned dates for all work packages and milestones. It involves the calculation of start and finish dates, using forward and backward calculations.

- **Forward Calculation**: This process calculates when each work package should start and finish, assuming everything goes as planned.
  - Early Start (ES) of the project is 0.
  - Early Finish (EF) for work package 1 (wp1) is calculated as: `ES(wp1) + duration(wp1)`.
  - The ES for the next work package (wp2) is calculated as the maximum EF of all predecessors of wp2: `ES(wp2) = max(EF(wpn))`, where wpn are all the predecessors of wp2.

- **Backward Calculation**: This calculation determines the latest possible time you can start and finish each work package without delaying the project.
  - Late Finish (LF) of the project equals the EF of the project.
  - Late Start (LS) for wp2 is calculated as: LF(wp2) – duration(wp2).
  - The LF for the previous work package (wp1) is calculated as the minimum LS of all successors of wp1: `LF(wp1) = min(LS(wpn))`, where wpn are all the successors of wp1.

- **Total Float**: It refers to the amount of time a work package may be delayed or extended from its early start without delaying the project’s finish date. Calculated as `Float = LF – EF or LS – ES`. If the float is greater than 0, there is available time; if the float equals 0, the situation is critical.

- **Free Float**: It is the amount of time a work package can be delayed without delaying the early start of any immediately following work package.

- **Critical Work Package**: A work package is critical if its total float equals zero.

- **Critical Path**: This is the path through the network consisting of only critical work packages. The sum of the total float on a critical path is zero. It represents the shortest possible project duration and is crucial for identifying schedule risks, focusing progress control, and shortening the project duration.

- **Schedule Compression**: This refers to techniques used to shorten the schedule without changing project scope. For instance, when projects are in trouble, you can use:
  - **Fast Tracking**: This involves executing activities in parallel that were initially planned in sequence, in order to shorten the critical path.
  - **Crashing**: This involves analyzing cost and schedule trade-offs to determine the greatest amount of compression. For instance, by reallocating resources from non-critical to critical activities, hiring additional resources, or improving productivity through technology application.

### Non-algorithmic Effort Estimation Techniques

#### Delphi Technique

The Delphi Technique is a structured communication technique, originally developed as a systematic, interactive forecasting method that relies on a panel of experts.

- **Procedure:**
  1. The coordinator or moderator presents the project/product definition to the panel of estimators.
  2. Each estimator individually and anonymously completes their estimation.
  3. The moderator then compiles and circulates a summary of all the estimations, along with any unique rationales provided by the estimators.
  4. Using this information, the estimators undertake a second round of estimation, yet again anonymously, taking into account the collective inputs from the first round.
  5. This process continues in iterative rounds until a consensus is reached or the law of diminishing returns is perceived to apply.

- **Advantages:**
  - Encourages a collaborative and team-based approach to estimating.
  - Minimizes bias that could be introduced in individual estimation.
  - Does not necessitate historical data.
  - Flexible and can be utilized for both high-level and detailed level estimations.
  - Economically efficient and straightforward to implement.

- **Disadvantages:**
  - Sourcing multiple experts for the panel could be challenging.
  - The estimation process is not easily reproducible and cannot be externally validated.
  - There is a risk of consensus being achieved on an incorrect estimate due to insufficient scepticism.
  - Can inadvertently foster a false sense of confidence or certainty.

#### Planning Poker

Planning Poker, sometimes referred to as Scrum poker, is an agile estimating and planning technique that is essentially a consensus-based variant of the Delphi Technique.

- **Procedure:**
  1. Individual user stories or work items are presented for estimation.
  2. Each story is discussed briefly by the entire team to clarify assumptions and dependencies.
  3. Every team member independently selects a card from their deck, which corresponds to their estimate of the effort involved in implementing the story under discussion.
  4. All estimates remain confidential until each team member has made their selection.
  5. All cards are then revealed simultaneously, and any significant deviations are discussed. This process continues until consensus is reached.

- **Advantages:**
  - Encourages team involvement and mutual understanding.
  - Mitigates influence or bias from dominant personalities.
  - It encourages discussion and clarifies assumptions, resulting in more accurate estimates.
  - The use of cards makes it a fun and engaging activity.

- **Disadvantages:**
  - It can be time-consuming, especially for larger teams or complex tasks.
  - Some team members may feel pressured to conform to the estimates of others.
  - Not suitable for very large teams or distributed teams without using digital tools.
  - It requires a good understanding of the task at hand by all team members.

### Algorithmic Effort Estimation Techniques

#### Software Sizing

Software sizing is a critical component in managing software projects. It's necessary to estimate the size of a software project to calculate the time and resources required for its completion. Two popular methods for software sizing include:

- **Lines of Code (LOC):** This involves counting the number of lines of code. However, the same function may vary in size when written in different programming languages, making this method heavily dependent on the chosen programming language.

- **Function Point Estimation (FP):** This method measures software size based on the functionality provided by the software, rather than its programming statements. Unlike LOC, FP estimation is language-independent, i.e., the same function would have the same FP size regardless of the programming language used.

The basic equation for effort calculation involves these three parameters:

- Quantity: This is the size measure, such as function points or lines of code.
- Quality: This refers to an adjustment factor that accounts for the software's quality attributes.
- Productivity: This is derived from an organization's own historical productivity data.

Effort can be calculated as: `Effort = (Quantity * Quality) / Productivity`

#### Function Point Method

The Function Point method is a structured way of assessing the size of a software project based on the user's perspective. It involves the following steps:

1. Identify elementary processes (user functions).
2. Classify each elementary process based on its primary intent (input, output, or inquiry).
3. Identify logical and user-identifiable groups of data.
4. Classify each group of data as external or internal data.
5. Assess the complexity of each elementary process and group of data.

These steps help to categorize the software into five function point elements:

- External input
- External output
- User inquiry
- Internal Data Store
- External Data Store

Each of these elements is then assigned a weight based on its complexity. The total of these weights gives us Unadjusted Function Points (uFP).

The final step is to adjust these function points by taking into account the quality attributes of the software, leading to Adjusted Function Points (aFP), calculated as:
- \(aFP = VAF \times uFP\), where:
  - \(VAF = 0.65 + 0.01 \times \sum_i GSC_i\)

Here, VAF stands for Value Adjustment Factor, and GSCi represents general system characteristics.

After calculating the function points, they can be converted into effort estimates in two ways:

- By creating a mapping from function points to persons per month, using organization-specific experience data.
- By converting function points to Source Lines of Code (SLOC) using a further estimation method like COCOMO.

#### Constructive Cost Model (COCOMO II)

The Constructive Cost Model II (COCOMO II) provides a method to predict the cost, effort, and schedule when planning new software development activities.

- Estimating the program size with COCOMO II is done by considering multiple factors:
  - The size of the code that is reused: Reuse can drastically reduce the overall effort required to develop a software product.
  - The stability of requirements: Unstable or changing requirements often lead to increases in project effort.
  - Calculation for the size (`Size`) is given by the formula \(Size = (1 + \frac{REVL}{100}) \times (LOC_{new} + LOC_{equivalent})\), where:
    - `REVL`: Stands for the percentage of reusable code.
    - `LOC_{new}`: Lines of new code.
    - `LOC_{equivalent}`: Lines of equivalent code.

- The effort can be estimated using the formula:
  - \(Effort = A \times Size^{SE} \times \prod_i EM_i\), where:
    - \(Effort\): The overall effort needed to complete the project, typically measured in person-months.
    - \(Size\): The size of the program in KSLOC (Thousand Source Lines of Code).
    - \(SE\): Scaling Exponent, which can be adjusted according to the particular characteristics of the project.
    - \(EM\): Effort multipliers, which represent the cost drivers that can impact the productivity of the project.
    - \(A\): An effort coefficient that should be calibrated to the local productivity data to accurately reflect the organization's capability.

- The scale factors in COCOMO II are:
  - `Precedentedness (PREC)`: The extent to which previous experiences with related projects can be applied to the current project.
  - `Development Flexibility (FLEX)`: The level of freedom we have in deciding the development process and the software's functional and performance requirements.
  - `Architecture and Risk Resolution (RESL)`: The proficiency in risk management and architecture design that the project team possesses.
  - `Team Cohesion (TEAM)`: Is the project team experienced, cohesive and operates harmoniously? 
  - `Process Maturity (PMAT)`: The level of process maturity, which is a measure of the team's familiarity with the software development process and its ability to execute it effectively.

- Project Duration and Staffing: COCOMO II also gives estimates for the project duration and staffing.
  - \(T_{nom} = C \times E_{nom}^{(D+0.2 \times (SE-B))}\), where:
    - \(T_{nom}\): Time to develop in calendar months.
    - \(C\): Schedule coefficient.
    - \(E_{nom}\): The nominal effort required without considering any schedule compression or expansion.
    - \(D\): Scaling Base Exponent for Schedule.
  - \(Average Staffing = Effort / T_{nom}\) : Average staffing, which is the total effort divided by the time to develop.


## Monitoring and Risk Management

### Monitoring and Controlling

Monitoring and Controlling are continuous and iterative project management activities that track, review, and regulate the progress and performance of the project. They identify any areas in which changes to the plan are required and initiate the corresponding changes.

- **Monitoring** entails:
  - Collecting project performance data to keep a real-time understanding of progress.
  - Determining performance measures and forecasts based on collected data and projections.
  - Reporting and disseminating performance information to stakeholders for transparency.

- **Controlling** involves:
  - Comparing actual performance with planned performance to highlight deviations.
  - Analysing deviations to understand their implications on the project.
  - Evaluating possible alternatives based on the analysis.
  - Taking appropriate corrective actions as needed to bring the project back on track.

The primary goals of monitoring and controlling include the comparison of progress to the schedule and budgets, the creation of project status reports, and the analysis of the results along with the definition of appropriate control measures. 

Secondary goals comprise the development of measurement procedures to assess actual project progress, the establishment of controlling standards, and ensuring that the experience gained in projects can be used in follow-up projects, fostering a culture of continuous learning and improvement.

#### Control Cycle and Consequence Analysis

A control cycle is a systematic process of monitoring, evaluating, and taking corrective action.

Consequence Analysis is a key component of the control cycle, where it analyses deviations from the plan and defines and plans appropriate control measures. These measures can either be corrective, closing the gap between the actual state and plan, or they could involve plan modifications, adapting the plan to the actual state of the project.

#### Measuring Progress

The goal of measuring progress is to deliver input data for a plan/actual comparison. Data must be up to date to react to deviations early. Factors to be controlled include defined work packages, dates, budget, and milestones.

##### Degree of Completion (DoC)

There are two major ways to determine the degree of completion:

- The naïve approach, \(DoCES = \frac{actualEffort}{plannedEffort}\), where:
  - \(ES\): Effort Spent.
  This approach works on the assumption that the planned effort is correct and if we have spent the effort, we are done. However, it fails when the planned effort is incorrectly estimated.

- The estimate to complete approach, \(DoCETC = \frac{actualEffort}{forecastFinalEffort}\), where:
  - \(ETC\): Estimate to Complete.
  It defines the effort still needed to complete a work package by assessing the value of the work that is already done. If the forecasts are totally wrong, this approach may also fail.

#### Milestone Trend Analysis

Milestone Trend Analysis (MTA) provides a visual representation of project progress. Its goals include the actual/plan comparison of all external milestones, illustration of the status of all milestones, and recognizing trends and deviations from the planned schedule.

- A horizontal line signifies that the planned date is likely to be met.
- An ascending line signifies a delay, meaning the milestone will be completed after the planned date.
- A descending line signifies that the milestone will be completed before the planned date.

The benefits of MTA include easy recognition of deviations from the plan and a simple means to communicate the project status to customers and senior management.

### Earned Value Analysis

Earned Value Analysis (EVA) is a method that allows us to track the project's progress and forecast its likely future performance based on past trends. It provides us with valuable information to make informed decisions.

Inputs

- **Planned Value (PV):** This is the budget allocated for the work currently scheduled. It represents the monetary value of the work that should have been completed by a specific date.
- **Earned Value (EV):** This represents the actual completion of the project. It's the sum of the planned cost for the work already completed.
  * `EV = DegreeOfCompletion * BAC`
- **Actual Cost (AC):** This is the total cost incurred for the project up to a specific date. It includes all costs spent on the project, regardless of what was budgeted.
- **Budget at Completion (BAC):** This is the estimated total cost of the project. It's calculated as `BAC = PV(enddate)`, which is the total PV at the project's scheduled completion date.

Current Status

- **Schedule Variance (SV):** It's the difference between the value of work performed (EV) and planned costs (PV). It helps assess if the project is ahead or behind schedule.
  * `SV = EV - PV`
- **Schedule Performance Index (SPI):** This index compares work performed (EV) to work planned (PV). It measures the project's speed in relation to how quickly it was expected to progress.
  * `SPI = EV / PV`
    * `SPI > 1`: Project is ahead of schedule.
    * `SPI = 1`: Project is on schedule.
    * `SPI < 1`: Project is behind schedule.
- **Cost Variance (CV):** It's the difference between the value of work performed (EV) and actual cost (AC). It shows if the project is over or under budget.
  * `CV = EV - AC`
- **Cost Performance Index (CPI):** This index compares the worth of work performed (EV) to the actual cost (AC). It indicates the project's efficiency by calculating how much output we get for every unit of cost spent.
  * `CPI = EV / AC`
    * `CPI > 1`: The cost of work performed is lower than planned, hence under budget.
    * `CPI = 1`: Project is on budget.
    * `CPI < 1`: The cost of work performed is higher than planned, hence over budget.

Forecasting

- **Estimate at Completion (EAC):** This is the forecasted budget adjusted according to the project's current performance. It's the sum of the actual cost to date and an objective estimate of costs for remaining work.
  * `EAC = BAC / CPI`
- **Variance at Completion (VAC):** It's the projected difference between the initial budget (BAC) and the forecasted total cost (EAC) at the project's end.
  * `VAC = BAC - EAC`
    * `VAC > 0`: The project is expected to finish under budget.
    * `VAC = 0`: The project is expected to finish on budget.
    * `VAC < 0`: The project is expected to finish over budget.
- **To-Complete Performance Index (TCPI):** This index measures the efficiency that must be achieved to complete the remaining work with the remaining budget.
  * `TCPI = (BAC - EV) / (BAC - AC)`

### Risk Management

Risk Management is a critical component of successful software project management. It involves identifying, assessing, and addressing the potential risks that may arise during the project execution.

#### Understanding Risk

A risk in project management is defined as an uncertain event or condition that, if it occurs, can have either a positive or negative effect on a project's objective. These risks could be related to various factors such as technology, resources, scope changes, or budget overruns. Properly identifying and managing these risks is crucial to the project's success.

#### Risk Management Process

Risk management is a systematic process that consists of several steps. It includes risk identification, risk analysis, risk response planning, and monitoring and controlling risks. 

#### Software Engineering Institute (SEI) Risk Taxonomy

The SEI Risk Taxonomy is a framework that defines a hierarchical structure consisting of class, element, and attribute. It's often used to develop a company-specific questionnaire, facilitating the identification of potential risks in a structured manner. This taxonomy helps in focusing the risk identification process on the areas that matter the most, allowing for a more efficient and effective risk management.

#### Risk Analysis

Risk analysis is an essential step in the risk management process. Its main goals are to:

- Identify risks that need to be mitigated
- Assess and prioritize all identified risks

In determining the severity of a risk, we need to consider two factors:

- The probability of the risk occurrence
- The impact on the project objectives if the risk occurs

By combining these two factors, we get a measure of risk severity. A risk is considered high if both its likelihood to occur and its potential impact are high.

#### Risk Response Planning

Risk response planning is the process of developing strategies to handle identified risks. The primary goal here is to define and plan appropriate measures to manage these risks. 

It involves the following tasks:

- Establishing mitigation options, which include:
  - Risk avoidance: Changing the plan to eliminate the risk altogether
  - Risk acceptance: Willingly accept the consequences if a risk occurs
  - Risk transference: Transfer all or part of the risk to another party (like insurance)
- Developing a comprehensive risk response plan, which should include triggers (the conditions under which the response will be initiated), roles and responsibilities, and the resources required to implement the response.

This framework of risk management not only minimizes the potential negative impact of adverse events on project objectives but also harnesses any potential opportunities that may arise.

## Stakeholder Management & Decision Analysis

### Stakeholder Management

**A stakeholder refers to an individual, group, or organization that could be affected by a decision, activity, or outcome of a project or who perceives itself as such. They may also have a significant influence over the project and its deliverables. Key Stakeholders: sponsor, customer, development organization, project team members, managers.**

For a project to deliver its optimum value, all stakeholders must be effectively engaged.

Stakeholder Management consists of processes required to:

- Identify the people, groups, or organizations that could impact or be impacted by the project
- Analyse stakeholder expectations and their potential impact on the project
- Develop appropriate management strategies for effectively engaging stakeholders in project decisions and execution

The first step, known as **Stakeholder Identification**, involves the following actions:

- Identifying stakeholders and their interests in the project
- Understanding the project's benefits to the stakeholder
- Identifying project activities that might cause damage or conflict for the stakeholder

Once stakeholders are identified, they are classified as either internal/external and primary/secondary. Tools such as brainstorming, meetings with experts, and a stakeholder register can be utilized for this purpose.

The next step is **Stakeholder Classification**, where stakeholders are mapped based on their attitudes such as Champion, Promoter, Opposition. It also involves identifying relations between stakeholders, whether they be negative, positive, or neutral.

Further, stakeholders are classified based on their **Power & Interest** in the project. This helps create a power-interest grid. It's crucial to base this assessment on the stakeholder's perspective rather than your own.

Following classification, we develop **Management Strategies** for each type of stakeholder:

- **High Power – High Interest**:
    - Positive Attitude: Provide regular information updates, consult them before decision-making, encourage them to act as project advocates.
    - Negative Attitude: Aim to build confidence in the project, identify what is important to them, and demonstrate that you are acting in the project's best interest.

- **Low Power – High Interest**:
    - Positive Attitude: Maintain their enthusiasm through regular updates, involve them as much as resources allow, and seek their input and opinion.
    - Negative Attitude: Don't allocate excessive resources to them, considering their low power.

- **High Power – Low Interest**: Ensure that project changes do not increase the level of negative interest. Understand what is important to them and ensure the project does not negatively affect this.

- **Low Power – Low Interest**: Provide them with basic information through means such as project newsletters or the project website.

The final output of this process is the **Stakeholder Engagement Plan**, a strategy for effective stakeholder engagement. Its purpose is to ensure all stakeholders are engaged during the project, establishing a balance between activities needed to mitigate negative stakeholders and encouraging positive ones.

### Decision Analysis & Resolution (DAR)

**Decision Analysis and Resolution (DAR) is a systematic technique used to evaluate different choices against a predefined set of criteria. This formal evaluation process reduces subjectivity, thereby increasing the likelihood of selecting an alternative that aligns with stakeholder needs.**

Benefits:

- reducing the bias inherent in decision-making
- increasing stakeholder buy-in through a more transparent process
- and ensuring a higher chance of choosing an alternative that satisfies multiple stakeholder requirements

#### DAR Process

- **Initial Steps**
  1. **Planning the Decision**: Begin by articulating the decision problem and identifying all stakeholders who will participate in the decision process.
  2. **Identifying Alternative Solutions**: Explore various potential solutions to the problem.

- **Establishing Evaluation Criteria**
  - Identify a range of criteria against which the alternatives will be evaluated. These criteria could include factors like cost, quality, RAM, or performance. Use a ranking scale to reflect the importance of each factor, such as a numerical scale (1-10) or qualitative descriptors (low-medium-high).

- **Selecting Evaluation Methods**
  - There are several methods for evaluating potential solutions, including Pareto Analysis, Paired Comparison Analysis, and Grid Analysis.

#### Evaluation Methods

- **Pareto Analysis**
  - Goal: Reduce an excessive number of alternatives.
  - Procedure: 
    1. Choose the most significant criterion.
    2. Evaluate all alternatives according to this criterion.
    3. Arrange all alternatives, sorted by their evaluated results.
    4. Select a subset of the most significant alternatives, such as those that account for 80% of the scores.

- **Paired Comparison Analysis**
  - Goal: Determine relative ranking between alternatives.
  - Procedure: 
    1. Compare alternatives in pairs.
    2. Determine the preferred or more significant alternative by assessing the difference in importance, using a scale ranging from 0 (no difference) to 3 (major difference).
    3. Calculate the total scores for each alternative.

- **Grid Analysis**
  - Goal: Choose the best solution using weighted criteria.
  - Procedure: 
    1. Start with a small number of viable alternatives and several criteria.
    2. Assign weights to the criteria according to their importance.
    3. Evaluate each alternative for each criterion using a simple ordinal scale.
    4. Calculate the product of the given assessment and weight, and the sum of the products for each alternative.

#### Solution Identification

- Evaluate the identified alternatives based on the criteria rankings and the selected evaluation method.
- Select the best solution from the alternatives.
- Conduct a detailed analysis of the chosen solution, assessing potential side effects or unintended consequences.
- Perform risk analysis, taking into account the project's attributes and potential pitfalls. This analysis will help ensure the decision remains optimal in the face of future challenges.
