# AI HR Interview Automation — n8n

An AI-assisted HR interview and candidate screening automation system built with n8n, AI Agents, APIs and workflow automation.

The project is designed to automate repetitive recruitment tasks while keeping candidate evaluation and hiring decisions structured, reviewable and human-controlled.

## Overview

This project demonstrates an end-to-end HR interview automation workflow that helps organize candidate intake, interview scheduling, interview result processing and hiring decision workflows.

The goal is not to replace human judgment, but to reduce repetitive administrative work and provide a structured process for HR teams.

## Key Features

- Candidate intake automation
- AI-assisted candidate screening
- Structured interview workflow
- Automated interview scheduling
- Interview result processing
- AI-generated interview notes and evaluation
- Structured candidate scoring
- Decision automation
- Automated workflow routing using n8n
- Human-controlled hiring decisions
- API and webhook integrations

## Automation Workflows

### 1. Candidate Intake

Handles the initial candidate information and starts the recruitment workflow.

**Key tasks:**
- Receive candidate information
- Process candidate data
- Start the screening workflow
- Route information to the appropriate automation stages

### 2. Interview Scheduling Automation

Automates the interview scheduling workflow after the candidate reaches the interview stage.

**Key tasks:**
- Manage interview scheduling
- Process interview-related information
- Automate workflow communication
- Connect scheduling with the recruitment workflow

### 3. Interview Results & Final Hiring

Processes interview results and generates structured interview information for the next stage of the recruitment process.

**Key tasks:**
- Process interview results
- Generate structured interview notes
- Organize evaluation information
- Prepare results for the hiring workflow

### 4. Decision Automation

Handles the structured decision workflow based on the available candidate and interview information.

**Key tasks:**
- Evaluate workflow conditions
- Route candidates through appropriate paths
- Generate structured outcomes
- Support the final human-controlled hiring decision

## Workflow Architecture

```text
Candidate Intake
       ↓
Candidate Screening
       ↓
Interview Scheduling
       ↓
Interview Process
       ↓
Interview Results
       ↓
Decision Automation
       ↓
Final Hiring Workflow
