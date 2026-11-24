# PRODUCT REQUIREMENTS DOCUMENT

## CAMPUS LOST AND FOUND SYSTEM

META DETAILS

| DETAIL | INFORMATION |
| --- | --- |
| Product Title | Campus Retrieve |
| Document Version | 1.0 |
| Date Created | 23rd November, 2026 |
| Product Manager | TBD |
| Design Point of Contact | TBD |
| Technical Point of Contact | TBD |
| Marketing Point of Contact | TBD |

PRODUCT OBJECTIVES

### Business Objective

The system aims to provide a centralized and organized platform for managing lost and found items on campus, reducing the difficulty of locating misplaced belongings and improving the recovery process.

### User Objective

It aims to enable students to easily report lost and found belongings, search for reported items, and access information about missing belongings through a centralized platform. It will reduce the dependence on word-of-mouth communication, scattered group chat announcements and physical visits to security offices trying to recover their belongings.

### Problem Being Solved

The current process of returning lost belongings on Campus relies heavily on word-of-mouth communication and announcements across different departmental group chats. This makes it difficult for students to locate their belongings, particularly when the person who finds an item does not know its owner or belong to the same department and while items like an id card may be identifiable and easier to announce, unnamed items such as headphones, chargers and other belongings may be difficult to identify through just a group chat. As a result of this, students may remain unaware that their missing item has been found simply because information never reaches them.

### Business Value

The campus lost and found system will improve the recovery of misplaced belongings within the campus community. It will give students a reliable place to check when they lose personal belongings, improving their confidence in the campus recovery process. It also reduces the workload of campus security by reducing the need for repeated enquiries and unnecessary CCTV checks for minor lost item cases.

HOW DO WE MEASURE SUCCESS

### Success Metrics

The primary measure of success for the Campus Lost and Found System will be the successful recovery of lost belongings by their rightful owners. While the number of lost and found reports, active users, and item searches can indicate platform engagement, these figures alone do not establish success. The system will be considered effective when students can successfully connect with information about their missing belonging and retrieve them. That is what will build student confidence in the lost and found recovery process.

### Guardrail Metrics

The system must prioritize the safe and rightful return of recovered belongings. To minimize false claims and unauthorized collection, found item reports should not reveal all identifying details of an item. Students claiming an item must provide additional information about its appearance, distinguishing features, circumstances surrounding its loss or some sort of proof of ownership. This information will be compared with the original report before the item is released. The system will also monitor unsuccessful ownership claims and reports of incorrectly released items to identify weaknesses in the verification process.

USERS

Students

Students are the primary users of the platform. They should be able to

Report belongings they have lost

Report items they have found

Browse and search reported items

Submit descriptions and information to support ownership verification

Track the status of their reports and recovery requests

Lost and Found Administrator

The administrator is responsible for managing the platform’s lost and found records. They should be able to

View and manage lost and found reports

Review claims submitted by students

Compare ownership information and verify claims

Update item statuses

Record successful item recoveries

PROBLEMS WE ARE SOLVING

Fragmented Communication: Lost and Found announcement are scattered across different class and departmental group chats, making them difficult to track.

Difficulty Identifying Item Owners: Students who find belongings may not know their owners, particularly when the items are found outside the owner’s department or social circle.

Lack of a Centralized Reporting Platform: There is no single accessible platform where students can report, search for and track lost and found belongings.

Unverified Ownership Claims: Without a structured verification process, returning found belongings to the rightful owners can be difficult.

PROBLEM VALIDATION AND RESEARCH

### Initial Observation

The need for a centralized campus lost and found platform was identified through personal observations of how students currently handle lost and found belongings. Existing practices often involve sharing announcements through class and WhatsApp groups or relying on word of mouth communication. These methods do not guarantee that information reaches the rightful owners, particularly when the person who finds an item does not know its owner or belong to the same academic group. This highlights the need for a more organized and accessible system for reporting and recovering lost belongings.

### Jobs to Be Done

“When students lose or find personal belongings on campus, they want a centralized platform where they can report, search and identify missing items so that lost belongings can be reunited with their rightful owners”.

### The Five Ways

| WHY? | EXPLANATION |
| --- | --- |
| Why do students struggle to recover lost belongings? | Information about found items does not always reach them. |
| Why doesn’t the information reach them? | Announcements are scattered across different groups and social circles |
| Why is this a problem? | The finder may not know the owner or belong to the same group |
| Why can’t students easily find the information elsewhere? | There is no centralized reporting platform |
| Why is a centralized reporting platform needed? | To connect students who lose belongings with those who find them through an organized recovery process. |

STAKEHOLDERS

The Campus Lost and Found System involves several stakeholders whose participation or support is important to its successful implementation and operation.

| STAKEHOLDERS | INTEREST AND INVOLVEMENT |
| --- | --- |
| Students | Use the platform to report lost and found belongings, search for items and submit ownership claims. |
| Lost and Found Administrator | Manages reports, reviews ownership claims, updates item statuses and records successful recoveries. |
| School Management | Provides institutional approval and support for the implementation and operation of the system. |
| Campus Security | May support the physical safekeeping and collection of recovered belongings where necessary. |

USER STORIES

The following user stories describe the needs of the main users of the system.

### Student User Stories

- As a student, I want to report a lost item so that other students can help identify and return it.
- As a student, I want to report an item I have found so that its rightful owner can locate it.
- As a student, I want to search and browse reported items so that I can identify belongings that may be mine.
- As a student, I want to submit additional information when claiming an item so that my ownership can be verified.
- As a student, I want to track the status of my reports and claims so that I know whether there has been progress.
### Administrator User Stories

