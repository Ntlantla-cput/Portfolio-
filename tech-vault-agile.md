## Tech Vault — Agile Portfolio of Evidence

### 1. Agile Team Charter

#### Evidence: Tech Vault Agile Team Charter
* **Shared Purpose:** Deliver a reliable, well-structured Tech Vault application with clean architecture, clear requirements traceability, and demonstrable end-to-end functionality within sprint timelines.
* **Team & Roles:** Collaborative delivery across development, backend/database/API implementation, quality assurance/testing, and documentation/pitch alignment (including collaboration with Abongile Zinja and team contributors).
* **Core Values:** Transparency, accountability, iterative improvement, respect for deadlines, and clear technical communication.
* **Working Agreements & SMART Goals:**
  * Use Git/GitHub with clear branches/commits and keep task tracking updated in the project board/logbook.
  * Align tasks to **SMART** sprint targets so deliverables remain scoped, measurable, and achievable within each iteration.
  * Escalate blockers early during check-ins rather than waiting until sprint review.
* **Operational Boundaries:** Individual portfolio reflections and final submission artifacts are authored independently; external/reference frameworks or code patterns follow proper attribution/Harvard referencing where applicable.

#### Reflection: Agile Team Charter
Establishing a clear team charter early helped reduce ambiguity around ownership, communication expectations, and sprint deliverables before heavy implementation began. Defining roles alongside SMART goals and working agreements gave the team a shared baseline for daily execution and kept handoffs smoother across features and testing. Looking back, a charter is most effective when treated as a living agreement revisiting boundaries and check-in habits when workload pressure increases keeps friction low and accountability consistent.

---

### 2. User Stories and Tasks

#### Evidence: Tech Vault User Stories & Task Breakdown

| ID | User Story | Acceptance Criteria | Broken-Down Tasks |
| :--- | :--- | :--- | :--- |
| **US-01** | **As a** user, **I want to** browse and view tech items/records in the vault **so that** I can quickly find relevant product/item details. | Items load cleanly with key attributes and handle empty/error states gracefully. | - Design data model & schema/entities<br>- Implement read endpoints / UI list & detail view<br>- Verify API responses & edge cases |
| **US-02** | **As a** user, **I want to** create and update entries in Tech Vault **so that** stored information stays accurate and current. | Valid inputs persist reliably; invalid inputs return clear validation feedback. | - Build create/update service & controller logic<br>- Add form/request validation rules<br>- Test CRUD flows & error handling |
| **US-03** | **As a** user, **I want to** search, filter, or organize vault items **so that** I can locate specific entries efficiently. | Filtered results match criteria accurately without breaking pagination/state. | - Implement query/filter logic<br>- Connect filter controls to state/backend<br>- Test filter combinations & empty results |
| **US-04** | **As a** team member/stakeholder, **I want to** verify core workflows and present a concise Tech Vault walkthrough **so that** quality and value are clearly demonstrated. | Core user journeys pass verification and key value propositions are communicated clearly. | - Run end-to-end smoke & regression checks<br>- Fix defects found during walkthrough/QA<br>- Prepare concise demo/pitch talking points |

#### Reflection: User Stories and Tasks
Writing user stories from the end-user's perspective forced us to anchor technical features in real user outcomes rather than jumping straight into implementation details. Breaking each story into concrete tasks made effort easier to estimate and exposed hidden dependencies such as data validation, state handling, and edge-case testing early in the workflow. This improved how we sequenced work so smaller, testable increments could be completed reliably.

---

### 3. Product Backlog

#### Evidence: Tech Vault Prioritized Product Backlog

