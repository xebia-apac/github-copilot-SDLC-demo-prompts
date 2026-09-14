# GitHub Copilot Demo Prompt Library

A practical prompt library for the `DEMO_SDLC` flow using the RequestHub application.

**Application:** RequestHub

**Scope:** Simple internal request management application

## DEMO_SDLC

Use the prompts below in order during the demo. Each prompt builds on the files or output created by the previous step.

### 01 — Create Business Requirements

**When to use:** Start the demo by defining the business scope for RequestHub.

#### Prompt

```
Create business-requirements.md for RequestHub.

Simple internal request management application:

- Employees create and track requests
- Admins view, assign, and update request priority and status
- Management views simple request counts

Keep the scope limited to these features. Do not include technical details.
```

### 02 — Create Functional Requirements

**When to use:** Use this after `business-requirements.md` is created to describe the requested functionality.

#### Prompt

```
Read business-requirements.md and create functional-requirements.md.

Follow the existing scope exactly. Define only the employee, admin, and dashboard functionality. Do not add extra features.
```

### 03 — Create Technical Requirements

**When to use:** Use this after `functional-requirements.md` is created to define the technical requirements for the locked scope.

#### Prompt

```
Read business-requirements.md and functional-requirements.md and create technical-requirements.md.

Keep the architecture simple for the locked scope. Use a React frontend and a Node.js backend. Do not add authentication, database setup, or external integrations.
```

### 04 — Create RequestHub Custom Agent

**When to use:** Use this after the three requirement files are available to create the custom agent used in the demo.

#### Prompt

```
Create a RequestHub custom agent.

It must follow all three requirement files, keep the scope locked, use simple and clean implementation, create a modern and easy-to-use UI, avoid unnecessary features, and verify the application after implementation.
```

### 05 — Create Implementation Plan

**When to use:** Use this after the requirements and custom agent are ready, before implementation begins.

#### Prompt

```
Read business-requirements.md, functional-requirements.md, and technical-requirements.md.

Create a simple implementation plan for RequestHub. Follow the requirements exactly and do not add any extra features.
```

### 06 — Implement RequestHub

**When to use:** Use this after the implementation plan has been reviewed and approved.

#### Prompt

```
Implement the approved RequestHub plan. Follow the existing requirements and build the application according to the approved plan.
```

### 07 — Review, Refine & Verify

**When to use:** Use this after implementation for final refinement and verification of the core workflow.

#### Prompt

```
Review the implemented RequestHub application and refine it where needed. Keep the locked scope unchanged. Improve the UI, usability, and overall polish. Fix any issues you find, then run the application locally in VS Code and verify the core workflow.
```

## RequestHub Demo Flow

Business Requirements
        ↓
Functional Requirements
        ↓
Technical Requirements
        ↓
RequestHub Custom Agent
        ↓
Implementation Plan
        ↓
Implementation
        ↓
Review & Refine
        ↓
Run & Verify

## Expected Requirement Files

business-requirements.md
functional-requirements.md
technical-requirements.md

These files establish the scope that the subsequent prompts should follow.

## Quick Copy Index

| # | Prompt | Use when |
| --- | --- | --- |
| 01 | Create Business Requirements | Starting the demo |
| 02 | Create Functional Requirements | After business requirements |
| 03 | Create Technical Requirements | After functional requirements |
| 04 | Create RequestHub Custom Agent | After all requirements |
| 05 | Create Implementation Plan | Before implementation |
| 06 | Implement RequestHub | After plan approval |
| 07 | Review, Refine & Verify | After implementation |

Use the prompts in sequence. Each step builds on the files or output created by the previous step.