- As a Lost and Found Administrator, I want to view and manage reported items so that all submissions are properly organized.
- As a Lost and Found Administrator, I want to review ownership claims so that items are only released after reasonable verification.
- As a Lost and Found Administrator, I want to update the status of items so that students can see the progress of their reports and claims.
- As a Lost and Found Administrator, I want to record successful recoveries so that completed cases are documented.
FUNCTIONAL REQUIREMENTS

Functional requirements describe the specific actions and operations the system must support.

| ID | FUNCTIONAL REQUIREMENT |
| --- | --- |
| FR-01 | The system shall allow students to register and log in using an approved campus registration method. |
| FR-02 | The system shall allow students to submit reports of lost belongings, including an item description, category, location and approximate date of loss. |
| FR-03 | The system shall allow students to submit reports of found belongings, including relevant item descriptions and information about where and when the item was found. |
| FR-04 | The system shall allow students to browse and search reported items using available details such as item name, category, location and date. |
| FR-05 | The system shall allow students to submit ownership claims and provide additional identifying information about the item. |
| FR-06 | The system shall provide the administrator with access to view and manage lost and found reports. |
| FR-07 | The system shall allow the administrator to review ownership claims and compare submitted information with the original item report. |
| FR-08 | The system shall allow the administrator to update the status of reported items and claims. |
| FR-09 | The system shall allow successful recoveries to be recorded in the system. |
| FR-10 | The system shall display relevant report and claim statuses to students. |

NON – FUNCTIONAL REQUIREMENTS

Non-functional requirements describe how the system should operate and the standards it should meet.

- Security: The system should protect user accounts and restrict administrative functions to authorized administrators.
- Privacy: Personal information and sensitive item-identification details should only be accessible to authorized users who need them.
- Performance: The system should respond to normal user actions, including searching and submitting reports, without unnecessary delays. A target response time should be established before implementation.
- Reliability: The system should maintain accurate and consistent records of reports, claims and recovery statuses.
- Usability: The platform should have a simple and understandable interface that allows students to report and search for items without difficulty.
- Availability: The system should be accessible to the campus community whenever the service is available, with appropriate measures to minimie interruptions.
- Scalability: The system should be capable of accommodating an increasing number of students and item reports as usage grows.
- ACCEPTANCE CRITERIA
Acceptance criteria define the conditions that must be satisfied before a feature can be considered complete.

| FEATURE | ACCEPTANCE CRITERIA |
| --- | --- |
| Student Registration and Login | Students can create accounts using the approved registration method, enter the required information and log in successfully. Invalid login details should produce an appropriate error message. |
| Lost Item Reporting | A student can submit a lost item report with the required information. The system should confirm successful submission and make the report available for management. |
| Found Item Reporting | A student can submit a found item report. Sensitive identifying details should not automatically be exposed in the public listing. |
| Search and Browse | Students can search or browse available reports and view relevant matching results. |
| Ownership Claims | A student can submit a claim and provide additional identifying information. The claim should be available for administrator review. |
| Administrator Management | The administrator can access reports, review claims and update item statuses. Unauthorised users must not have access to administrative functions. |
| Recovery Tracking | Students can view the current status of their reports or claims, and successful recoveries can be recorded by the administrator. |

MVP, SCOPE AND MoSCoW PRIORITIES

### Minimum Viable Product (MVP)

The Minimum Viable Product (MVP) will focus on the essential functions required to make the Campus Lost and Found System useful to students and administrators.

- Student registration and login.
- Lost item reporting.
- Found item reporting.
- Searching and browsing reported items.
- Submission of ownership claims.
- Administrator access to reports and claims.
- Ownership verification and item status updates.
- Recording successful recoveries.
These features form the foundation of the platform and allow the system to address the main problem of fragmented lost and found communication on campus.

### Scope

### In Scope

- Reporting lost and found belongings.
- Searching and browsing item reports.
- Submitting ownership claims.
- Administrator review and verification of claims.
- Updating and tracking item statuses.
- Recording successful recoveries.
### Out of Scope for the First Release

- Automated ownership verification.
- Public access for people outside the campus community.
- Delivery or transportation of recovered belongings.
- Integration with external security or surveillance systems.
- Advanced analytics and reporting features.
### MoSCoW Prioritization

Features are prioritized according to their importance to the first release.

| Priority | Features |
| --- | --- |
| Must Have | Student registration and login, lost and found reporting, search and browsing, ownership claims, administrator review and status updates. |
| Should Have | Recovery records and clear status tracking for students. |
| Could Have | Optional item images and additional search filters. |
| Won't Have in This Release | Automated ownership verification, external security-system integration and delivery services. |

ASSUMPTION AND OPEN QUESTIONS

### Assumptions

The following assumptions guide the initial development of the product:

- The system will primarily serve students within the campus community.
- Students will have access to an internet connection to use the platform.
- The school will provide the necessary approval and support for implementation.
- A designated administrator will be responsible for managing reports and reviewing ownership claims.
- Students will provide accurate information when submitting reports and ownership claims.
- Physical collection and handover arrangements will be handled according to procedures approved by the school.
### Open Questions

The following matters require further clarification before implementation:

- What method will be used to verify that registered users are members of the campus community?
- Which department or individual will be responsible for administering the system?
- Where will found belongings be stored and collected?
- What procedures will the school approve for handing recovered belongings to their owners?
- How long should item reports and user information remain stored in the system?
- What level of access will administrators have, and how will additional administrators be authorized?
- What platform format and technical approach will be selected for implementation?