| Priority | Item | Type | Rationale | Status |
| :--- | :--- | :--- | :--- | :--- |
| **P1 (High)** | Core domain entities, database persistence, and baseline CRUD endpoints/views | Feature | Foundational capability required for all downstream workflows | Done |
| **P1 (High)** | Input validation and consistent error handling across core flows | Improvement / Quality | Prevents bad data and improves user feedback | Done |
| **P2 (Medium)** | Search / filtering and item organization capabilities | Feature | High usability value once core data exists | In Progress / Done |
| **P2 (Medium)** | Defect fixes from walkthrough & QA verification pass | Bug Fix | Stabilizes end-to-end reliability prior to sign-off | Ongoing |
| **P3 (Low)** | Enhanced UI polish, extra filters, or secondary reporting enhancements | Enhancement | Valuable after core MVP/sprint goals are secured | Backlog |

#### Reflection: Product Backlog
Maintaining a prioritized product backlog helped keep Tech Vault focused on high value core functionality first rather than getting pulled into low-priority extras too early. As we completed core features, ran walkthroughs, and identified bugs or usability gaps, backlog priorities shifted dynamically to address real blockers and user needs. Prioritization taught me to weigh immediate functional impact and risk reduction against effort when deciding what moves up next.

---

### 4. Sprint Backlog 

#### Evidence: Tech Vault Sprint Backlog
* **Sprint Goal:** Deliver and verify core Tech Vault functionality (data persistence, core CRUD/item workflows, and baseline quality/walkthrough readiness) with clear task ownership.

| Task ID | Linked Story | Sprint Task | Owner / Focus | Status |
| :--- | :--- | :--- | :--- | :--- |
| **SB-01** | US-01 | Finalize core model/schema & seed/test sample data | Backend / Data | Completed |
| **SB-02** | US-01, US-02 | Implement & connect core CRUD service/API/UI flows | Full-Stack / Backend | Completed |
| **SB-03** | US-02 | Add validation checks and handle invalid/missing inputs | Backend / QA | Completed |
| **SB-04** | US-03 | Implement filtering/lookup behavior and test edge cases | Feature / QA | In Progress |
| **SB-05** | US-04 | Execute walkthrough checks, log bugs, and apply fixes | QA / Team | Completed |

#### Reflection: Sprint Backlog
Translating broader product goals into a focused sprint backlog made daily execution much clearer because every item tied directly to a specific sprint objective. Comparing planned sprint tasks against actual execution highlighted the importance of realistic capacity estimation accounting for debugging, integration, and testing time rather than assuming only "happy-path" coding. Whenever scope or blockers shifted mid-sprint, keeping the sprint backlog visible helped us re-focus on finishing high-impact tasks cleanly.

---

### 5. Agile Logbook 

#### Evidence: Tech Vault Agile Logbook (Stand-Ups, Sprint Plans & Retrospectives)
* **Sprint Planning Note:** Scoped core vault features and verification tasks aligned to the sprint goal; assigned clear responsibilities and identified key technical dependencies upfront.
* **Daily Stand-Up Entries:**
  * *Yesterday:* Built/updated core entities, endpoints/components, and initial test cases for Tech Vault features.
  * *Today:* Refine validation/filtering logic, integrate components, and verify behavior against acceptance criteria.
  * *Blockers:* Checked environment/configuration alignment, DTO/schema mapping mismatches, and edge-case test data.
* **Sprint Retrospective Notes:**
  * *What Went Well:* Collaborative problem-solving, steady progress on core functionality, and clearer alignment after walkthrough reviews.
  * *What Could Improve:* Earlier edge-case/QA testing alongside feature work and tighter task sizing so fewer items carry over.
  * *Action Items:* Run walkthrough/verification checks earlier in the cycle and keep task statuses updated daily.

#### Reflection: Agile Logbook
Keeping an Agile logbook of stand-ups, sprint plans, and retrospectives turned day-to-day work into a clear record of how Tech Vault progressed. Reviewing past stand-up blockers and retrospective notes made recurring patterns like testing late or underestimating integration details easy to spot and correct. Across the portfolio as a whole, the logbook connects our **Team Charter** and **Backlogs** to actual delivery habits, showing how structured reflection drives better engineering discipline over time.



