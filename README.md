# AI Workflow Automation Portfolio

A collection of earlier workflow automation projects I built to explore how structured inputs, APIs, AI models, and automation platforms could reduce repetitive operational work.

These projects were built before I began formally studying data engineering. They represent early hands-on experience designing workflows, integrating external systems through APIs, troubleshooting integration issues, and producing structured downstream outputs.

## Projects

### 1. AI Sprint Report Generator

**Workflow:** Typeform → Make → Claude API → Google Docs / Drive

Collects structured sprint information through Typeform, processes the submission through an automated workflow, sends the data to Claude for report generation, and creates a stakeholder-ready sprint report in Google Docs.

### 2. Confluence Weekly Digest Bot

**Workflow:** Scheduled Trigger → Make → Confluence API → Claude API → Google Docs / Drive

Retrieves recently updated Confluence content on a schedule, processes the source data, generates a summarized weekly digest, and creates a team-ready document.

### 3. Jira Ticket Triage Bot

**Workflow:** Scheduled Trigger → Make → Jira REST API → Claude API → Google Docs / Drive

Retrieves active Jira ticket data, processes and classifies the tickets, and generates a structured daily triage report containing priorities, blockers, and recommended areas of focus.

During development, the Jira search API changed from `/rest/api/3/search` to `/rest/api/3/search/jql`. I updated the integration to accommodate the upstream API change.

## What These Projects Demonstrate

- REST API integration
- Workflow orchestration with Make
- Structured data collection and transformation
- LLM API integration
- Scheduled automation
- Automated document generation
- Troubleshooting API and JSON issues
- Adapting integrations to upstream API changes

## Historical Context

These are preserved as earlier automation projects rather than production systems. They document the progression of my technical work and the problem-solving patterns that later led me toward deeper study of data engineering and system architecture.
