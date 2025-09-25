# Internal View Onboarding Command

## Parameters
- `--company`: Company name (required)
- `--repo`: GitHub repository URL (required)

## Command
I'm a new developer joining the **{{company}}** team.

**Step 2: The User Workflow & Application Journey (Internal View)**

Now, connect the business context to how the application actually works. Using our internal documentation (e.g., Confluence, design docs), please describe:

**Internal doc links:**

- {{repo}}/issues
- {{repo}}/releases
- {{repo}}/pulls - closed PRs
- and recent commit messages


**The Core User Journey**: Outline the typical, step-by-step path a primary user takes through our application to get value and solve their problem (e.g., from signing up -> creating their first project -> inviting a team member -> seeing results).

**Mapping Journey to Business Goals**: Briefly explain how this user journey directly supports the business model you identified in Step 1 (e.g., 'The journey leads users to a paywall after they've created 3 projects, which aligns with our freemium model').

Export this information into a markdown file named `docs/internal-view.md`.
