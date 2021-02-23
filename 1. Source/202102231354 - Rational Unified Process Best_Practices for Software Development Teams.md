#Project-Management #Software-Engineering 
# 202102231354 - Rational Unified Process: Best Practices for Software Development Teams
**source:** https://www.ibm.com/developerworks/rational/library/content/03July/1000/1251/1251_bestpractices_TP026B.pdf

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
**See also:**
- [[202102211220 Udacity - Rational Unified process]]
- [[202102171903 - La importancia del project management]]
- [[202102181349- Introducción a Poject Management]]
