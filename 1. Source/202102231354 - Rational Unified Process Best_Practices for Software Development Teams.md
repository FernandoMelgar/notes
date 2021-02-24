#Project-Management #Software-Engineering 
# 202102231354 - Rational Unified Process: Best Practices for Software Development Teams
**source:** https://www.ib	m.com/developerworks/rational/library/content/03July/1000/1251/1251_bestpractices_TP026B.pdf

---
#### What is the rational unified process?
The Rational Unified Process is a **Software Engineering Process**. It provides a **disciplined** approach to **assigning tasks** and **responsibilities** within a development organization. Its goal is to ensure the production of high-quality software that meets the needs of its end-users, within a **predictable schedule and budget**.
- **Software Engineering Process**: Has a well defined order of phases and also transitions criteria between this phases.
- **Disciplined**: Has a process and set of instructions that need to be follow.
- **Assigning task**: Task are defined an refined during planning.
- **Responsibilities**: We know in every moment who is in charge of something.
- **Predictable schedule and budget**: We can rely on a system planning for timing, distribution of activities and budget.

#### Unified knowledge base for the team
The Rational Unified Process enhances team productivity, by providing every team member with easy access to a knowledge base with guidelines, templates and tool mentors for all critical development activities. By having all team members accessing the same knowledge base, we ensure that all team members share a common language, process and view of how to develop software.

#### Phases and iterations - the timeline dimension
This is the dynamic organization of the process along time. The software life-cycle is broken into cycles. **RUP** divides one development cycle in four consecutive phases.
- Inception phase.
- Elaboration phase .
-  Construction phase.
-  Transition phase. 

==Each phase is concluded with a well-defined milestone==—a point in time at which certain critical decisions must be made, and therefore key goals must have been achieved.

##### Inception phase
During the inception phase, you ==establish the business case== for the system and ==delimit the project scope==. For this, you need to ==identify all external entities with which the system will interact (actors)== and define the nature of the interactions at a high level. This involves ==identifying all use cases ==and describing a few significant ones.

> The business case includes success criteria, risk assessment, and estimate of the resources needed, and a phase plan showing dates of major milestones. The outcome of the inception phase is:

The outcome of the inception phase is:
- **A vision document**: a general vision of the core project's requirements, key features, and main constraints. 
- A initial use-case model (10% -20%) complete). 
- An initial project glossary (may optionally be partially expressed as a domain model). 
- An initial business case, which includes business context, success criteria (revenue projection, market recognition, and so on), and financial forecast.
- An initial** risk assessment**. 
- A **project plan**, showing phases and iterations. 
-  A business model, if necessary. 
-   One or several prototypes.

###### Milestone : Life-cycle Objectives
At the end of the inception phase is the first major project milestone: the Lifecycle Objectives Milestone. The evaluation criteria for the inception phase are:
- Stakeholder concurrence on scope definition and cost/schedule estimates.
- Requirements understanding as evidenced by the fidelity of the primary use cases. 
- Credibility of the cost/schedule estimates, priorities, risks, and development process. 
- Depth and breadth of any architectural prototype that was developed.
- Actual expenditures versus planned expenditures. 

**The project may be cancelled or considerably re-thought if it fails to pass this milestone.
**

##### Elaboration Phase
==The purpose of the elaboration phase is to analyze the problem domain, establish a sound architectural foundation, develop the project plan, and eliminate the highest risk elements of the project==. It is easy to argue that the elaboration phase is the most critical of the four phases. At the end of this phase, the hard “engineering” is considered complete and the project undergoes its most important day of reckoning: the decision on whether or not to commit to the construction and transition phases. For most projects, this also corresponds to the transition from a mobile, light and nimble, low-risk operation to a high-cost, high-risk operation with substantial inertia. While the process must always accommodate changes, the elaboration phase activities ensure that the architecture, requirements and plans are stable enough, and the risks are sufficiently mitigated, so you can predictably determine the cost and schedule for the completion of the development. Conceptually, this level of fidelity would correspond to the level necessary for an organization to commit to a fixed-price construction phase.

**The outcome of the elaboration phase is:** 
- A use-case model (at least 80% complete) — all use cases and actors have been identified, and most use case descriptions have been developed. 
- Supplementary requirements capturing the non functional requirements and any requirements that are not associated with a specific use case.
-  A Software Architecture Description. 
-  An executable architectural prototype. 
-  A revised risk list and a revised business case. 
-  A development plan for the overall project, including the coarse-grained project plan, showing iterations” and evaluation criteria for each iteration.
-   An updated development case specifying the process to be used.
-   A preliminary user manual (optional).

###### Milestone : Lifecycle Architecture
At this point, you examine the detailed system objectives and scope, the choice of architecture, and the resolution of the major risks.

The main evaluation criteria for the elaboration phase involves the answers to these questions:
- Is the vision of the product stable? 
- Is the architecture stable? 
- Does the executable demonstration show that the major risk elements have been addressed and credibly resolved? 
- Is the plan for the construction phase sufficiently detailed and accurate? Is it backed up with a credible basis of estimates?
- Do all stakeholders agree that the current vision can be achieved if the current plan is executed to develop the complete system, in the context of the current architecture? 
- Is the actual resource expenditure versus planned expenditure acceptable?

**The project may be aborted or considerably re-thought if it fails to pass this milestone.**

##### Construction Phase
During the construction phase, all remaining components and application features are developed and integrated into the product, and all features are thoroughly tested. ==The construction phase is, in one sense, a manufacturing process where emphasis is placed on managing resources and controlling operations to optimize costs, schedules, and quality.== In this sense, ==the management mindset undergoes a transition from the development of intellectual property during inception and elaboration, to the development of deployable products during construction and transition==.

