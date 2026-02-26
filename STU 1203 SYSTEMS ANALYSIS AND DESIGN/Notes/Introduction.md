# System Analysis and Design: Introduction

## Key Terminologies
1. **System**: An orderly grouping of interdependent components, linked together according to a plan, to achieve a specific objective.
2. **System Analysis**: The process of collecting factual data, understanding processes, identifying problems, and recommending feasible improvements.
3. **System Design**: The process of specifying a new system's architecture, components, modules, interfaces, and data.
4. **System Analyst**: A professional who analyzes, designs, and modifies systems to ensure compatibility and user effectiveness.
5. **SDLC**: System Development Life Cycle - a common methodology for systems development featuring several phases.

---

## 1. System Fundamentals
> [!abstract] System
> A system is an orderly grouping of interdependent components, linked together according to a plan, to achieve a specific objective.

### Parts/Elements of a System
1. **Components** - The individual parts that enable conversion of input into output.

2. **Inputs and Outputs** - The objective of any system is to generate an output of value to the user.
   - **Input**: Goods, services, information, materials, human resources, or data.
   - **Output**: Must meet user expectations and deliver value.

> [!note] Important Principle
> The first step in specifying the nature of input required to operate a system is determination of the desired output.

3. **Boundaries and Interfaces**
   - **Boundaries**: The limits that identify the system's components, processes, and interrelationships when it interacts with other systems.
   - **Interfaces**: The interactions between the system and its environment.

> [!example] Bank Teller System
> A teller system in a bank is confined to deposits, withdrawals, and related customer activities (checking and saving accounts), but excludes foreclosures, which are processed by a separate mortgage loan system.

4. **Environment** - The supra-system (overall system) within which an organization operates and defines everything that interacts with the system elements.

5. **Constraints/Control** - Elements that regulate system operations, such as policies, specifications, standards, and regulations. These constitute a decision-making subsystem controlling activities related to input, processing, and output.

6. **Purpose** - The key objective(s) that a system must fulfill for the intended user.

### System Examples

**Example 1: Human Body System**

| **System** | **Subsystems**                                      | **Interfaces**                     | **Environment** | **Input**                | **Output**                                     |
| ---------- | --------------------------------------------------- | ---------------------------------- | --------------- | ------------------------ | ---------------------------------------------- |
| Human Body | Nervous system, Digestive system, Respiratory system | Skin, Hair, Ear, Nose, Mouth, etc. | Atmosphere      | Oxygen, Water, Foods     | Energy, Waste products, Carbon dioxide         |

**Example 2: Exam Processing System**

**Example 2: Exam Processing System**

| **System**             | **Subsystems**                                    | **Interfaces**         | **Environment**                                  | **Input**                    | **Output**                                 | **Constraints/Controls**                    |
| ---------------------- | ------------------------------------------------- | ---------------------- | ------------------------------------------------ | ---------------------------- | ------------------------------------------ | ------------------------------------------- |
| Exam Processing System | Database systems, Operating system, Grading logic | Input forms, Dashboards | Department, University, Administrators, Students | Raw scores: CAT, Assignment, Exam | Individual results, Overall results, Reports | Submission deadlines, No partial marks |

---

## 2. Types of Systems

### 1. Physical/Abstract Systems
**Physical Systems** are concrete entities that are static or dynamic in operation.
- **Example**: Chairs and tables in a computer center facilitate operations because they can be *seen* and *counted*.
- **Dynamic Example**: Data, programs, outputs, and applications in a computer system change based on user demand or information request priority.

**Abstract Systems** are non-physical entities.
- **Example**: Formulas showing relationships between sets of variables, or mathematical models representing physical situations.

### 2. Open/Closed Systems
Classification depends on the extent of system independence.

**Open System**: A system that interacts with its environment.
**Closed System**: A system that does not interact with its environment.

> [!note] Important Note
> It is nearly impossible to have a truly closed system because systems need to interact with their environment. In system analysis, almost all systems are open systems that are affected by their environment.

### 3. Natural/Man-made Systems
**Natural Systems**: Products of evolution (e.g., ecosystems, human body).
**Man-made Systems**: Created by humans to satisfy specific needs (e.g., computer systems, transportation systems).

---

## 3. Computer-Based Information Systems

### 1. Transaction Processing System (TPS)
> [!abstract] TPS
> Automates the handling of data about business activities or transactions—simple, discrete events in the life of an organization.

**Key Functions**:
- Captures data about each transaction
- Verifies and validates transactions (accept or reject)
- Stores validated transactions for later aggregation

**Development Focus**:
- Analyze current procedures for transaction processing (manual or automated)
- Track data capture, flow, processing, and output carefully

**Goal**: Improve transaction processing by:
- Speeding up processes
- Using fewer people
- Improving efficiency and accuracy
- Integrating with other information systems
- Providing previously unavailable information

