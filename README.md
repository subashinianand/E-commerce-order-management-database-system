#BuySmart E-Commerce Order Management Database System

 Week 1 – Requirement Analysis ,BRD,SRS

---

## Project Overview

This project focuses on analyzing the business requirements of an E-Commerce Order Management Database System.
The aim is to understand the business processes, identify stakeholders, define system requirements, and prepare
a Software Requirement Specification (SRS) document before the database design phase.The proposed system will manage
customer registration, product information, inventory, order processing, payment management, shipment tracking, supplier
information, and customer reviews using a centralized database.

---

## Project Objectives

- Analyze the business requirements of the system.
- Identify stakeholders and their roles.
- Define functional requirements.
- Define non-functional requirements.
- Identify project scope.
- List assumptions and constraints.
- Prepare a Software Requirement Specification (SRS).

---

## Core Entities

The project uses the following mandatory entities:

- Customer
- Category
- Product
- Supplier
- Order
- Order Details
- Payment
- Shipment
- Review

---

## Features

- Customer Management
- Product Management
- Category Management
- Supplier Management
- Order Processing
- Payment Management
- Shipment Tracking
- Customer Reviews
- Business Report Support

---

## Deliverables

The repository contains the following documents:

- Requirement Analysis Report
- Business Requirement Document (BRD)
- Stakeholder Analysis
- Functional Requirements
- Non-Functional Requirements
- Project Scope
- Assumptions and Constraints
- Software Requirement Specification (SRS)
- README.md

---

## Technologies Used

- Microsoft Word
- GitHub
- Markdown

---

---



## Conclusion

This project provides a detailed analysis of the business requirements for an E-Commerce Order Management Database System.
The documentation serves as the foundation for future database design, ER modeling, normalization, SQL implementation, and report generation.

---

WEEK-2

Entity Analysis & Entity Relationship Analysis

Objective

The objective of this task is to identify the entities involved in the E-Commerce Order Management System, define their attributes, primary keys, foreign keys, and analyze the relationships between them. This helps in designing an efficient and well-structured database.

Task Performed
Identified all entities in the system.
Defined attributes for each entity.
Assigned Primary Keys (PK) and Foreign Keys (FK).
Applied database constraints.
Analyzed relationships between entities.
Identified relationship cardinality (1:1 and 1:M).
Prepared Entity Analysis Report.
Prepared Entity Relationship Analysis Report.
Entities Identified
Customer
Product
Category
Supplier
Order
Order_Item
Payment
Shipment
Review
Relationship Types
One-to-One (1:1)
One-to-Many (1:M)
Tools Used
Microsoft Word
MySQL
MySQL Workbench
Draw.io (ER Diagram)
Files Included
Entity Analysis Report.docx
Entity Relationship Analysis Report.docx
README.md
Learning Outcomes
Understood database entity identification.
Learned Primary Key and Foreign Key concepts.
Understood database constraints.
Learned relationship mapping and cardinality.
Improved database design skills.
Conclusion

Week 2 focused on analyzing the entities and their relationships in the ShopEasy E-Commerce Order Management Database System.
The completed reports provide a strong foundation for creating the ER diagram and implementing the database in MySQL during 
the next phase of the project.




# Week 3 –
Entity Relationship (ER) Diagram and Relational Schema Design


**E-Commerce Order Management Database System**

## Overview
This Week 3 activity focuses on designing the **Entity Relationship (ER) Diagram** and converting it into a **Relational Schema** for the E-Commerce Order Management Database System. The objective is to transform the conceptual database design created in Week 2 into a logical database structure that can be implemented in the following weeks.

## Objectives
- Design a complete ER Diagram.
- Represent all entities and their attributes.
- Identify Primary Keys (PK) and Foreign Keys (FK).
- Define relationships between entities.
- Specify relationship cardinality and participation constraints.
- Convert the ER model into a Relational Schema.
- Verify the correctness of relationship mapping.
- Prepare the ER Diagram and Relational Schema Design Report.

## Entities Included
- Customer
- Product
- Category
- Supplier
- Orders
- Order_Item
- Payment
- Shipment

## Relationships
- Customer → Orders (1:M)
- Orders → Order_Item (1:M)
- Product → Order_Item (1:M)
- Category → Product (1:M)
- Supplier → Product (1:M)
- Orders → Payment (1:1)
- Orders → Shipment (1:1)

## Relational Schema
The relational schema includes all database tables with:
- Primary Keys (PK)
- Foreign Keys (FK)
- Attributes
- Relationship mapping between tables

## Folder Structure
```
Week3/
│── ER_Diagram.png
│── Relational_Schema.pdf
│── ER_Design_Report.pdf


## Learning Outcomes
- Understand ER modeling concepts.
- Design relationships with appropriate cardinality.
- Convert conceptual models into relational schemas.
- Prepare database documentation for implementation.

