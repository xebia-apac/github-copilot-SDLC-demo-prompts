GitHub Copilot Demo Prompts

A reusable prompt library for the RequestHub GitHub Copilot SDLC demo.

Demo: DEMO_SDLC
Application: RequestHub
Scope: Simple internal request management application

🚀 DEMO_SDLC

Use the prompts below in the listed order during the demo.

01 — Create Business Requirements

When to use: Start of the demo. Use this to define the business scope.

Create business-requirements.md for RequestHub.

Simple internal request management application:

- Employees create and track requests
- Admins view, assign, and update request priority and status
- Management views simple request counts

Keep the scope limited to these features. Do not include technical details.

02 — Create Functional Requirements

When to use: After business-requirements.md is created.

Read business-requirements.md and create functional-requirements.md.

Follow the existing scope exactly. Define only the employee, admin, and dashboard functionality. Do not add extra features.

03 — Create Technical Requirements

When to use: After functional-requirements.md is created.

Read business-requirements.md and functional-requirements.md and create technical-requirements.md.

Keep the architecture simple for the locked scope. Use a React frontend and a Node.js backend. Do not add authentication, database setup, or external integrations.

04 — Create RequestHub Custom Agent

When to use: After the three requirement files are available. Use this to create the custom agent for the demo.

Create a RequestHub custom agent.

It must follow all three requirement files, keep the scope locked, use simple and clean implementation, create a modern and easy-to-use UI, avoid unnecessary features, and verify the application after implementation.

05 — Create Implementation Plan

When to use: After the requirements and custom agent are ready, before implementation.

Read business-requirements.md, functional-requirements.md, and technical-requirements.md.

Create a simple implementation plan for RequestHub. Follow the requirements exactly and do not add any extra features.

06 — Implement RequestHub

When to use: After reviewing/approving the implementation plan.

Implement the approved RequestHub plan. Follow the existing requirements and build the application according to the approved plan.

07 — Review, Refine & Verify

When to use: After the application has been implemented. Use this for the final polish and verification.

Review the implemented RequestHub application and refine it where needed. Keep the locked scope unchanged. Improve the UI, usability, and overall polish. Fix any issues you find, then run the application locally in VS Code and verify the core workflow.

🔄 Demo Flow

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

📁 Expected Requirement Files

business-requirements.md
functional-requirements.md
technical-requirements.md

These files establish the scope that the subsequent prompts should follow.

⚡ Quick Copy Index

#

Prompt

Use When

01

Create Business Requirements

Start

02

Create Functional Requirements

After BR

03

Create Technical Requirements

After FR

04

Create Custom Agent

After requirements

05

Create Implementation Plan

Before implementation

06

Implement RequestHub

After plan approval

07

Review, Refine & Verify

After implementation

💡 Demo Tip

Use the prompts in sequence. Each step builds on the files or output created by the previous step.