### 2. Management Information System (MIS)
> [!abstract] MIS
> Converts raw data from TPS into meaningful aggregated information that managers need to conduct their responsibilities.

**Development Focus**:
- Understand what information managers require
- Understand how managers use information in their jobs

### 3. Decision Support Systems (DSS)
> [!abstract] DSS
> Designed solely to help organizational decision makers make decisions.

**Key Features**:
- Provides interactive environment
- Allows quick manipulation of data
- Uses models of business operations

**Development Focus**:
- Database component
- Model base component
- User dialogue component

### 4. Expert Systems (ES)
> [!abstract] ES
> Attempts to codify and manipulate knowledge rather than information.

**Key Features**:
- Uses knowledge representations
- Describes how experts approach situations in specific problem domains

**Development Focus**:
- Acquire knowledge from experts in the particular problem domain

---

## 4. Characteristics of a System
1. **Interdependence** - Components depend on one another within the system.
2. **Order** - The arrangement of components that helps achieve objectives; portrays system-subsystem relationships.
3. **Integration** - Parts work together within the system, even though each part performs a unique function.
4. **Central Objective** - Systems are goal-driven entities; every system must have goals and objectives.
5. **Interaction** - Interrelationships between components enable the system to perform.

---

## 5. System Analysis and Design

### System Analysis
> [!abstract] System Analysis
> The process of collecting factual data, understanding processes involved, identifying problems, and recommending feasible suggestions for improving system functioning.

**Activities Include**:
- Studying business processes
- Gathering operational data
- Understanding information flow
- Finding bottlenecks
- Evolving solutions for overcoming system weaknesses
- Achieving organizational goals

### System Design
> [!abstract] System Design
> The process of specifying the new system, detailing tasks to be carried out and data to be input, output, and stored.

**Design Phases**:
1. **Logical Design** - Specifies functions to be carried out without tying them to specific hardware or software.
2. **Physical Design** - Provides precise details of hardware, software, file formats, etc.

---

## 6. System Analyst

### Role and Responsibilities
> [!abstract] System Analyst
> A professional in charge of analyzing, designing, and modifying systems to ensure compatibility and user effectiveness.

### System Analyst Skills

#### 1. Analytical Skills
The analyst must possess system thinking, organizational knowledge, problem identification, and problem-solving skills.

- **System Thinking**: The analyst must view everything as a system.
- **Organizational Knowledge**: Must understand the functions and procedures of the organization they work for.
- **Problem Identification**: Must define differences by comparing the current situation to predicted outputs.
- **Problem Analyzing and Solving**: Must analyze problems through four phases:
  1. **Intelligence** - Collect all relevant information
  2. **Design** - Formulate alternatives
  3. **Choice** - Select the best alternative solution
  4. **Implementation** - Put solution into practice

#### 2. Technical Skills
- Understand how various technologies work
- Know potentials and limitations of technologies
- Possess technical know-how of different notations for representing/modeling information systems

#### 3. Management Skills
- Know how to manage work effectively
- Use organizational resources productively
- Demonstrate resource, project, risk, and change management skills

#### 4. Interpersonal Skills
- Communication skills
- Group facilitation skills
- Skills to manage expectations of users and managers

### Roles of System Analyst
1. Business Analysis
2. Requirements Elicitation (producing requirements)
3. Infrastructure Analysis
4. Change Management (providing adequate documentation and support to users)
5. Project Management

---

## 7. System Development Life Cycle (SDLC)
> [!abstract] SDLC
> A common methodology for systems development that features several phases marking the progress of system analysis and design effort.

### SDLC Phases (Waterfall Model)

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

> [!note] Milestones and Deliverables
> At the end of each phase (and sometimes within phases for intermediate steps), a project reaches a milestone. Deliverables produced are often reviewed by parties outside the project team.

### Phase 1: Project Identification and Selection
**Purpose**: Identify the need for a new or enhanced system.

**Activities**:
- Examine needs resulting from:
  - Problems in current procedures
  - Desire to perform additional tasks
  - Realization that IT could capitalize on existing opportunities
- Prioritize identified needs
- Translate needs into a development schedule

**Outcome**: Determination of which system development projects should be undertaken based on available resources.

### Phase 2: Project Initiation and Planning
**Purpose**: Investigate the system problem or opportunity and determine project feasibility.

**Activities**:
1. **Investigation**: Examine the system problem or opportunity at hand
2. **Justification**: Present reasons why the system should or should not be developed
3. **Scope Determination**: Define the boundaries of the proposed system
4. **Project Planning**: Produce a specific plan including:
   - Time requirements
   - Resource requirements
   - Execution strategy

**Key Question**: Do the benefits of developing the system outweigh the costs?

### Phase 3: Analysis
**Purpose**: Thoroughly study current procedures and information systems.

