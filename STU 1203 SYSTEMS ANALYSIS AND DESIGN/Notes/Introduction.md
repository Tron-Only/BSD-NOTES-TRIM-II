# System Analysis and Design: Introduction to System Analysis and Design
## Concepts of System Analysis and Design

> [!INFO] System
> An orderly grouping of interdependent components, linked together according to a plan, to achieve a specific objective

### Parts/Elements of a System
1. **Components** - This involves the conversion of input into output
2. **Inputs and Outputs** - the objective of any system is to generate an output that is of value to the user. An input can include goods, services, or information while the output must be within the expectations of the user like materials, human resources, data, information etc.
> [!NOTE] Note
> The first step in specifying the nature of the input required to operate a system is determination of the output.

 3. **Boundaries and Interfaces** - 
*Boundaries* are the limits that identify the system's components, processes and interrelationships when it interacts with other systems. 

**For example**: A teller system in the bank is confined to the deposits, withdrawals and related customer activities such as checking and saving accounts but limits foreclosures which is processed by a 'mortgage loan system'.

*Interfaces* are interactions between the system and the environment

 4.  **Environment** - This is the supra-system(overall system) within which an organization functions and defines everything that interacts with the system elements.
 5. **Constraints/Control** - These are elements that regulate the system operation, e.g policies, specifications, standards, and regulations, which constitute decision-making subsystem that controls activities related to input, processing and output.
 6. **Purpose** - This is the key objective(s) that a system must fulfill to the intended user
A proper example is the human body

| **System** | **Subsystems**                                                               | **Interfaces**                                       | **Environment** | **Input**                                    | **Output**                                                     |
| ---------- | ---------------------------------------------------------------------------- | ---------------------------------------------------- | --------------- | -------------------------------------------- | -------------------------------------------------------------- |
| Human Body | Nervous system<br><br>Digestive system<br><br>Respiratory system<br><br>etc. | Skin, Hair<br><br>Ear, Nose<br><br>Mouth<br><br>etc. | Atmosphere      | Oxygen<br><br>Water<br><br>Foods<br><br>etc. | Energy<br><br>Waste products<br><br>Carbon dioxide<br><br>etc. |
Similarly an exam processing system has the following:

| System                 | Subsystems                                                 | Interfaces                          | Environment                                                                      | Input                            | Output                                                     | Constraints/controls                                        |
| ---------------------- | ---------------------------------------------------------- | ----------------------------------- | -------------------------------------------------------------------------------- | -------------------------------- | ---------------------------------------------------------- | ----------------------------------------------------------- |
| Exam processing system | Database systems, operating system, grading functions etc. | Input forms,<br><br>Dashboards etc. | Department<br><br>University<br><br>Administrator<br><br>Students, lecturers etc | Raw score: CAT, assignment, exam | Individual results, overall results, reports and summaries | Submission dates and deadlines,<br><br>No partial marks etc |

### Types of Systems
#### 1. Physical/Abstract Systems
These are content entities that are static or dynamic parts in an operation, e.g., the chairs and tables in a computer center that facilitate its operation because they can be *seen* and *counted*

Data, programs, outputs and applications in a computer system change with user demand or priority of the information requests. Such entities form dynamic entities of a computer system.

Abstract systems are non-physical entities. For example, formulas of relationship between sets of variables, or models that represent a physical situation.  

#### 2. Open/Closed Systems
It depends on the extent of system independence. 

A system is said to be an open system if there exists interaction between the system and its environment. 

If there is no interaction of the system with its environment, the system is said to be a closed system.

> [!NOTE] Note
> It is nearly impossible to have a closed system because a system needs to interact with its environment and in system analysis almost all systems are open systems, which get affected by their environment.
#### 3. Natural/Man-made Systems
Natural systems are products of evolution whereas man-made systems have been created by human beings to satisfy their specific needs.

### General classification of computer-based systems
#### 1. Transaction Processing System
Automate the handling of data about business activities or transactions, which can be thought of as simple, discrete events in the life of an organization. 

Data about each transaction are captured, transaction verified and accepted or rejected, and validated transactions are stored for later aggregation. 

To analyze and design TPS one must focus on the firm’s current procedures for transaction processing, whether manual or automated. This requires careful tracking of data capture, flow, processing, and output. 

The goal of TPS development is to improve transaction processing by speeding them up, using fewer people, improving efficiency and accuracy, integrating it with other information systems, or providing information not previously available.


#### 2. Management Information System (MIS)
Takes the raw data available through a TPS and converts them into a meaningful aggregated form that managers need to conduct their responsibilities. 

To analyze and design such a system, one must have a good understanding of what kind of information managers require and how they use the information in their jobs.

#### 3. Decision Support Systems (DSS)
They are solely meant to help organization decision makers make decision. 
DSS provides an interactive environment in which decision makers can quickly manipulate data and models of business operations. 

