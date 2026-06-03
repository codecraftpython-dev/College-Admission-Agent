# College Admission Agent

## Overview

The College Admission Agent is an AI-powered admission assistance prototype developed using **IBM Orchestrate**, **IBM watsonx.ai**, **IBM Granite Models**, and a **Retrieval-Augmented Generation (RAG)** architecture.

The solution helps students explore admission opportunities by retrieving and analyzing information from uploaded college brochures, counselling documents, cutoff records, and fee structure data. Instead of manually searching through multiple documents, users can ask questions in natural language and receive accurate, document-grounded responses.

This project demonstrates how Agentic AI can automate admission guidance through specialized agents coordinated by IBM Orchestrate.

---

## Problem Statement

Students often struggle to find reliable admission information because details such as eligibility criteria, counselling procedures, cutoff trends, seat availability, and fee structures are distributed across multiple documents and websites.

The objective of this project is to build an intelligent admission assistant that can retrieve, analyze, and summarize admission-related information while providing personalized college recommendations.

---

## Solution Architecture

The system is built using a Multi-Agent AI architecture.

### Technologies Used

* IBM Orchestrate
* IBM watsonx.ai
* IBM Granite Models
* Retrieval-Augmented Generation (RAG)
* Vector Database
* Python

### Data Sources

The knowledge base contains:

* College brochures
* Counselling documents
* Cutoff datasets
* Fee structure documents
* Admission guidelines

Documents are processed, embedded, and indexed for semantic retrieval.

---

## Agents Implemented

### 1. Institute Knowledge Agent

Retrieves and summarizes information from uploaded brochures and admission documents.

### 2. College Recommendation Agent

Suggests colleges based on user inputs such as rank, category, branch preference, and budget.

### 3. Admission Advisory Agent

Provides guidance regarding eligibility, admission chances, and counselling processes.

### 4. Document Query Agent

Answers user questions using information retrieved from brochures, cutoff records, and fee documents.

---

## RAG Workflow

1. Upload admission-related documents.
2. Extract and process document content.
3. Generate embeddings using watsonx.ai.
4. Store embeddings in a vector database.
5. Retrieve relevant information based on user queries.
6. Generate grounded responses using IBM Granite Models.
7. Return personalized admission guidance through IBM Orchestrate agents.

---

## Sample Queries

* Which colleges can I get with a rank of 15,000?
* What is the fee structure for this institute?
* What was the previous year's cutoff for Computer Science?
* Compare admission opportunities for two colleges.
* What documents are required during counselling?
* Which colleges fit within my budget?

---

## Repository Contents

```text
College-Admission-Agent/
│
├── README.md
├── Project_Presentation_ppt.pptx
├── Project_Presentation_pdf.pdf
├── data/
|   ├── brochures/
|   ├── cutoff_data/
|   └── fee_structures/ 
└── images/

---

## Key Features

* Multi-Agent Architecture using IBM Orchestrate
* Retrieval-Augmented Generation (RAG)
* Document-based Question Answering
* College Recommendation Support
* Cutoff and Fee Information Retrieval
* Personalized Admission Guidance
* IBM Granite Model Integration
* Context-Aware Responses

---

## Future Enhancements

* Integration with live counselling portals
* Real-time seat matrix tracking
* Voice-enabled admission assistant
* Multilingual support
* Admission probability prediction
* Mobile and web application interface

---

## Project Status

Prototype Developed on IBM Orchestrate

Current version demonstrates:

* Agent orchestration
* Document retrieval
* RAG-based question answering
* College recommendation workflow

Frontend and production deployment are planned for future development.

---

## Acknowledgements

This project was developed using:

* IBM Orchestrate
* IBM watsonx.ai
* IBM Granite Models

for demonstrating Agentic AI and RAG-based admission assistance.

---

## License

This project is created for educational, academic, and demonstration purposes.
