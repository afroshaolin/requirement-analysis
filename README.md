# requirement-analysis-
School project 
Booking Management System: Requirement Analysis Document

# Introduction

This repository contains document outlining a detailed requirement analysis for a Booking Management System (BMS). It aims to provide developers, stakeholders, and product owners with a structured understanding of the system's functionality, constraints, and design expectations. And guide the Software Development Lifecycle in further details so that Roleplayers understand thier task, what is expected of them and by engaging with the end-user to gather more insight on how the design UI/UX should be like in order to meet user needs.

### What is Requirement Analysis?

Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) that involves systematically identifying, gathering, documenting, and analyzing the needs and expectations of stakeholders for a proposed software system. It serves as the foundation for all future stages of development by translating abstract business goals into concrete, actionable requirements. During this process, both functional (what the system should do) and non-functional (how the system should perform) requirements are captured through techniques like stakeholder interviews, use case modeling, and workflow analysis. The primary goal of requirement analysis is to ensure a shared understanding between developers, clients, and end users, thereby minimizing risks of miscommunication, scope creep, and project failure. It culminates in the creation of well-structured documentation—such as requirement specifications and visual diagrams—that guides design, development, testing, and deployment.


### Why is Requirement Analysis Important?

Requirement analysis importance lies in the ability to clearly define, document, and align business goals with technical solutions before development begins. By thoroughly understanding stakeholder needs, identifying functional and non-functional requirements, and uncovering potential risks or constraints early on, requirement analysis ensures that the final product delivers real value, avoids costly rework, and minimizes scope creep. 
*It bridges the communication gap between stakeholders and developers.
*Sets clear expectations, and provides a roadmap for design, development, testing, and deployment.
*Ultimately improving efficiency, quality, and user satisfaction.


###📘 Key Activities in Requirement Analysis 

This document outlines the five essential activities in the Requirement Analysis phase of the Software Development Life Cycle (SDLC). Each activity plays a crucial role in ensuring that the final software product aligns with user needs and business goals.

---

## 📥 1. Requirement Gathering

- Focuses on collecting high-level information about the system from stakeholders.
- Aims to understand the **business context**, objectives, and expected outcomes.
- Involves identifying all relevant stakeholders (clients, users, business analysts, developers).
- Helps define the **scope** and **boundaries** of the project.
- Sets the foundation for deeper elicitation by understanding stakeholder goals and priorities.

---

## 🧠 2. Requirement Elicitation

- A deeper, interactive process to uncover **detailed user needs**.
- Techniques used include:
  - Interviews and focus groups
  - Surveys and questionnaires
  - Workshops and brainstorming sessions
  - Job shadowing and direct observations
  - Document analysis and reverse engineering
- Uncovers both **explicit** and **implicit** requirements.
- Addresses both **functional** and **non-functional** aspects of the system.

---

## 📝 3. Requirement Documentation

- Converts gathered and elicited requirements into structured, readable formats.
- Ensures clarity and alignment across stakeholders and development teams.
- Common documentation types:
  - Software Requirements Specification (SRS)
  - User Stories and Use Cases
  - Functional Requirement Documents (FRD)
- Acts as a **single source of truth** for the project.
- Supports **traceability** throughout the SDLC.

---

## 🔍 4. Requirement Analysis and Modeling

- Involves analyzing requirements for **completeness, consistency, feasibility**, and relevance.
- Identifies **gaps, conflicts**, or **ambiguities** in the requirement set.
- Uses models and visual aids for clarity, such as:
  - Use case diagrams
  - Entity-Relationship diagrams (ERDs)
  - Flowcharts and process
    
---
    
## ✅ 5. Requirement Validation

- Ensures that documented requirements **reflect stakeholder needs** and expectations.
- Confirms that requirements are:
  - ✅ Correct
  - ✅ Complete
  - ✅ Feasible
  - ✅ Testable
- Involves reviews, walkthroughs, and stakeholder feedback sessions.
- Prevents costly changes later in the development cycle.
- Ends with **formal approval (sign-off)** before proceeding to design and development.

---

## Types of Requirements

### Functional Requirements

**Definition**: Functional requirements specify what the system should do — the specific behaviors, tasks, or functions the system must perform.

**Examples for the Booking Management System**:
- Users must be able to create, edit, or cancel a booking.
- The system must prevent double bookings for the same time slot and resource.
- Admins can add or remove users and assign roles.
- Notifications must be sent upon successful booking.
- The calendar should reflect real-time availability updates.

### Non-functional Requirements

**Definition**: Non-functional requirements define how the system should perform. They describe system attributes such as reliability, usability, performance, and security.

**Examples for the Booking Management System**:
- The system must load booking data within 2 seconds under normal load.
- Passwords must be stored using industry-standard encryption methods.
- The platform must be accessible via mobile and desktop.
- System uptime must be at least 99.9% per month.
- All communications must occur over HTTPS.

### Use Case Diagram

Use Case Diagrams are visual representations used in software and systems engineering to illustrate the interactions between users (called *actors*) and the system itself. They show the system’s functional requirements by capturing the various ways users engage with different features or services of the system.

### What Use Case Diagrams Do:
- Depict actors (users or external systems) that interact with the system.
- Represent key use cases (functionalities or actions) the system provides.
- Show relationships and dependencies among actors and use cases.

### Benefits of Use Case Diagrams:
- **Clarity:** Provide a simple, visual way to understand the scope and boundaries of the system from the user’s perspective.
- **Communication:** Help bridge communication gaps between stakeholders, developers, and designers by providing a common language.
- **Requirement Gathering:** Facilitate identification and validation of functional requirements early in the development process.
- **Documentation:** Serve as valuable artifacts for ongoing project reference and onboarding new team members.
- **Design Foundation:** Guide developers and testers by outlining user-system interactions clearly.

By using Use Case Diagrams, teams can ensure everyone shares a mutual understanding of how the system should behave and how users will engage with it.


The following diagram illustrates the high-level system architecture for the Booking Management System:

![1CASE DIAGRAM](https://github.com/user-attachments/assets/ef0a8729-4e79-495d-81a1-a100b1b21a4c)

![System Architecture Diagram] (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*SkqrFz5Bpcl8LBiPlx3-Fg.png)


### Acceptance Criteria

- Users must be able to review booking details (date, time, resource, price) before finalizing payment.
- Payment options include credit/debit cards and PayPal.
- Users receive confirmation upon successful payment.
- Users can cancel the booking within 5 minutes of checkout without penalty.
- The system prevents double payment for the same booking.
- An email receipt is automatically sent to the user after payment confirmation.
- The checkout process must complete within 3 seconds under normal load.