To analyze and design such system, one must concentrate on its DSS components that include database, model base and the user dialogue.

#### 4. Expert Systems (ES)
It attempts to codify and manipulate knowledge rather than information. 
Knowledge representations describe the way expert approach situations in a specific problem domain. 

To analyze and design such system one must acquire knowledge of the expert in the particular problem domain.

### Characteristics of a System
1. **Interdependence** - Components depend on one another in a system.
2. **Order** - Refers to the arrangement of components that helps to achieve objectives.  It portrays system-subsystem relationship.
3. **Integration** - Parts of a system work together within the system even though each part performs a unique function.
4. **Central objective** - Systems are goal-driven entities and every system must have some goals and objectives.
5. **Interaction** - Interrelationship between these components enables a system to perform.


### System Analysis and Design
- **System Analysis** – is the process of collecting factual data, understand the process involved, identifying problems and recommending feasible suggestions for improving the system functioning. This involves studying the business processes, gathering operational data, understand the information flow, finding out bottlenecks and evolving solutions for overcoming the weaknesses of the system so as to achieve the organizational goals.


- **System design** – is the process of specifying the new system. It involves detailing the tasks to be carried out and the data to be input, output and stored on files. Initially a logical design is produced, specifying the functions to be carried out by the new system without tying these down to specific hardware or software. Then a physical design is produced, giving precise details of hardware, software, file formats etc.

#### System Analyst
They are in charge of analyzing, designing and modifying various systems and processes to ensure compatibility and user effectiveness.

##### System Analyst Skills
1. **Analytical skills** - skills the analyst must have _system thinking, organizational knowledge, problem identification,_ and _problem analyzing and solving skills_
_System thinking_ - the analyst must see everything as a system. 

_Organizational knowledge_- They must understand the functions and procedures of the particular organization they are working for. 

_Problem identification_ – They must define differences by comparing the current situation to the output of a model that predicts what the output should be. 

_Problem analyzing and solving_ – They must analyze a problem and solve it through four phases: intelligence, design, choice, and implementation. During intelligence, all information relevant to the problem must be collected. In the design phase, alternatives should be formulated. During choice phase, the best alternative solution is chosen, and solution put into practice during implementation phase

2. **Technical skills** - They must know how various technologies work, their potentials and limitations as well as the technical know-how of how different notations for representing, or modeling various aspects information systems work.

3. **Management skills** – They must know how to manage their work and how to use organizational resources in the most productive ways possible. They must demonstrate resource, project, risk, and change management skills.

4. **Interpersonal skills** – They needs interpersonal skills that include communication skills, groups’ facilitation skills, and skills to manage expectations of users and managers.

##### Roles of System Analyst
1. Business Analysis
2. Requirements elicitation (To produce requirements)
3. Infrastructure analysis
4. Change management by providing adequate documentation and support to users
5. Project Manager


## System Development Life Cycle (SDLC)
The **system development life cycle (SDLC)** is a common methodology for systems development that features several phases that mark the progress of the system analysis and design effort.
```mermaid
flowchart LR
    A[Project Identification and Selection] --> B[Project Initiation and Planning]
    B --> C[Analysis]
    C --> D[Design]
    D --> E[Implementation]
    E --> F[Maintenance]
    
    F --> E
    E --> D
    D --> C
    C -->B
    B --> A
```
This presentation is known as the *waterfall model*.
At the end of each phase (and sometimes within phases for intermediate steps), a project reaches a milestone and, as deliverables are produced, they are often reviewed by parties outside the project team

1. **Project Identification and selection**

This is the first phase of SDLC where the need for a new or enhanced system is identified.  This need is examined and projects to meet this need are identified. These needs result from requests to deal with problems in current procedures, desire to perform additional tasks, or from realization that IT could be used to capitalize on an existing opportunity.  These needs are then prioritized and translated into a plan that includes a schedule for developing new major systems.

System analyst determines whether or not resources should be devoted to the development or enhancement of system under consideration. The outcome of this phase is determination of which system development projects should be undertaken.

2. **Project initiation and planning**
This is the second phase that involves two activities: investigation of system problem or opportunity at hand, and the presentation of reasons why the system should or should not be developed by the organization. The scope of the proposed system is determined and a specific plan to be followed by the project team is produced. The baseline is to specify the time and resources needed for the execution of the system. This forms the likelihood that system analyst and IS department will develop a system that will solve the problem or exploit the opportunity and also determine whether the costs of developing the system outweighs the benefits it could provide.

3. **Analysis**
In this phase, the analysts thoroughly studies the current procedures of the business and the information system used to perform those tasks for the following reasons:
-  **Requirement determination** – determine what users want from the proposed system. This involves careful scrutiny of current systems, manual or computerized, that will be replaced or enhanced.

- Studying the requirements and structuring them according to their interrelationships, and eliminating any redundancy.

