## Getting Started
### Prerequisites 

To contribute, you must first complete the following prerequisites:

- **Sign the Contributor License Agreement (CLA)**: You must sign the FOCUS Corporate Contributor License Agreement (CLA) available at <a href="https://github.com/FinOps-Open-Cost-and-Usage-Spec/EasyCLA" target="_blank">EasyCLA</a>.

    > Note: FOCUS does not accommodate Individual Contributors for the CLA.

- **Join the Organization**: After signing the EasyCLA, our staff will invite you to join:
    *  Slack <a href="https://app.slack.com/client/TH7CE9HP1/C053CNCRVCL" target="_target">FOCUS-signed-members</a>, 
    * Google Groups, <a href="https://groups.google.com/" target="_blank">FOCUS Groups</a>, and 
    * GitHub <a href="https://github.com/orgs/FinOps-Open-Cost-and-Usage-Spec/repositories" target="_blank">FOCUS organization</a>. 
    > You will receive WRITE access after sending an email to <a mailto="xxxx@finops.org" target="_blank"> xxxxx@finops.org</a>.

- **Repository Access**: Key branches are restricted; only maintainers and administrators can merge content on them. While there is no need to fork this repository, you may clone it locally for command-line work. Contact <a mailto="xxxx@finops.org" target="_blank"> xxxxx@finops.org</a> for any questions.

### Get Familiar with FOCUS Work

Understand our workflow and contribution process:

- **FOCUS Process Diagram**: Familiarize yourself with the diagrams representing collaboration in a FOCUS Project.
    * [Specification Life-Cycle Stages](): Stages to build a Technical Specification
    * [Development Stage](): How to build consensus and develop FOCUS Technical Specifications in GitHub.
- **RELEASE PLANNING.md**: This document contains the Specification roadmap. Check here for upcoming release versions, schedules, and high-level feature plans.
- **CONTRIBUTING.md**: Review this document to understand how to work on the repository.

    > **Note**: Every FOCUS repository with release material SHOULD contain the `RELEASE PLANNING.md` and `CONTRIBUTING.md` files.

## Technical Specifications Life-Cycle
![image](https://github.com/standards-hub/test/assets/3258579/da37f18e-4883-4577-9dd3-d0bf37e96480)

The Specifications Life-Cycle is a structured process that outlines the steps involved in the creation, development, approval, and publication of a set of specifications. This process ensures that the specifications are thoroughly reviewed and meet the necessary criteria before becoming publicly available. The life-cycle can be broken down into several key stages:

### Draft Phase

#### Work Item Creation
- The process begins with the creation of a work item. This is the initial concept or proposal for the specifications. A release MAY contain one or more work items.

#### Specifications Development
- Once the work item is approved, the specifications are developed. This involves detailed work and may go through several iterations, including bug fixes.

#### Consistency Review
- After development, the specifications undergo a consistency review to ensure all elements are aligned and meet the predefined criteria.

#### Final Spec Working Group Approval
- The developed specifications are presented to the working group for final approval.

### Approved Phase

#### Steering Committee Ratification
- Following approval from the working group, the specifications are forwarded to the steering committee for ratification.

### Publicly Available Phase

#### Publication
- Once ratified, the specifications are published and made publicly available.

#### Feedback
- After publication, feedback is collected for potential inclusion in future versions or bug fixes.

The process is iterative, with the possibility of creating new versions of the specifications as needed.

## Work Item Creation

## Specification Development
Sandwiched between the "Work Item" initiation and the "Consistency Review", the "Specification Development" phase encapsulates the entire GitHub-driven workflow. It represents a significant phase in the specification life-cycle where the proposed items are fleshed out, debated, refined and approved until they are ready for the final consistency check, ensuring alignment with the overarching goals and existing standards.

![image](https://github.com/standards-hub/test/assets/3258579/4ca9ea87-b54f-468b-afd7-4fc33075a5ee)

This diagram is a reference for contributors, providing a clear and organized path from the creation of items (Issues and Pull Requests) to its final Review and Approval. It emphasizes the collaborative nature of the process and the critical role of consensus in developing robust, widely-accepted standards.

The diagram maps the workflow of specification development using GitHub. It outlines a structured approach to progressing from the initial concept of a work item to the final consistency review, framed within both consensus stages and GitHub Workflow.

Here's a detailed description of the diagram:

### Consensus Process

The development of standards within any organization is a meticulous process that requires a structured approach to ensure broad agreement and quality outcomes. The consensus stages described here outline the essential steps taken by standards organizations to reach an agreement when developing specifications and changes. This content serves to explain the inner workings of these stages, providing clarity on how consensus is achieved in a systematic and inclusive manner. In the following section, we will explore how these consensus stages are practically applied using a GitHub Project workflow, demonstrating a real-world process of collaboration and decision-making. This implementation is not only practical but also aligns with contemporary methods of software development and project management, thus exemplifying a modern approach to standards development. These are the consensus stages:

#### Creation:
In the initial "Creation" stage, Working Group (WG) members initiate the process by generating issues and pull requests (PRs) against a specific release. This marks the conceptual inception of new features and signifies the beginning of the specification development process.

#### Discussion:
Subsequently, the "Discussion" stage provides a platform for dynamic engagement among maintainers and WG members. Through the collaborative examination and enhancement of ideas, this phase ensures that issues are fully vetted and, if meritorious, transformed into actionable Pull Requests.

#### Review & Approval:
As we progress to the "Review & Approval" stage, there is a shift to meticulous scrutiny by WG members. It is here that the proposals are subjected to a thorough review, ensuring they meet the organization's exacting standards for approval.

#### Merged or Closed:
Finally, we reach the decisive point of the consensus stages. In "Merged or Closed," the fate of each PR is determined: those that achieve approval are merged, signaling the successful addition of a new or improved feature to the standard. Those that fail to meet the consensus Approval Criteria are closed, thus concluding their journey without integration. This stage marks the resolution of the consensus process and sets the stage for the next cycle of development and improvement.

### GitHub Project Workflow
To effectively bridge the Standards Consensus Process stages with practical application, the FinOps FOCUS project leverages GitHub Workflows, enabling transparent and efficient tracking of each stage's progress within the [FOCUS WG](https://github.com/orgs/FinOps-Open-Cost-and-Usage-Spec/projects/5) Project. These are the Project Status:

#### Triage: 
As the inception point within the GitHub environment, items are initially triaged by maintainers. This sorting process is essential for prioritizing tasks and streamlining the workflow.
    >New Items are automatically assigned to this stage.

#### Parking Lot: 
Identified by the qualifier "In & Out," this stage serves as a temporary hold for items that, while acknowledged as important, are not immediately actionable. The work on these items is paused, often due to external dependencies or strategic considerations.

#### Work in Progress: 
Task forces come into play, getting into active discussions on the items assigned to the Task Force. It's a hive of collaborative effort, where the groundwork for the specifications is laid out and iteratively refined.

#### Review & Approval: 
Post-discussion, items deemed technically complete are forwarded to the WG for final approval. This is a critical gatekeeping phase where standards are scrutinized before formally integrate them into the Specification baseline.

#### Merged or Closed:
The process concludes with the merging of agreed-upon PRs. Alternatively, issues that garner consensus may be transitioned into PRs for integration. Some items may be closed if the WG decides no action is necessary.

## Consistency Review

## SC Ratification

## Publication