# Codebase View Onboarding Command

## Parameters
- `--company`: Company name (required)

## Command
I'm a new developer joining the **{{company}}** team.

Please analyze the codebase and explain:

**High-Level Architecture**: What is the overall software architecture that supports this user journey (e.g., microservices, monolith, serverless)?

**Mapping Code to the Journey**: Which services, repositories, or major directories correspond to the key steps in the user journey? (For example: 'The Sign-Up step is handled by the auth-service, the Project Creation step is handled by the project-service, etc.').

**Starting Points**: Based on this mapping, what are the 2-3 most important code repositories or directories I should look at first to understand the core logic?

Export this information into a markdown file named `docs/codebase-view.md`.