**Activities**:
1. **Requirement Determination**: Determine what users want from the proposed system through careful scrutiny of current systems (manual or computerized).
2. **Requirement Structuring**: Study requirements, structure them according to interrelationships, and eliminate redundancy.
3. **Alternative Generation**: Generate alternative initial designs that match the requirements.
4. **Alternative Comparison**: Compare generated alternatives to determine the best fit within cost, labor, and technical constraints.

**Outcome**: A description (but not detailed design) of the recommended alternative solution.

### Phase 4: Design
**Purpose**: Convert the recommended solution into logical and physical system specifications.

**Two Design Types**:

1. **Logical Design**: Independent of any specific hardware or software platform
   - Concentrates on business aspects of the system
   - Oriented to high-level specificity

2. **Physical Design**: Provides precise details of:
   - Hardware specifications
   - Software specifications
   - File formats
   - Physical operations for data capture, processing, and information output

**Outcome**: Physical specifications of the designed system (as a model or detailed documentation) to guide system builders.

### Phase 5: Implementation
**Purpose**: Turn system specifications into a working system.

**Activities**:
1. **Coding**: Programmers write the programs that make up the system
2. **Testing**: Programmers and analysts test:
   - Individual programs
   - The entire system
   - Find and correct errors
3. **Installation**: 
   - Load system on new or existing hardware
   - Introduce users to the new system
   - Provide user training

**Outcome**: A working, tested system in daily organizational use.

### Phase 6: Maintenance
**Purpose**: Keep the system running and useful over time.

**Activities**:
- Fix problems discovered by users
- Modify system to reflect changing business needs
- Implement user suggestions for improvements

> [!note] Ongoing Phase
> Maintenance is an overlay to the life cycle. It continues throughout the system's operational life.

---

## 8. System Development Methodologies

### 1. Structured System Analysis and Design
> [!abstract] Structured SAD
> Uses a series of phases (SDLC) incorporating process models to describe a system graphically.

**Key Features**:
- Uses process models to show data flow in and out of system processes
- Addresses data organization and structure
- Includes relational database design
- Handles user interface issues
- Emphasizes partitioning (dividing problems into smaller, manageable units)
- Makes clear distinction between physical and logical design

**Milestone-Based Approach**:
- Phases end when milestones are reached
- Milestones typically take the form of deliverables or pre-specified outputs
- Easier to return to earlier phases when necessary

### 2. Object-Oriented Analysis and Design (OOAD)
> [!abstract] OOAD
> Combines data and processes (methods) into single entities called objects.

**Key Concepts**:
- Objects correspond to real things an information system deals with (customers, suppliers, contracts, agreements, etc.)
- Goal is to make system elements more reusable
- Improves system quality and productivity

**Object-Oriented Analysis (OOA)**:
- Identify objects
- Define object structures and behaviors
- Define object relationships

**Object-Oriented Design (OOD)**:
- Model details of object behavior
- Model object communication
- Ensure system requirements are met
- Reexamine and redefine to take advantage of object-orientation benefits

### 3. Agile/Adaptive Methods
> [!abstract] Agile
> Attempts to make system development less of an art and more of a science by applying rigorous engineering techniques.

**Key Features**:
- System developed incrementally
- Builds a series of prototypes
- Constantly adjusts to user requirements
- Developers revise, extend, and merge earlier versions into the final product

**Philosophy**:
- Emphasizes continuous feedback
- Each incremental step is affected by learning from prior steps
- Has attracted a wide following and entire community of users

---

## 9. Methodology Comparison
| **Aspect**         | **Structured SAD**                                                                                                          | **Object-Oriented AD**                                                                                                                 | **Agile/Adaptive Methods**                                                                                                                  |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description**    | Represents system in terms of data and processes. Organized into phases with deliverables and milestones. Iteration possible. | Views system as objects combining data and processes. More iterative approach.                                                          | Stresses team-based efforts. Breaks development into cycles/iterations. Reduces risks through incremental steps in short intervals.         |
| **Modeling Tools** | Data Flow Diagrams (DFD), Process descriptions                                                                              | Various OO diagrams depicting system actors, methods, and messages                                                                     | Communication tools: collaborative software, brainstorming, whiteboards                                                                     |
| **Pros**           | Heavy documentation. Flexible phase iteration. Well-suited to project management tools.                                     | Integrates with OO programming languages. Modular, reusable code. Easy maintenance and expansion through inheritance.                  | Very flexible with change. Strong team interaction. Frequent deliverables validate project and reduce risk.                                 |
| **Cons**           | Changes costly in later phases. Early requirement definition can become outdated. Users may not know needs until seeing examples. | Object and class interactions can be complex in larger systems.                                                                        | Requires high technical and communication skills. Lack of structure/documentation introduces risk. Subject to scope change. |

---

> [!tip] Study Summary
> System Analysis and Design involves understanding how systems work, identifying their components, and developing methodologies to build effective information systems. The SDLC provides a structured approach, while different methodologies (Structured, OO, Agile) offer various ways to tackle system development challenges.
