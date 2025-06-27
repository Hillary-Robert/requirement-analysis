# requirement-analysis

# Requirement Analysis in Software Development

**Purpose:**  
This repository covers the fundamental activities, techniques, and best practices for performing requirement analysis in software development. You’ll find:

- Definitions and distinctions between functional and non-functional requirements  
- Common elicitation techniques (interviews, surveys, workshops)  
- Documentation standards and templates  
- Examples and exercises to practice requirement gathering and specification  

By following the materials here, you’ll gain a clear understanding of how to gather, document, validate, and manage software requirements effectively.


## What is Requirement Analysis?

Requirement Analysis is the process of identifying, documenting, and validating the needs and constraints of stakeholders for a software system. It serves as the bridge between business needs and the technical solution, ensuring that the final product delivers exactly what users expect.

Key aspects of Requirement Analysis:

- **Elicitation**  
  Gathering information through interviews, workshops, questionnaires, observation, and document studies.  
- **Documentation**  
  Organizing requirements into clear, unambiguous artifacts (user stories, use cases, requirement specifications).  
- **Validation & Verification**  
  Reviewing requirements with stakeholders to confirm accuracy, consistency, feasibility, and completeness before moving on to design and development.  
- **Prioritization**  
  Ranking requirements by business value, risk, and technical dependency to guide iterative planning and resource allocation.

### Why It Matters in the SDLC

1. **Reduces Rework & Cost**  
   Catching misunderstandings early prevents costly changes in later phases (design, coding, testing).  
2. **Aligns Stakeholders**  
   Provides a shared vision of what the software must do, minimizing conflicts and scope creep.  
3. **Improves Quality**  
   Well-defined requirements become the baseline for test cases, ensuring the system meets its intended purpose.  
4. **Supports Project Planning**  
   Clear requirements allow for realistic estimates of time, effort, and budget, leading to smoother project execution.

By investing time in thorough Requirement Analysis, teams can deliver higher-quality software on time and within budget, with greater confidence that it meets user needs.


## Why is Requirement Analysis Important?

1. **Reduces Cost and Rework**  
   Identifying and clarifying requirements early prevents misunderstandings that lead to expensive fixes later in design, development, or testing.

2. **Aligns Stakeholders and Prevents Scope Creep**  
   A well-documented set of requirements creates a shared understanding among users, business sponsors, and developers—minimizing conflicts and uncontrolled changes.

3. **Improves Product Quality**  
   Clear, testable requirements serve as the foundation for writing effective test cases, ensuring the system behaves exactly as intended.

4. **Enables Accurate Project Planning**  
   Detailed requirements allow for realistic estimates of time, effort, resources, and cost, leading to more reliable schedules and budgets.

5. **Facilitates Better Risk Management**  
   By uncovering constraints and assumptions up front, teams can identify potential technical or business risks early and plan appropriate mitigation.  


   ## Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collecting all relevant information about the system’s needs from stakeholders, business documents, existing systems, and market research.

- **Requirement Elicitation**  
  Using techniques like interviews, workshops, surveys, and observation to draw out both explicit and tacit requirements from users and stakeholders.

- **Requirement Documentation**  
  Organizing and recording requirements in clear, standardized formats (user stories, use cases, SRS) so they can be reviewed and agreed upon.

- **Requirement Analysis and Modeling**  
  Examining requirements for completeness, consistency, feasibility, and priority; creating models (data flow diagrams, UML diagrams) to visualize system behavior and relationships.

- **Requirement Validation**  
  Reviewing and verifying requirements with stakeholders through walkthroughs, prototyping, and formal inspections to ensure accuracy and alignment with business goals.  



  ## Types of Requirements

### Functional Requirements  
Functional requirements specify **what** the booking management system must do. Examples for our case study:

- **User Registration & Login**  
  - Allow new users (guests, hosts, admins) to sign up with email and password.  
  - Permit existing users to log in, recover forgotten passwords, and log out.

- **Property Search & Filtering**  
  - Enable users to search available properties by location, date range, number of guests, price range.  
  - Support filters such as “pet-friendly,” “instant booking,” and “amenities” (Wi-Fi, pool, parking).

- **Booking Creation & Management**  
  - Let guests select dates, confirm payment details, and create a reservation.  
  - Allow hosts to view, approve, modify, or cancel bookings.  
  - Generate confirmation emails and notifications for both parties.

- **Payment Processing**  
  - Integrate with a payment gateway to securely process credit-card payments.  
  - Issue refunds or partial refunds according to cancellation policies.

- **Review & Rating**  
  - After checkout, enable guests to submit a review and star rating for the property.  
  - Allow hosts to respond to reviews.

### Non‐functional Requirements  
Non‐functional requirements define **how** the system performs. Examples for our case study:

- **Performance & Scalability**  
  - The system should handle up to 1,000 simultaneous users without response times exceeding 2 seconds.  
  - Support horizontal scaling to accommodate seasonal traffic spikes.

- **Security**  
  - All user data must be encrypted in transit (HTTPS/TLS) and at rest.  
  - Implement role-based access control so only hosts can modify their own listings and only admins can access audit logs.

- **Availability & Reliability**  
  - Maintain 99.9% uptime, with automated failover across data centers.  
  - Ensure booking transactions are atomic—no partial or corrupted reservations.

- **Usability**  
  - Interfaces should load fully within 3 seconds on a standard broadband connection.  
  - Provide clear error messages and inline form validation for all user inputs.

- **Compliance**  
  - Adhere to GDPR for users in the EU, including data-subject rights and consent capture.  
  - Meet PCI DSS requirements for processing payment card information.



