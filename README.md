# Citadel Operations

Citadel Operations is a fictional dual-use geospatial intelligence company based in Belfast, Northern Ireland. Its mission is to combine satellite intelligence, drone operations and AI-driven analysis to support surveillance, operational decisions and critical infrastructure protection.

The planned Citadel Geospatial Intelligence Platform helps defence contractors and energy organisations monitor geographical areas, analyse satellite/drone information and prepare operational or intelligence reports. Its two fictional customers are **Sentinel Defence Systems** and **Northstar Oil & Gas**, whose information must remain strictly separated.

Platform roles are **Customer Analyst**, **Customer Administrator** and **Citadel Platform Administrator**. The reference design includes a public website and customer application with secure login, a separate admin portal, application and public partner APIs, a database, a private imagery/document store and an AI chatbot. Azure AI Foundry versus AWS Bedrock remains undecided.

Company facts follow the user-supplied Company Summary. Data categories, AI capabilities and priority risks remain proposals. This is a planning exercise; no live product, deployment or passing security test is claimed.

## Session 1 workspace

- [Confluence: Citadel Operations](https://citadeloperations42.atlassian.net/wiki/spaces/CIT)
- [Session 1 epic — KAN-4](https://citadeloperations42.atlassian.net/browse/KAN-4)
- [Session 2 epic — KAN-5](https://citadeloperations42.atlassian.net/browse/KAN-5): do not start before 22 November 2026.
- [Company story](https://citadeloperations42.atlassian.net/wiki/spaces/CIT/pages/458754)
- [Team roles](https://citadeloperations42.atlassian.net/wiki/spaces/CIT/pages/131217)
- [Data inventory](https://citadeloperations42.atlassian.net/wiki/spaces/CIT/pages/557057)
- [Architecture](https://citadeloperations42.atlassian.net/wiki/spaces/CIT/pages/589825)
- [Security requirements](https://citadeloperations42.atlassian.net/wiki/spaces/CIT/pages/589842)
- [Decisions log](https://citadeloperations42.atlassian.net/wiki/spaces/CIT/pages/491555)
- [Incident runbook](https://citadeloperations42.atlassian.net/wiki/spaces/CIT/pages/622593)

## Editable diagrams

Open these files in draw.io / diagrams.net:

- [Organisation chart](docs/org-chart.drawio) — KAN-8. The user is the only security engineer; AI assistants support the product owner, UX, architecture/full-stack, data, AI engineering, QA and delivery roles.
- [Architecture](docs/architecture.drawio) — KAN-11. This is a logical reference design with application, data and external AI trust boundaries. Azure AI Foundry versus AWS Bedrock remains undecided.

The same editable diagrams and rendered previews are attached to their Confluence pages. They do not establish that the draw.io Confluence app has been installed or tested.

## Working rules

- Use fictional data only; never real customers, people or employer systems.
- Never commit credentials, tokens, passwords or other secrets.
- Keep this repository private.
- Start commit messages with the relevant Jira ticket key and link evidence from Jira.
- Preserve undecided choices explicitly. Proposed risk appetite needs founder acceptance.
- Session 1 contains no application code, deployment or passing security-test claims.

## Authorized repository scope

This repository update contains only this README and the two draw.io diagrams. The broader starter's company.md, decisions.md, .gitignore, .env.example, role skills and gitleaks hook are outside the user's latest GitHub authorization. Their original acceptance criteria are therefore not claimed complete. Company story and decisions are documented in Confluence.

The App register summary has not been posted externally/publicly; that publication requires user confirmation.

Based on the Cyber Agoge Project Build Room starter, adapted for Citadel Operations.
