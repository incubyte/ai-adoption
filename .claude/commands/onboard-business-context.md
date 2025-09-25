# Business Context Onboarding Command

## Parameters
- `--company`: Company name (required)
- `--website`: Company website URL (required)
- `--repo`: GitHub repository URL (optional)

## Command

I'm a new developer joining the **{{company}}** team.

To get the best possible context before diving into the code, I need you to act as my onboarding buddy and walk me through the project in three distinct steps: Business, Workflow, and then Code. Please explain each step clearly.

**Step 1: The Business & Customer Context (Outside-In View)**

First, I want you to ignore the codebase and internal documentation. Act as a market analyst and browse our public website **{{website}}** and any other public marketing materials you can find. Based on that external information, please summarize:

**Our Customers**: Who are the primary users or target audience for our product?

**The Problem We Solve**: What key pain point does our product address for these customers?

**Our Business Model**: How does the company make money (e.g., SaaS subscription tiers, e-commerce, usage-based pricing, advertising)?

**Key Public Features**: What are the main features we advertise to our customers on the website?

{{#if repo}}Use the gh cli tool to fetch any relevant public repositories or documentation from {{repo}} that might provide additional context.{{/if}}
Feel free to search the internet for any recent news articles, press releases, or reviews about {{company}} to gather more insights.

Export this information into a markdown file named `docs/business_context.md`.
