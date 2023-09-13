# Integrate airflow using OpenLineage

## Problem Statement
Integrate Airflow into Atlan using OpenLineage

## Background

Airflow, as a workflow orchestration platform, empowers data engineers to create and oversee their data pipelines. However, addressing runtime issues and outages in complex pipelines becomes a humongous task without easily accessible traceability. When a pipeline malfunctions, data engineers are forced to respond manually, leading to increased data downtime, hence big probability of business impact.

Data consumers (business stakeholders) lacks visibility into the operational aspects of upstream data sets, including job frequency, processing duration and other data quality metrics. The absence of transparency in data pipelines and their downstream utilization gives rise to trust issues concerning the data's reliability.


## Goals

 - Collect operational metadata from Airflow DAGs for visualization in Atlan.
 - Offer visibility into operational flow within Atlan's lineage to enhance understanding of pipeline issues.
 - Enable Data Engineers to effectively troubleshoot data flow pipeline issues, reducing both mean time to detect and mean time to resolve data-related problems.
 - Gain a deeper understanding of the timeliness and reliability of source and target data to boost confidence in data integrity.


## Non-Goals or Out of Scope

 - Airflow integration of showing DAG and other related artifacts in Airflow is out of scope
 
 

## Future Goals

Product and technical requirements slated for a future time

## Assumptions

 - Airflow enabled with OpenLineage


### Suggested or Proposed Solution / Design



External components that the solution will interact with and that it will alter
Dependencies of the current solution
Pros and cons of the proposed solution
Data Model / Schema Changes
Schema definitions
New data models
Modified data models
Data validation methods
Business Logic
API changes
Pseudocode
Flowcharts
Error states
Failure scenarios
Conditions that lead to errors and failures
Limitations
Presentation Layer
User requirements
UX changes
UI changes
Wireframes with descriptions
Links to UI/UX designer’s work
Mobile concerns
Web concerns
UI states
Error handling
Other questions to answer
How will the solution scale?
What are the limitations of the solution?
How will it recover in the event of a failure?
How will it cope with future requirements?

## Test Plan

Explanations of how the tests will make sure user requirements are met
Unit tests
Integrations tests
QA

## Monitoring and Alerting Plan

Logging plan and tools
Monitoring plan and tools
Metrics to be used to measure health
How to ensure observability
Alerting plan and tools

## Release / Roll-out and Deployment Plan

Deployment architecture
Deployment environments
Phased roll-out plan e.g. using feature flags
Plan outlining how to communicate changes to the users, for example, with release notes

## Rollback Plan

Detailed and specific liabilities
Plan to reduce liabilities
Plan describing how to prevent other components, services, and systems from being affected

## Alternate Solutions / Designs

Short summary statement for each alternative solution
Pros and cons for each alternative
Reasons why each solution couldn’t work
Ways in which alternatives were inferior to the proposed solution
Migration plan to next best alternative in case the proposed solution falls through

## Further Considerations
a. Impact on other teams

How will this increase the work of other people?
b. Third-party services and platforms considerations

Is it really worth it compared to building the service in-house?
What are some of the security and privacy concerns associated with the services/platforms?
How much will it cost?
How will it scale?
What possible future issues are anticipated?
c. Cost analysis

What is the cost to run the solution per day?
What does it cost to roll it out?
d. Security considerations

What are the potential threats?
How will they be mitigated?
How will the solution affect the security of other components, services, and systems?
e. Privacy considerations

Does the solution follow local laws and legal policies on data privacy?
How does the solution protect users’ data privacy?
What are some of the tradeoffs between personalization and privacy in the solution?
f. Regional considerations

What is the impact of internationalization and localization on the solution?
What are the latency issues?
What are the legal concerns?
What is the state of service availability?
How will data transfer across regions be achieved and what are the concerns here?
g. Accessibility considerations

How accessible is the solution?
What tools will you use to evaluate its accessibility?
h. Operational considerations

Does this solution cause adverse aftereffects?
How will data be recovered in case of failure?
How will the solution recover in case of a failure?
How will operational costs be kept low while delivering increased value to the users?
i. Risks

What risks are being undertaken with this solution?
Are there risks that once taken can’t be walked back?
What is the cost-benefit analysis of taking these risks?
j. Support considerations

How will the support team get across information to users about common issues they may face while interacting with the changes?
How will we ensure that the users are satisfied with the solution and can interact with it with minimal support?
Who is responsible for the maintenance of the solution?
How will knowledge transfer be accomplished if the project owner is unavailable?
## Success Evaluation
a. Impact

Security impact
Performance impact
Cost impact
Impact on other components and services
b. Metrics

List of metrics to capture
Tools to capture and measure metrics
## Work
a. Work estimates and timelines

List of specific, measurable, and time-bound tasks
Resources needed to finish each task
Time estimates for how long each task needs to be completed
b. Prioritization

Categorization of tasks by urgency and impact
c. Milestones

Dated checkpoints when significant chunks of work will have been completed
Metrics to indicate the passing of the milestone
d. Future work

List of tasks that will be completed in the future

