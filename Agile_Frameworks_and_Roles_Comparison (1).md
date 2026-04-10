# Agile Frameworks and Roles: A Comprehensive Comparison

**Document Version:** 1.0  
**Last Updated:** April 2026  
**Framework Versions Referenced:** Scrum Guide 2020+, Kanban Method (Current), SAFe 6.0 (March 2023, Updated 2025)

---

## Table of Contents

1. [Comparative Framework Analysis](#comparative-framework-analysis)
   - [Scrum](#scrum)
   - [Kanban](#kanban)
   - [SAFe (Scaled Agile Framework)](#safe-scaled-agile-framework)
   - [Key Differences Summary](#key-differences-summary)

2. [Agile Roles: General Perspective](#agile-roles-general-perspective)

3. [Framework-Specific Roles](#framework-specific-roles)
   - [Scrum Roles](#scrum-roles)
   - [Kanban Roles](#kanban-roles)
   - [SAFe Roles](#safe-roles)

---

## Comparative Framework Analysis

### Scrum

#### Definition
Scrum is a lightweight, iterative framework for managing product development. It provides a structured approach to planning, executing, and delivering work in fixed time-boxed iterations called sprints.

#### Core Philosophy
- **Empirical Process Control:** Built on transparency, inspection, and adaptation
- **Iterative Development:** Work completed in fixed sprints (typically 1-4 weeks)
- **Push-Based System:** Work is planned and "pushed" into sprints
- **Ceremony-Driven:** Structured meetings define the rhythm of work

#### Key Characteristics

| Aspect | Details |
|--------|---------|
| **Iteration Length** | Fixed sprint duration (1-4 weeks, typically 2 weeks) |
| **Cadence** | Time-boxed ceremonies at defined intervals |
| **Planning** | Sprint planning occurs before each sprint begins |
| **Workflow** | Fixed phases: To Do → In Progress → Done within each sprint |
| **Roles** | Three defined roles: Product Owner, Scrum Master, Development Team |
| **Artifacts** | Product Backlog, Sprint Backlog, Increment |
| **Delivery** | Potentially shippable increment at end of each sprint |
| **Change Management** | Changes accommodated during planning; mid-sprint changes discouraged |
| **Scaling** | Designed for single team; scaling requires frameworks like SAFe or LeSS |

#### When to Use Scrum
- Teams building software products with clear feature requirements
- Organizations needing predictable delivery cycles
- Teams requiring strong structure and defined ceremonies
- Products where regular releases are possible
- Teams new to Agile (framework provides guardrails)

#### Strengths
- Clear structure and well-defined ceremonies
- Predictable sprint cycles facilitate planning
- Emphasis on delivering working increments frequently
- Strong feedback loops through sprint reviews
- Widely adopted and well-understood

#### Limitations
- May feel restrictive for teams requiring flexibility
- Requires commitment to time-boxed sprints
- Not optimized for continuous flow
- Scaling across multiple teams requires additional frameworks
- Can create bottlenecks if workflow doesn't fit sprint boundaries

---

### Kanban

#### Definition
Kanban is a method for visualizing work, managing flow, and continuous delivery. Rather than working in fixed iterations, Kanban uses a pull-based system where work flows continuously through defined stages.

#### Core Philosophy
- **Evolutionary Change:** Continuous incremental improvement without disruption
- **Continuous Flow:** Work moves steadily through the process
- **Pull-Based System:** Work is "pulled" into the workflow when capacity allows
- **Principle-Driven:** Built on flexibility and adaptation to existing processes

#### Key Characteristics

| Aspect | Details |
|--------|---------|
| **Iteration Length** | No fixed iterations; continuous flow |
| **Cadence** | No mandatory ceremonies; flexible meeting cadences |
| **Planning** | Continuous; work pulled as capacity becomes available |
| **Workflow** | Visualized workflow with explicit stages (e.g., To Do → In Progress → Done) |
| **Roles** | No prescribed roles; works within existing team structure |
| **Artifacts** | Kanban Board, Work Items, Metrics (cycle time, throughput) |
| **Delivery** | Continuous delivery of individual items as completed |
| **Change Management** | Minimal disruption; evolutionary approach respects existing processes |
| **Scaling** | Scales naturally; can manage multiple teams and boards |

#### Four Core Principles
1. **Start with What You Do Now:** Apply Kanban to current processes without major restructuring
2. **Agree to Pursue Incremental, Evolutionary Change:** Avoid big-bang transformations
3. **Respect Current Process, Roles, and Responsibilities:** Preserve valuable existing elements
4. **Encourage Leadership at All Levels:** Empower all team members to suggest and implement improvements

#### Six Core Practices
1. **Visualize the Work:** Display all work items on a Kanban board showing workflow stages
2. **Limit Work-In-Progress (WIP):** Cap the number of items in each workflow stage to maintain focus
3. **Manage Flow:** Monitor and optimize the movement of work through stages
4. **Make Policies Explicit:** Document rules, standards, and decision criteria
5. **Implement Feedback Loops:** Hold regular meetings (standups, reviews, operations reviews) to assess outcomes
6. **Improve Collaboratively, Evolve Experimentally:** Use data and scientific method to guide process improvements

#### When to Use Kanban
- Teams handling continuous work streams (support, operations, maintenance)
- Organizations resistant to major process changes
- Projects with unpredictable work arrival rates
- Teams needing flexibility in workflow design
- Multi-product or multi-team environments
- Integration with existing non-Agile processes

#### Strengths
- Minimal disruption to existing workflows
- Extreme flexibility in process design
- Natural fit for continuous delivery environments
- Reduces work-in-progress bottlenecks
- Scales easily across multiple teams
- Lower training overhead

#### Limitations
- Lacks structure of defined sprints (some teams find this challenging)
- No built-in role definitions (requires clarity from team)
- Less suitable for teams needing hard deadlines
- Requires discipline in WIP limit enforcement
- Metrics-driven; requires good measurement practices

---

### SAFe (Scaled Agile Framework)

#### Definition
SAFe is a knowledge base of proven, integrated principles, practices, and competencies for applying Agile at enterprise scale. It provides structured guidance for aligning and coordinating multiple Agile teams across portfolios and large solutions.

#### Current Version
SAFe 6.0 is the current version, last updated in September 2025. Recent 2025 updates focused on a new approach to solving business problems with competencies, and continued simplification of guidance.

#### Core Philosophy
- **Business Agility:** Align the entire organization around delivering value
- **Scaled Coordination:** Synchronize work across tens to hundreds of teams
- **Lean-Agile Values:** Rooted in Agile, Lean, and systems thinking
- **Disciplined Execution:** Maintains governance while enabling team autonomy

#### Four SAFe Configurations

SAFe provides four scalable configurations to meet organizations of different sizes:

##### Essential SAFe
- Most basic configuration
- Covers team and program (Agile Release Train) level
- Suitable for organizations with 50-125 people
- Provides majority of SAFe benefits

##### Large Solution SAFe
- Adds coordination across multiple programs
- Handles value stream level concerns
- For organizations with 125-500 people
- Manages dependencies between ARTs

##### Portfolio SAFe
- Includes strategic direction and investment funding
- Adds portfolio governance and Lean Portfolio Management
- For large enterprises with portfolio-level decisions
- Suitable for 500+ people

##### Full SAFe
- Combines all three levels
- Most comprehensive configuration
- For complex enterprises with multiple value streams
- Provides complete alignment from portfolio to team

#### Key Characteristics

| Aspect | Details |
|--------|---------|
| **Iteration Length** | 2-week sprints (team level); grouped into Program Increments (PI, typically 10 weeks) |
| **Cadence** | Synchronized across all levels; PI Planning every 10 weeks |
| **Planning** | Multi-level planning: Portfolio → Value Stream → Program (ART) → Team → Iteration |
| **Workflow** | Standardized across teams with defined stages and dependencies |
| **Roles** | Multiple defined roles at team, program, solution, and portfolio levels |
| **Artifacts** | Epic, Feature, Story, Team Backlog, PI Objectives, Roadmaps |
| **Delivery** | Integrated releases at end of Program Increments (typically every 10 weeks) |
| **Change Management** | Planning-heavy; changes accommodated at PI planning boundaries |
| **Governance** | Built-in governance through defined roles and ceremonies |
| **Scaling** | Designed explicitly for enterprise-scale (100+ teams) |

#### SAFe Core Values

SAFe emphasizes alignment, collaboration, and delivery with values including built-in quality, transparency, and program execution, with principles rooted in lean and systems thinking.

#### When to Use SAFe
- Large enterprises with multiple product lines or value streams
- Organizations with 100+ development teams
- Industries requiring synchronized, coordinated releases
- Environments requiring portfolio-level governance
- Organizations with complex dependencies between teams
- Regulated industries needing structured governance

#### Strengths
- Designed specifically for enterprise scale
- Provides complete governance and alignment framework
- Synchronizes work across large numbers of teams
- Clear role definitions and accountability
- Extensive training and certification ecosystem
- Proven with Fortune 100 companies (70% adoption in 2025)
- Comprehensive guidance on scaling Agile practices

#### Limitations
- Significant complexity; steep learning curve
- Overhead of multiple synchronization ceremonies
- May be over-engineered for small organizations
- Perceived as hierarchical by some critics
- Requires substantial commitment to implementation
- Can create process overhead if not tailored appropriately

---

### Key Differences Summary

#### Planning Approach

| Framework | Planning Style | Planning Frequency | Planning Scope |
|-----------|---|---|---|
| **Scrum** | Sprint-based planning | Every sprint (1-4 weeks) | One sprint at a time |
| **Kanban** | Continuous planning | On-demand, as capacity allows | Individual work items |
| **SAFe** | Multi-level synchronized planning | PI Planning every 10 weeks + iteration planning | Portfolio → Team |

#### Work Flow Model

| Framework | Flow Type | Work Cadence | Batch Size |
|-----------|---|---|---|
| **Scrum** | Push-based; planned into sprints | Fixed sprint iterations | Sprint's worth of work |
| **Kanban** | Pull-based; work pulled as needed | Continuous flow | Individual items |
| **SAFe** | Push-based; synchronized across programs | Fixed PI cycles + iterations | PI's worth of coordinated work |

#### Change Management

| Framework | Approach | Timing |
|-----------|---|---|
| **Scrum** | Changes accepted during planning; mid-sprint discourages changes | At sprint boundaries |
| **Kanban** | Continuous, evolutionary; minimal disruption | On-going, any time |
| **SAFe** | Changes planned at PI boundaries; accommodated within PI as needed | Every 10 weeks at PI Planning |

#### Structure and Roles

| Framework | Role Definition | Team Structure | Ceremony Count |
|-----------|---|---|---|
| **Scrum** | Three defined roles (PO, SM, Team) | Single team focus (9 people recommended) | 5 ceremonies minimum |
| **Kanban** | No prescribed roles; flexible | Works with existing structure | 4-7 cadence meetings recommended |
| **SAFe** | Multiple defined roles at 4 levels | Multiple teams organized in ARTs | 10+ ceremonies across levels |

#### Scale and Complexity

| Framework | Ideal Team Size | Suitable Scale | Complexity Level |
|-----------|---|---|---|
| **Scrum** | 1 team (up to 9 people) | Small to medium teams | Low-to-Moderate |
| **Kanban** | 1-many teams | Can scale naturally across teams | Low-to-Moderate |
| **SAFe** | 100-1000+ people across multiple teams | Enterprise-wide | High |

---

## Agile Roles: General Perspective

Before examining framework-specific roles, it's important to understand the broader ecosystem of roles that exist across Agile organizations. These general roles represent functional responsibilities that may be distributed differently depending on the framework chosen.

### General Agile Roles and Responsibilities

#### 1. **Product Owner / Product Manager**
- **Primary Responsibility:** Defines what gets built and prioritizes work
- **Focus:** Customer value, business outcomes, market fit
- **Key Activities:** Backlog creation, prioritization, stakeholder management, vision articulation
- **Characteristics:** Business-focused, customer-centric, visionary
- **Reports To:** Typically product leadership or executive stakeholder

#### 2. **Scrum Master / Agile Coach**
- **Primary Responsibility:** Facilitates Agile adoption and removes obstacles to delivery
- **Focus:** Process health, team effectiveness, organizational change
- **Key Activities:** Coaching, facilitation, removing impediments, protecting team focus
- **Characteristics:** Servant-leader, facilitator, change agent
- **Reports To:** Typically operations or quality leadership

#### 3. **Development Team / Technical Team**
- **Primary Responsibility:** Designs, builds, tests, and delivers working product
- **Focus:** Technical excellence, continuous improvement, delivering value
- **Key Activities:** Development, testing, code review, technical problem-solving
- **Characteristics:** Cross-functional, self-organizing, collaborative
- **Reports To:** Team lead or technical leadership

#### 4. **Release Manager / Release Train Engineer**
- **Primary Responsibility:** Manages the release and deployment process
- **Focus:** Coordinating releases, managing dependencies, ensuring quality gates
- **Key Activities:** Release planning, deployment coordination, dependency management
- **Characteristics:** Detail-oriented, risk-aware, process-focused
- **Reports To:** Operations or product leadership
- **Note:** More prominent in SAFe; less defined in pure Scrum/Kanban

#### 5. **Agile Coach / Agile Transformation Lead**
- **Primary Responsibility:** Guides organizational Agile adoption and continuous improvement
- **Focus:** Organization-wide transformation, culture change, capability building
- **Key Activities:** Training, change management, process design, mentoring
- **Characteristics:** Strategic thinker, change leader, organizational awareness
- **Reports To:** Executive leadership or Chief Transformation Officer
- **Note:** Organizational role; may not exist on individual teams

#### 6. **Stakeholder / Product Sponsor**
- **Primary Responsibility:** Provides business context, funding, and strategic direction
- **Focus:** Business outcomes, ROI, strategic alignment
- **Key Activities:** Prioritization input, requirement clarification, funding decisions
- **Characteristics:** Strategic, business-minded, decision-making authority
- **Reports To:** Executive leadership
- **Note:** External to team; consulted regularly but not a team member

#### 7. **Business Analyst / Requirements Specialist**
- **Primary Responsibility:** Bridges customer needs and team delivery
- **Focus:** Requirements clarity, acceptance criteria, customer understanding
- **Key Activities:** Requirements elicitation, user story creation, acceptance testing
- **Characteristics:** Detail-oriented, customer-focused, analytical
- **Reports To:** Product Owner or team lead
- **Note:** May be part of team or work across multiple teams

---

## Framework-Specific Roles

### Scrum Roles

Scrum defines **three core roles** that form the Scrum Team. These are the only roles in pure Scrum.

#### 1. Product Owner (PO)

**Definition:**  
The Product Owner is accountable for maximizing the value of the product resulting from the work of the Development Team.

**Responsibilities:**
- Developing and explicitly communicating product vision and strategy
- Creating and maintaining the Product Backlog
- Ordering Product Backlog items to best achieve goals and missions
- Ensuring Product Backlog items are understood by the Development Team
- Deciding when to release the product
- Engaging with stakeholders to gather requirements and feedback
- Making final accept/reject decisions on completed work

**Key Accountabilities:**
- Product value maximization
- Stakeholder satisfaction
- Backlog clarity and grooming
- Release decisions

**Time Commitment:** Full-time for team (typically dedicated to one team)

**Note:** The Product Owner is ONE person; decisions are not made by committee.

#### 2. Scrum Master (SM)

**Definition:**  
The Scrum Master is a servant-leader for the Scrum Team, accountable for the Scrum Team's effectiveness.

**Responsibilities:**
- Coaching the team in self-management and cross-functionality
- Removing impediments to the Development Team's progress
- Ensuring that all Scrum events take place and are positive, productive, and kept within time-boxes
- Coaching the organization on Scrum adoption and practices
- Working with Product Owner on effective Product Backlog management
- Facilitating collaboration among stakeholders

**Key Accountabilities:**
- Team effectiveness
- Process health
- Impediment removal
- Organizational transformation

**Time Commitment:** Full-time for team (typically dedicated to one team)

**Leadership Style:** Servant-leader (facilitator, not director)

**Note:** Not a project manager or team supervisor; focuses on process and team dynamics.

#### 3. Development Team

**Definition:**  
The Development Team consists of professionals who do the work of delivering a potentially releasable Increment of product at the end of each Sprint.

**Characteristics:**
- Cross-functional: Includes all skills needed to create product increment
- Self-organizing: Decides how to accomplish sprint work
- Small: 3-9 people recommended (sometimes stated as 5±3)
- Empowered: Decides on technical approach and process details
- Accountable: Collectively responsible for sprint success

**Responsibilities:**
- Creating the Definition of Done
- Estimating Product Backlog items
- Committing to achievable Sprint Goals
- Delivering increments of working product
- Collaborating with Product Owner on acceptance criteria
- Continuously improving processes and practices

**Key Accountabilities:**
- Technical delivery
- Quality assurance
- Continuous improvement
- Sprint commitment

**Time Commitment:** Full-time team members

**Note:** No sub-roles (no separate QA, architects, specialists reporting outside team).

---

### Kanban Roles

Kanban is deliberately **role-agnostic**. Unlike other lean methodologies, Kanban doesn't have any built-in team roles, so it works within your current team structure and process.

#### Kanban's Approach to Roles

Instead of prescribing roles, Kanban operates on the principle that work is performed by people in existing organizational structures, and those structures are respected and preserved.

#### Typical Roles (Not Prescribed, But Common)

While Kanban doesn't define roles, organizations typically maintain:

##### 1. **Service Owner / Process Owner**
- **Role:** Oversees the Kanban system for a service or workflow
- **Responsibilities:** Policy setting, WIP limit decisions, bottleneck resolution
- **Note:** Could be a team lead, manager, or Product Owner (role varies by organization)

##### 2. **Kanban Team Members**
- **Role:** Perform the work visible on the Kanban board
- **Responsibilities:** Pull work, complete work according to policies, participate in improvement
- **Note:** May have specialized roles (developer, tester, designer) but work within Kanban flow

##### 3. **Stakeholders**
- **Role:** Request work, provide feedback, prioritize
- **Responsibilities:** Entering work items, reviewing completions, participating in cadences
- **Note:** More integrated into the process than in Scrum

##### 4. **Kanban Coach / Improvement Facilitator** (Optional)
- **Role:** Guides Kanban adoption and continuous improvement
- **Responsibilities:** Facilitating feedback loops, teaching metrics, coaching teams
- **Note:** Not a required role; emerges as organization matures

#### Kanban Cadence Roles (Meeting-Specific)

Kanban recommends specific meetings (cadences) where roles emerge:

| Cadence | Purpose | Participants |
|---------|---------|---|
| **Daily Standup** | Coordinate daily work | All team members |
| **Service Delivery Review** | Review against service level targets | Team + stakeholders |
| **Operations Review** | Discuss metrics and system performance | Team + management |
| **Risk Review** | Identify and mitigate risks | Team + stakeholders |

---

### SAFe Roles

SAFe defines roles across **four organizational levels**, creating a comprehensive role structure for scaled organizations.

#### Team Level Roles

##### 1. Product Owner (Same as Scrum)
- **Scope:** Single team or small set of teams
- **Responsibilities:** Backlog prioritization, story acceptance, team-level value delivery
- **Reports To:** Product Manager or Product Management

##### 2. Scrum Master (SAFe Variant)
- **Scope:** Single team
- **Responsibilities:** Team coaching, ceremony facilitation, team-level impediment removal
- **Distinct SAFe Focus:** Collaboration with Release Train Engineer (RTE) on program-level concerns
- **Reports To:** Team lead or program management

##### 3. Team Members
- **Scope:** Individual team
- **Responsibilities:** Executing story work, estimation, quality assurance
- **SAFe Distinction:** Organized into Agile Release Train (ART)

---

#### Program Level Roles

##### 4. Product Manager (Program Level)
- **Scope:** One Agile Release Train (ART); typically 5-12 teams
- **Responsibilities:** 
  - Defining features and epics for the ART
  - Maintaining program backlog
  - Communicating business objectives
  - Facilitating cross-team prioritization
- **Reports To:** Director of Product Management or Chief Product Officer
- **Interaction:** Works with Product Owners to ensure team-level alignment with program vision

##### 5. Release Train Engineer (RTE)
- **Scope:** Single Agile Release Train
- **Responsibilities:**
  - Organizing and facilitating PI Planning
  - Managing ART-level dependencies
  - Removing program-level impediments
  - Coordinating across Scrum Masters
  - Tracking ART metrics and health
  - Escalating risks and issues
- **Reports To:** Program Director or VP of Engineering
- **Key Accountability:** ART synchronization and delivery
- **Note:** One of the most advanced and critical SAFe roles

##### 6. Business Analyst (Program Level)
- **Scope:** One or more ARTs
- **Responsibilities:**
  - Clarifying feature requirements
  - Defining acceptance criteria
  - Eliciting business needs
  - Supporting Product Manager

##### 7. System Architect / Engineering Lead (Program Level)
- **Scope:** One ART
- **Responsibilities:**
  - Defining technical direction for ART
  - Managing architectural decisions
  - Ensuring built-in quality
  - Mentoring technical teams

---

#### Solution Level Roles

##### 8. Product Manager (Solution Level)
- **Scope:** Large solution spanning multiple ARTs and value streams
- **Responsibilities:**
  - Vision and roadmap for large solution
  - Cross-ART prioritization
  - Customer engagement at solution level
  - Feature prioritization across value streams

##### 9. Solution Architect
- **Scope:** Large solution across multiple ARTs
- **Responsibilities:**
  - Overall solution architecture
  - Technical strategy for solution
  - Cross-ART technical integration
  - Non-functional requirements

##### 10. System Team (Optional)
- **Scope:** Solution level
- **Responsibilities:**
  - Supporting infrastructure and integration
  - Building shared capabilities
  - Cross-ART concerns
  - DevOps support

---

#### Portfolio Level Roles

##### 11. Epic Owner
- **Scope:** Portfolio level
- **Responsibilities:**
  - Defining and sponsoring strategic epics
  - Business case development
  - Cross-solution prioritization
  - Strategic alignment
- **Reports To:** Chief Product Officer or VP of Product Strategy

##### 12. Portfolio Manager
- **Scope:** Entire portfolio
- **Responsibilities:**
  - Strategic roadmap
  - Resource allocation
  - Investment decisions
  - Portfolio-level metrics
- **Reports To:** Chief Financial Officer or Chief Executive Officer

##### 13. Chief Product Officer / VP Product
- **Scope:** All products and solutions
- **Responsibilities:**
  - Product strategy and vision
  - Market positioning
  - Investment decisions
  - Organizational direction
- **Reports To:** Executive leadership (CEO)

---

#### Cross-Functional SAFe Roles

##### 14. Agile Coach
- **Scope:** Can span team, program, or enterprise level
- **Responsibilities:**
  - Coaching teams on Agile practices
  - Removing organizational impediments
  - Training and enablement
  - Facilitating transformation
- **Types:**
  - **Team Coach:** Focuses on single team or small group of teams
  - **Program Consultant:** Works at ART level
  - **Enterprise Architect:** Guides large-scale technical transformation

##### 15. Scrum of Scrums Master
- **Scope:** Multiple ARTs (typically 5-20 teams)
- **Responsibilities:**
  - Facilitating cross-team coordination
  - Escalating impediments
  - Managing inter-ART dependencies
  - Note: Emerges in larger Scale Agile implementations

##### 16. Lean Portfolio Management (LPM) Team
- **Scope:** Portfolio level
- **Responsibilities:**
  - Strategic planning
  - Investment funding
  - Portfolio prioritization
  - Portfolio governance
- **Members:** CFO, Chief Architect, Chief Product Officer, Portfolio Managers

---

## Comparison of Roles Across Frameworks

### Team-Level Role Mapping

| Responsibility | Scrum | Kanban | SAFe (Team Level) |
|---|---|---|---|
| **Value Definition** | Product Owner | Service Owner (optional) | Product Owner |
| **Delivery** | Development Team | Team Members | Team Members |
| **Facilitation** | Scrum Master | Process Facilitator (optional) | Scrum Master |
| **Quality Assurance** | Dev Team responsibility | Dev Team responsibility | Dev Team responsibility |

### Scaling and Coordination Roles

| Function | Scrum | Kanban | SAFe |
|---|---|---|---|
| **Cross-Team Coordination** | Not defined | Not defined | Release Train Engineer |
| **Program Prioritization** | Not defined | Not defined | Product Manager (Program) |
| **Architecture** | Not defined | Not defined | Solution Architect |
| **Portfolio Governance** | Not defined | Not defined | Epic Owner, Portfolio Manager |

### Role Flexibility

| Framework | Role Flexibility | Role Definition | Organizational Adaptation |
|---|---|---|---|
| **Scrum** | Low - Three roles strictly defined | Explicit and required | Must adapt org to Scrum roles |
| **Kanban** | High - No prescribed roles | Implicit; emerges from context | Fits existing org structure |
| **SAFe** | Medium - Defined at each level | Explicit by level | Org adapts with SAFe structure |

---

## Recommendations for Framework Selection Based on Organizational Context

### Choose Scrum When:
- Building product features with clear, definable requirements
- Team is new to Agile and needs structure
- Organization can commit to dedicated Product Owner and Scrum Master
- Predictable sprint cycles are important for planning
- Team size is small (under 10 people)
- Organization embraces change management toward Agile practices

### Choose Kanban When:
- Work arrives unpredictably or continuously
- Organization is resistant to major structural changes
- Need to integrate with existing (non-Agile) processes
- Teams handle support, operations, or maintenance work
- Organization values evolutionary over revolutionary change
- Multiple teams need to coordinate without heavy overhead

### Choose SAFe When:
- Organization has 100+ development people
- Multiple product lines or value streams require coordination
- Portfolio-level governance is required
- Regulatory requirements demand clear structure
- Organization needs to scale Agile across divisions
- Enterprise synchronization at regular intervals is necessary

### Hybrid Approaches:
Many organizations successfully combine frameworks:
- **Scrum + Kanban:** Teams use Scrum sprints with Kanban boards for daily management
- **Scrum + SAFe:** Scrum teams operate within SAFe's program and portfolio structure
- **Kanban + SAFe:** Continuous flow at team level with synchronized PI Planning at program level

---

## Conclusion

The choice between Scrum, Kanban, and SAFe is not binary; rather, it depends on organizational context, scale, and constraints:

- **Scrum** provides structure and ceremony for teams building discrete products
- **Kanban** provides flexibility and flow for continuous delivery environments
- **SAFe** provides coordination and governance for large-scale enterprises

Similarly, roles vary dramatically by framework. Scrum mandates three specific roles, Kanban respects existing roles, and SAFe defines comprehensive roles across organizational levels.

The most successful Agile transformations are those where the framework and roles are deliberately chosen to align with organizational strategy, team composition, and business objectives—not adopted wholesale without adaptation.

---

## Appendices

### A. Glossary of Terms

**Agile Release Train (ART):** In SAFe, a group of 5-12 teams (100-130 people) that works together to deliver value in synchronized iterations.

**Definition of Done:** Explicit criteria for when work is considered complete and acceptable.

**Increment:** In Scrum, the working product produced at the end of a sprint.

**Program Increment (PI):** In SAFe, a 10-week fixed time-box during which multiple ARTs coordinate and deliver value.

**Product Backlog:** Ordered list of features, enhancements, and fixes that comprises the work to be done.

**Sprint:** In Scrum, a fixed time-box (typically 1-4 weeks) in which a team completes a defined amount of work.

**Work-In-Progress (WIP):** In Kanban, the number of items actively being worked on at any time; limited to optimize flow.

### B. Reference Materials

- Scrum Guide (2020+) - Official guide at scrum.org
- Kanban Method - Kanban University and David J. Anderson's published works
- SAFe 6.0 Framework - Scaled Agile, Inc. (scaledagile.com)
- The Agile Manifesto and Principles (agilemanifesto.org)

---

**Document Prepared For:** Committee Review and Organizational Reference  
**Confidence Level:** High (all frameworks current as of April 2026)  
**Recommendations:** Customize framework selection and role definitions to organizational context with support of experienced Agile practitioners.
