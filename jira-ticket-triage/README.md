# Jira Ticket Triage Bot

A scheduled automation that retrieves active Jira tickets and turns the backlog into a structured daily triage report.

## Workflow

Scheduled Trigger → Make → Jira REST API → Claude API → Google Docs / Drive

## How It Works

1. Make triggers the workflow on a daily schedule.
2. The Jira REST API retrieves active ticket data.
3. The returned ticket data is processed and sent to the Claude API.
4. Claude classifies and summarizes the tickets for triage.
5. A structured daily report is created in Google Docs and stored in Google Drive.

## What I Built

I designed and built the workflow to reduce repetitive backlog review and create a consistent starting point for daily ticket triage.

The project required integrating with the Jira REST API, retrieving and processing ticket data, sending structured information to the Claude API, and automatically generating a reusable downstream document.

During development, Jira changed its search API endpoint from `/rest/api/3/search` to `/rest/api/3/search/jql`. I updated the integration to accommodate the upstream API change and restore the workflow.

## Technical Components

- Make for scheduled workflow orchestration
- Jira REST API for ticket retrieval
- Claude API for classification and summarization
- Google Docs / Drive for document output and storage
- JSON-based API requests and responses
- Scheduled daily execution
- API integration troubleshooting

## Output

The generated triage report was designed to include:

- Priority snapshot
- Critical, high, medium, and low-priority ticket sections
- Blockers log
- Recommended areas of focus
- Standup-ready summary

## Purpose

The project was designed to reduce repetitive manual backlog review by automatically retrieving active Jira tickets and organizing them into a consistent daily triage report.

## Demo

[Watch the Backend Workflow Demonstration](https://drive.google.com/file/d/1SWcp-1nWNx04iSmEdZHAWd3MuAc6Gbng/view?usp=sharing)

The recording shows the scheduled Jira triage workflow and generated report.


## Notes

This is an earlier automation project preserved as part of my technical progression. It was built as a working proof of concept rather than a production-scale system.