- Generating alternative initial designs that match the requirements

- Comparing the generated alternative designs to determine the one that best meets the requirements within the cost, labor and technical levels of the organization.

The output of this phase is a description of (but not a detailed design for) the alternative solution recommended by the analysis team.

4. **Design**
In this phase, the description of the recommended alternative solution is converted into logical and then physical system specifications. All aspects of the system, from input and output screens to reports, databases and computer processes must be designed. This is followed by provision of physical specifications of the designed system, either as a model or as a detailed documentation, to guide those who will build the system.

The part of the design that is independent of any specific hardware or software platform is referred to as **logical design.** It concentrates on the business aspects of the system and tends to be oriented to a high level specificity.  Once the overall high-level design of the system is worked out, they are turned into physical specifications, a process referred to as **physical design.** Various parts of the system to perform the physical operations necessary to facilitate data capture, processing, and information output is designed.

5. **Implementation**

In this phase, system specifications are turned into a working system that is tested and then put into use. Implementation includes coding, testing and installation. During coding, programmers write the programs that make up the system. During testing, programmers and analysts test individual programs and the entire system in order to find and correct errors. During installation, the new system becomes a part of the daily activities of the organization where system is loaded on new or existing hardware and users are introduced into the new system and trained.

6. **Maintenance**
This is the final phase which is the overlay to the life cycle. Sometimes users find problems with how system works and often think of better ways to perform its tasks. Programmers make changes that users ask for and modify system to reflect changing business needs. These changes are necessary to keep the system running and useful.

## System Development Methodologies

#### Structured System Analysis and Design

It uses a series of phases known as SDLC which incorporates process models to describe a system graphically. Process models show the data that flows in and out of system processes. It also addresses data organization and structure, relational database design, and user interface issues.

Usually, when one phase ends, another begins when milestone has been reached. A milestone usually took the form of some deliverables or pre-specified output from phase. Currently, it is easier to go back to earlier phases in the life cycle when necessary. It additionally emphasizes on partitioning or dividing a problem into smaller, more manageable units and on making clear distinction between physical and logical design.  

#### Object-Oriented Analysis and Design

This approach combines data and processes (methods) into single entities called objects. Objects correspond to the real things an information system deals with such as customers, suppliers, contracts, agreements etc.

The goal of OOAD is to make system elements more reusable, thus improving system quality and productivity of system analysis and design.

Generally, the primary task of OOA is identification of objects, definition of their structures and behavior, and definition of their relationships.  OOD, on the other hand, models the details of object’s behavior and communication with other objects so that system requirements are met, reexamined and redefined to take advantage of benefits of object-orientation.

#### Agile/adaptive

These are the newest methods that attempt to make system development less of an art and more of science. Rigorous engineering techniques are applied.  A system is developed incrementally, by building a series of prototypes and constantly adjusting them to user requirements. As the agile process continues, developers revise, extend, and merge earlier versions into the final product.

The approach emphasizes continuous feedback, and each incremental step is affected by what was learned in the prior steps.  It has attracted a wide following and an entire community of users.


|                    | **STRUCTURED SAD**                                                                                                                                                                                                                    | **OBJECT-ORIENTED AD**                                                                                                                                                                                  | **AGILE/ADAPTIVE METHODS**                                                                                                                                                                                           |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description**    | Represents the system in terms of data and the processes that act upon that data.<br><br>System development is organized into phases with deliverables and milestones to measure progress.<br><br>Iteration is possible among phases. | View system as objects that combine data and processes.<br><br>They are more iterative.                                                                                                                 | Stresses intense team-based efforts.<br><br>Breaks development process down into cycles, or iterations that add functionality.<br><br>Attempts to reduce major risks by incremental steps in short intervals.        |
| **Modeling Tools** | Data flow diagrams (DFD) and process descriptions                                                                                                                                                                                     | Various OO diagrams that depict system actors, methods and messages                                                                                                                                     | Tools that enhance communication, such as collaborative software, brainstorming and whiteboards.                                                                                                                     |
| **Pros**           | Relies heavily on written documentation. Frequent phase iteration provides flexibility comparable with other methods. Well suited to project management tools and techniques.                                                         | Integrates easily with OO programming languages. Code is modular and reusable, reducing development time and cost. Easy to maintain and expand as new objects can be cloned using inherited properties. | Very flexible and efficient in dealing with change. Stresses team interaction and reflects a set of community-based values. Frequent deliverables constantly validate the project and reduce risk.                   |
| **Cons**           | Changes can be costly, especially in later phases. Requirements are defined early, and can change during development. Users might not be able to describe their needs until they can see examples of features and functions.          | Interaction of objects and classes can be complex in larger systems.                                                                                                                                    | Team members need a high level of technical and communications skills. Lack of structure and documentation can introduce risk factors. Overall project might be subject to scope change as user requirements change. |