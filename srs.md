# Project Name
## Software Requirements Specification
> This template is a simplified version based on the documentation templates from IBM Rational Unified Process (RUP).
### 1. Introduction
#### 1.1 Overview
> What are the selling points of your application?
#### 1.2 Scope
> What is covered (not covered) in this document? Is it for your whole system or a subsystem? Does it cover both functional and nonfunctional requirements? (Will you seperate some of requirements into another document?)
#### 1.3 Definitions, Acronyms and Abbreviations
> Definitions of all terms, acronyms, and abbreviations required to properly interpret this document.
#### 1.4 References
> A complete list of all documents referenced. Each document should be identified by title, date, and publishing organization. You can also insert hyperlinks, in order to open the references conviniently.

### 2. Functional requirements
>  This section contains all the software requirements to a level of detail sufficient to enable designers to design a system to satisfy those requirements and testers to test that the system satisfies those requirements.  
>  This section is typically organized by feature, but alternative organization methods may also be appropriate, for example, organization by user or organization by subsystem.

> [!NOTE]
> You can insert links to your UML diagrams and user stories, or labels of user stories into this document.

#### 2.1 Overview 
> A brief description of the functionality of your application.  
> Include one or more **UML use case** diagram(s) and necessary description to specify the major use cases of your application.

#### 2.2 Name of Feature 1 / Use Case 1
> Specify this feature / use case by:
> - Relevant **user stories (their links or labels)**
> - **UI mockups**
> - **UML behavior diagrams** and necessary text specification
> - **Preconditions**. *A precondition of a use case is the state of the system that must be present prior to a use case being performed.*
> - Postconditions. *A postcondition of a use case is a list of possible states the system can be in immediately after a use case has finished.*
> - **Estimated efforts (high, medium, low)**


#### 2.3 Name of Feature 2 / Use Case 2
... ...

### 3. Nonfunctional requirements

> [!NOTE]  
> It is not necessary to cover all of the following ASRs (Architecturally Significant Requirements), but focus on what your project will implement.  
> If some ASRs are described as user stories in your backlog, add their **links** in this section, or any information to guide the reader find them in your backlog, such as a **label** of those relevant user stories.

> Categories: Availability, Performance, (Energy) Efficiency, Deployability, Integrability, Modifiability, Testability, Safety, Security, Usability

#### 3.1 Utility tree

| Quality attribute    | Refinement             | Quality attribute scenarios   | Business value | Technical risk  |
| :---                 | :----                  | :----                         | :----          | :----           | 
| e.g. Availability    | e.g. data loss         | Scenario 1.1  who/what, Event, Influence, Condition, Action, Measurement                |  e.g. H        | e.g., L         |
|                      |                        | Scenario 1.2                  |  e.g. M        | e.g., L         |
|                      | e.g. hardware issue    | Scenario 2.1                  |  e.g. H        | e.g., L         |
| e.g. Security        | ... ...                |                               |                |                 |

> [!IMPORTANT]
> When specifying the quality attribute scenarios, cover 6 aspects: who/what, Event, Influence, Condition, Action, Measurement

#### 3.2 Tactics for Top 3 quality attribute scenarios

##### 3.2.1 ...

##### 3.2.2 ...

##### 3.2.3 ...

### 4. Technical constraints
> Specify any major constraints, assumptions or dependencies, e.g., any restrictions about which type of server to use, which type of open source license must be complied, etc. 
