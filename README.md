# Pega Car Rental System - A Minimum Viable Product (MVP)

This project is a **Minimum Viable Product (MVP)** built on the Pega Platform, designed for a fictional company, Tourist Car Rentals (TCR). Its primary goal is to validate the core business process of an online car rental reservation by building the single most critical workflow: a new customer successfully booking a vehicle.

This MVP focuses on core functionality to prove the solution's viability with minimum initial investment, establishing a foundation for future enhancements.

## 📝 Table of Contents

  - [Core Problem]
  - [MVP Features]
  - [Technology Stack]
  - [Post-MVP Roadmap]
  - [Environment Setup]
  - [Author]
  - [License]

## 🎯 Core Problem

The fundamental business problem this MVP solves is enabling a customer to reserve a car online and ensuring TCR can receive and process that reservation. The focus is exclusively on the 'happy path' for a new customer to test the viability of a digital reservation channel.

## ✨ MVP Features

This MVP includes only the essential features required to complete the core transaction successfully:

  * **New Customer Onboarding:** A simple, functional form for new customers to create an account.
  * **Essential Real-time Validation:** Enforces critical business rules at the point of entry, such as verifying customer age.
  * **Customer Record Creation:** Successfully saves new customer data to a system of record.
  * **Back-Office Approval Step:** Includes a necessary manual approval for new accounts as part of the core workflow.
  * **Basic Vehicle Selection:** Provides a functional, text-based list of available vehicle types for the user to choose from.
  * **Confirmation Screen:** A clear summary of the reservation details before final submission.
  * **Task Routing:** Ensures the completed reservation request is successfully routed to a work queue for processing.

## 🛠️ Technology Stack

  * **Platform:** Pega Platform
  * **Methodology:** Agile (Scrum)

## 🚀 Post-MVP Roadmap

This MVP establishes the foundational workflow. Once the core concept is proven, the product roadmap would focus on enhancing the user experience and operational efficiency by introducing "lovable" features (MLP), such as:

  * **`[Post-MVP]` A separate, streamlined workflow for returning customers** (Login & Skip-Step Logic).
  * **`[Post-MVP]` A dynamic and adaptive user interface** (Hiding/showing fields).
  * **`[Post-MVP]` Visual enhancements** like interactive maps and vehicle images.
  * **`[Post-MVP]` Automated Service-Level Agreements (SLAs)** to optimize back-office processing times.

## ⚙️ Environment Setup

This project was developed on a dedicated Pega Platform instance. It is not a standalone application that can be run with a simple command.

  * **To Review/Run:** The application `Rule-Admin-Product` (RAP) file would need to be imported into a corresponding Pega environment.
  * **Development Credentials:**
      * **Role:** Application Developer
      * **User:** `author@tourist`
      * **Password:** `pega123!`

## 👤 Author

  * **Kavya Sri Meka**
  * [https://www.linkedin.com/in/kavyasrimeka/]
  * [https://github.com/mks257]
