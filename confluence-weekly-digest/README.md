# Confluence Weekly Digest Bot

A scheduled automation that retrieves recently updated Confluence content and turns it into a structured weekly team digest.

## Workflow

Scheduled Trigger → Make → Confluence API → Claude API → Google Docs / Drive

## How It Works

1. Make triggers the workflow on a weekly schedule.
2. The Confluence API retrieves pages updated during the previous seven days.
3. The retrieved content is processed and sent to the Claude API.
4. Claude summarizes the source material into a structured weekly digest.
5. The finished digest is created in Google Docs and stored in Google Drive.

## What I Built

I designed the workflow to automate the repetitive process of reviewing recent Confluence activity and turning distributed updates into a consistent summary.

The project required connecting to the Confluence API, retrieving content within a defined time window, processing the returned data, integrating the Claude API, and generating a reusable downstream document.

## Technical Components

- Make for scheduled workflow orchestration
- Confluence REST API for source-data retrieval
- Claude API for summarization
- Google Docs / Drive for document output and storage
- API authentication and JSON-based requests/responses
- Time-windowed retrieval of recently updated content

## Output

The generated digest was designed to include:

- Weekly activity summary
- Recently updated pages
- Key decisions and action items
- Suggested owners or due dates when supported by the source material
- Team-ready formatted output

## Purpose

The project was designed to reduce repetitive manual Confluence review by automatically retrieving recent activity and converting it into a concise weekly digest.

## Demo

A recorded workflow demonstration is available for this project.

## Notes

This is an earlier automation project preserved as part of my technical progression. It was built as a working proof of concept rather than a production-scale system.
