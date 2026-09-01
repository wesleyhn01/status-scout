# Status Scout

Automates job-application tracking by scanning Gmail for application-related emails and logging the results (date, company, status) to a Google Sheet.

I built this to solve a real problem during my own job search — manually tracking dozens of applications across Handshake, LinkedIn, and direct company sites got unmanageable fast.

> 🕰️ **Note:** This was my first full-stack project, built while learning backend development and API integration. I've kept the original code to show that progression.

## What it does
- Searches Gmail for job-application emails (Handshake, LinkedIn, or custom keyword queries)
- Extracts key info: application date, company, status
- Writes results to a connected Google Sheet
- Exports results as a downloadable database or text file

## Tech stack
`Python` `Flask` `Gmail API` `Google Sheets API`

## Why it's worth a look
- End-to-end API integration, including OAuth
- Automates a genuinely tedious manual task
- First project combining backend logic, external APIs, and a web interface

## Setup
```bash
git clone https://github.com/<username>/status-scout.git
cd status-scout
pip install -r requirements.txt
python app.py
```
You'll need your own Gmail API and Google Sheets API credentials — see [Google's API docs](https://developers.google.com/workspace) for setup.

## Current limitations
- Frontend is minimal (HTML only, no JS interactivity yet)
- Error handling and credential security could be more robust
- No automated tests yet
- Single-user only

I list these because I think being upfront about a project's real state is more useful to anyone evaluating my work than polishing over the gaps.

## Roadmap
- React-based frontend
- Data visualization of application stats
- Multi-user support
- Cloud deployment
