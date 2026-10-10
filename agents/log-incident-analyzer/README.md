# Log & Incident Analyzer

Parses server logs, container crash dumps, and stack traces to isolate failure root causes and generate comprehensive SRE incident postmortems.

## Working Folder Structure

- Server Logs: `./logs/`
- Operational Runbooks: `./runbooks/`
- Postmortems: `./postmortems/`

## Example Prompts

- "Analyze the production crash logs in ./logs/app_error.log and identify the root cause."
- "Reconstruct the timeline of events that led to the database connection pool exhaustion."
- "Draft a blameless postmortem with actionable prevention items for this incident."
