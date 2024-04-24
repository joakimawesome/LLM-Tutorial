# LLM Healthcare Agents Project

## Overview
This project explores the application of Large Language Models (LLMs) in the healthcare sector. Utilizing advanced AI techniques, we focus on developing healthcare agents that can perform tasks such as patient communication, clinical decision support, and therapy. The core technology behind our project is the MemGPT model, which enhances traditional LLMs by introducing a memory hierarchy for long-term context retention.

## Features
- **Patient Communication and Triage**: Automate initial patient interactions and preliminary triage using AI-driven conversations.
- **Clinical Decision Support**: Aid healthcare professionals by providing AI-powered insights and support in decision-making processes.
- **Therapy and Mental Health Assistance**: Deliver therapeutic support through conversational agents tailored for mental health care.
- **MemGPT Memory Hierarchy**: Incorporate a hierarchical memory system consisting of core memory and archival memory, managed by a controller to maintain the context and relevance of interactions.

## Components
### MemGPT
- **Core Memory**: Similar to RAM, it holds immediately relevant pieces of conversations.
- **Archival Memory**: Functions like a hard drive, storing vast amounts of information for later retrieval.
- **Controller**: Manages the flow of information between core and archival memories, ensuring that the most relevant information is always at hand.

### Agent Personas
- **Psychiatrist Persona**: Designed to offer psychiatric consultations, prescribe medications, and manage treatment plans.
- **Therapist Persona**: Provides therapy and counseling, supporting patients in managing mental health issues.
- **Nurse Persona**: Focuses on direct patient care, collecting vital information and administering prescribed treatments.

## Getting Started
To get started with this project, clone the repository and install the required dependencies:
```bash
pip install -r requirements.txt
