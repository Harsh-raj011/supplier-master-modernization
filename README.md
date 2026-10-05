# Supplier Master Modernization

A training capstone project based on Oracle Fusion Cloud Applications ERP (Financials), focused on modernizing supplier master data and improving supplier information exchange and retrieval.

## Project Overview

The solution addresses supplier master-data challenges by:

- Converting priority supplier data into Oracle Fusion Cloud with traceability to legacy supplier records.
- Publishing supplier information to downstream AP and procurement systems through a REST-based integration.
- Providing an AI-powered interface for retrieving supplier information using a supplier number.

## Platform & Technologies

- Oracle Fusion Cloud Procurement / Supplier Management
- Oracle Supplier Import / Supplier Master
- Oracle Fusion REST API / Supplier Business Object
- Oracle Integration
- Oracle AI Agent Studio
- Business Objects, Functions, Tools, Topics and Agents
- Descriptive Flexfields (DFF)

## Solution Components

### 1. Supplier Master Data Conversion

Priority supplier records are prepared using the Oracle supplier interface template and imported into Oracle Fusion Cloud. Conversion-source information and legacy supplier numbers are maintained for traceability.

### 2. Outbound Supplier Interface

An Oracle Integration flow receives supplier information, maps the required fields, and invokes the Oracle Fusion Supplier REST service to create or update supplier information.

### 3. AI-Studio Supplier Query Agent

An AI Studio supplier query agent uses a configured supplier lookup tool to retrieve supplier information from Oracle Fusion based on a supplier number and present the result conversationally.

## Key Concepts Demonstrated

- Supplier master data management
- Data conversion and traceability
- REST API integration
- Data mapping
- Oracle Fusion business objects
- Descriptive Flexfields
- AI agent configuration
- Enterprise application integration

## Repository Note

This repository contains an original project summary and documentation created from the training capstone. It does **not** contain the original training question paper, solution document, private credentials, Oracle environment exports, or proprietary training screenshots.

## Project Context

This project was completed as part of training in the Oracle Fusion Cloud Applications ERP (Financials) stream.

> Note: This repository documents the project at a high level. It does not claim client-production deployment or independent ownership of the underlying Oracle platform.
