# AI Sprint Report Generator

An automated workflow that turns structured sprint inputs into a stakeholder-ready report.

## Workflow

Typeform → Make → Claude API → Google Docs / Drive

## How It Works

1. A structured Typeform collects sprint information across 17 fields.
2. Make receives the submission and orchestrates the workflow.
3. The collected data is sent to the Claude API.
4. Claude generates a formatted sprint report.
5. The finished report is created in Google Docs and stored in Google Drive.

## What I Built

I designed and built the complete workflow from structured data collection through API integration and automated document generation.

I had no prior hands-on API or workflow automation experience when I started. I worked through JSON errors, API deprecations, and workflow logic until the output was reliable and professionally formatted.

## Technical Components

- Typeform for structured input collection
- Make for workflow orchestration
- Claude API for report generation
- Google Docs / Drive for document output and storage
- JSON-based API requests and responses

## Purpose

The project was designed to reduce repetitive manual sprint-report preparation by collecting information in a consistent format and automatically turning it into a reusable stakeholder-facing document.

## Demo

[Watch the Backend Workflow Demonstration](https://drive.google.com/file/d/12HSZCrV4hq3Bs4dneSZScZTwkxq3pg3r/view?usp=sharing)

The recording shows the automation workflow and generated output.

## Notes

This is an earlier automation project preserved as part of my technical progression. It was built as a working proof of concept rather than a production-scale system.
