# Requirement Analysis in Software Development

---

## What is Requirement Analysis?
Requirement Analysis is a critical phase in the **Software Development Life Cycle (SDLC)** where the needs, expectations, and constraints of stakeholders are gathered, analyzed, and documented.  
It ensures that the software developed aligns with business goals and user needs. During this phase, both functional and non-functional requirements are identified, which helps prevent misunderstandings and reduces the risk of costly errors later in the development process.

---

## Why is Requirement Analysis Important?
Requirement Analysis is vital in SDLC for several reasons:

- **Clarity and Understanding:** Ensures all stakeholders have a shared understanding of what the system should achieve.  
- **Resource Optimization:** Helps plan resources, timelines, and effort effectively, reducing waste and improving efficiency.  
- **Risk Reduction:** Identifies potential issues early, minimizing errors and rework in later stages of development.  

---

## Key Activities in Requirement Analysis
The key activities involved in Requirement Analysis include:

- **Requirement Gathering:** Collecting information from stakeholders using interviews, surveys, and observations.  
- **Requirement Elicitation:** Engaging stakeholders to extract detailed requirements and expectations.  
- **Requirement Documentation:** Recording requirements clearly in a structured format, often in a Software Requirement Specification (SRS) document.  
- **Requirement Analysis and Modeling:** Evaluating feasibility, consistency, and completeness; modeling workflows and system interactions using diagrams.  
- **Requirement Validation:** Confirming that documented requirements accurately reflect stakeholder needs and resolving ambiguities.

---

## Types of Requirements

### Functional Requirements
Functional requirements define **what the system should do**. Examples for the booking management system include:  
- User can search for available properties.  
- Users can book a property and receive confirmation.  
- Admin can manage property listings.  

### Non-functional Requirements
Non-functional requirements define **how the system performs its functions** and other constraints. Examples include:  
- System must respond to search queries within 2 seconds.  
- Application must support at least 500 concurrent users.  
- Data must be encrypted during transmission to ensure security.  

---

## Use Case Diagrams
Use Case Diagrams are visual representations of the interactions between **actors** (users or external systems) and the system. They help clarify requirements, identify actors, and define system functionalities.  

![Booking System Use Case Diagram](alx-booking-uc.png)  
*Figure: Use Case Diagram for Booking Management System*  

**Benefits:**  
- Provides a clear overview of system functionality  
- Helps identify missing requirements early  
- Facilitates communication between stakeholders and developers  

---

## Acceptance Criteria
Acceptance Criteria define the **conditions that a feature must satisfy** to be considered complete and acceptable. They ensure that development aligns with stakeholder expectations and quality standards.

**Importance:**  
- Provides clear, testable conditions for feature completion  
- Helps developers understand what “done” looks like  
- Facilitates validation during manual or automated testing  

**Example – Checkout Feature:**  
- User can review selected booking details before payment.  
- Payment is successfully processed using multiple payment options.  
- Confirmation email is sent immediately after booking.  
- Error messages are displayed for invalid payment or incomplete information.  

---