The outcome of the construction phase is a product ready to put in hands of its end-users. At minimum, it consists of: 
- The software product integrated on the adequate platforms. 
- The user manuals. 
- A description of the current release.

###### Milestone : Initial Operational Capability
At the end of the construction phase is the third major project milestone (Initial Operational Capability Milestone). At this point, you decide if the software, the sites, and the users are ready to go operational, without exposing the project to high risks. This release is often called a **“beta” release.**

The evaluation criteria for the construction phase involve answering these questions:
- Is this product release stable and mature enough to be deployed in the user community? 
- Are all stakeholders ready for the transition into the user community? 
- Are the actual resource expenditures versus planned expenditures still acceptable?

**Transition may have to be postponed by one release if the project fails to reach this milestone.**

##### Transition Phase
==The purpose of the transition phase is to transition the software product to the user community==. Once the product has been given to the end user, issues usually arise that require you to develop new releases, correct some problems, or finish the features that were postponed.

This includes: 
- “beta testing” to validate the new system against user expectations
-  Parallel operation with a legacy system that it is replacing 
-  Conversion of operational databases 
-  Training of users and maintainers.
-  Roll-out the product to the marketing, distribution, and sales teams.

Considerable effort is expended in developing user-oriented documentation, training users, supporting users in their initial product use, and reacting to user feedback. At this point in the lifecycle, however, user feedback should be confined primarily to product tuning, configuring, installation, and usability issues.
The primary objectives of the transition phase include:
- Achieving user self-supportability.
- Achieving stakeholder concurrence that deployment baselines are complete and consistent with the evaluation criteria of the vision.
- Achieving final product baseline as rapidly and cost effectively as practical.

###### Milestone: Product Release
At this point, you decide if the objectives were met, and if you should start another development cycle. In some cases, this milestone may coincide with the end of the inception phase for the next cycle.

The primary evaluation criteria for the transition phase involve the answers to these questions: 
- Is the user satisfied?
- Are the actual resources expenditures versus planned expenditures still acceptable?

#### Static structure of the process.

==*A process describes* **who** is doing **what**, **how**, and **when**.==

The Rational Unified Process is represented using four primary modeling elements:
- **Workers** the **who**.
- **Activities** the **how**.
- **Artifacts** the **what**.
- **Workflows** the **when**.
![](https://i.imgur.com/xGdxzpr.png)

##### Worker
A worker defines the behavior and responsibilities of an individual, or a group of individuals working together as a team. **You could regard a worker as a "hat" an individual can wear in the project.** One individual may wear many different hats. This is an important distinction because it is natural to think of a worker as the individual or team itself, but in the Unified Process the worker is more the role defining how the individuals should carry out the work. The responsibilities we assign to a worker includes both to perform a certain set of activities as well as being owner of a set of artifacts
![](https://i.imgur.com/Dez5pFH.png)

> The way you work depends on the role you take.

##### Activity
==An activity of a specific worker is a unit of work that an individual in that role may be asked to perform.== The activity has a clear purpose, usually expressed in terms of creating or updating some artifacts, such as a model, a class, a plan. Every activity is assigned to a specific worker. **An activity should be usable as an element of planning and progress**; if it is too small, it will be neglected, and if it is too large, progress would have to be expressed in terms of an activity’s parts.

##### Artifact
An artifact is a piece of information that is produced, modified, or used by a process. Artifacts are the tangible products of the project, the things the project produces or uses while working towards the final product. ==Artifacts are used as input by workers to perform an activity, and are the result or output of such activities==. In object-oriented design terms, as activities are operations on an active object (the worker), artifacts are the parameters of these activities.

##### Workflow
A mere enumeration of all workers, activities and artifacts **does not** quite constitute a process. We need a way to describe meaningful sequences of activities that produce some valuable result, and to show interactions between workers.

> A workflow is a sequence of activities that produces a result of observable value.

#### Core workflows
**There are nine core process workflows in the Rational Unified Process**, which represent a partitioning of all workers and activities into logical groupings.

The core process workflows are divided into six core “engineering” workflows:
1. Business modeling workflow.
2. Requirements workflow.
3. Analysis & Design workflow.
4. Implementation workflow.
5. Test workflow.
6. Deployment workflow. 

And three core “supporting” workflows: 
1. Project Management workflow.
2. Configuration and Change Management workflow.
3. Environment workflow.

##### Business modeling
==One of the major problems with most business engineering efforts, is that the software engineering and the business engineering community do not communicate properly with each other==. This leads to the output from business engineering is not being used properly as input to the software development effort, and vice-versa. The Rational Unified Process addresses this by providing a common language and process for both communities, as well as showing how to create and maintain direct traceability between business and software models.

In business modeling there is a documentation of the business process in what is called **business use case**. This assures a common understanding among all stakeholders of what business process needs to be supported in the organization. This is documented in a business object-model.

##### Requirements 
==The goal of the Requirements workflow is to describe **what the system should do** and allows the **developers and the customer to agree** on that description.== To achieve this, we elicit, organize, and document required functionality and constraints; track and document trade offs and decisions.

A Vision document is created, and stakeholder needs are elicited. Use cases are identified, representing the behavior of the system. Each use case is described in detail. The use-case description shows how the system interacts step by step with the actors and what the system does. Non-functional requirements are described in Supplementary Specifications.

##### Analysis and design
**See also:**
- [[202102211220 Udacity - Rational Unified process]]
- [[202102171903 - La importancia del project management]]
- [[202102181349- Introducción a Poject Management]]
