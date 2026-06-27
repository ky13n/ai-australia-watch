# Database Schema

This document defines the first version of the AI Australia Watch database.

## 1. Projects

Tracks data centres, AI infrastructure projects, and related physical developments.

Fields:

- project_name
- project_type
- status
- company_id
- location_name
- suburb
- state
- latitude
- longitude
- decision_level
- decision_maker
- approval_status
- energy_notes
- water_notes
- risk_level
- summary
- last_updated

## 2. Companies

Tracks companies involved in AI infrastructure, cloud, data centres, lobbying, defence, privacy, and policy influence.

Fields:

- company_name
- company_type
- website
- headquarters
- australia_presence
- known_projects
- lobbying_notes
- security_notes
- privacy_notes
- environmental_notes
- summary
- last_updated

## 3. Government Actions

Tracks bills, inquiries, approvals, planning decisions, procurement decisions, and policy changes.

Fields:

- action_title
- action_type
- government_level
- jurisdiction
- decision_maker
- status
- related_company
- related_project
- summary
- concern_notes
- source_url
- last_updated

## 4. Concerns

Tracks risks and issues linked to a project, company, or government action.

Fields:

- concern_title
- concern_type
- severity
- related_project
- related_company
- related_government_action
- plain_english_summary
- evidence_notes
- source_url
- last_updated

## 5. Actions

Tracks campaigns, petitions, submissions, legal pathways, consultations, and contact-your-representative options.

Fields:

- action_title
- action_type
- organiser
- jurisdiction
- related_project
- related_company
- related_government_action
- action_url
- deadline
- plain_english_summary
- last_updated

## 6. Sources

Tracks evidence for each record.

Fields:

- source_title
- source_type
- publisher
- url
- date_published
- date_accessed
- related_project
- related_company
- related_government_action
- reliability_notes
