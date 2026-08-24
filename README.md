# M365Agents

# Microsoft 365 Copilot Agents — Beginner Setup Guide

A collection of Microsoft 365 Copilot agents designed to help users learn, implement, troubleshoot, and govern Microsoft technologies using **only official Microsoft public documentation**.

These agents are optimized for **Microsoft 365 Copilot Chat** and can be created using the free agent-building capabilities available in Microsoft 365 Copilot. No coding or Copilot Studio license is required — anyone with access to Microsoft 365 Copilot Chat can build one in a few minutes.

---

## Why This Repository Exists

Many AI agents pull information from blogs, forums, social media, or unofficial websites, which can lead to inaccurate or unsupported recommendations.

This repository provides **reusable agent instructions** that:

- Ground responses in official Microsoft content
- Promote Microsoft-supported guidance
- Deliver accurate and supportable answers
- Provide step-by-step implementation assistance
- Help users learn Microsoft technologies faster
- Encourage governance, security, and compliance best practices

---

## Included Agents

### 1. Power Platform Advisor

A specialized Microsoft Power Platform expert focused on:

- Power Apps
- Power Automate
- Microsoft Copilot Studio
- Dataverse
- Power Pages
- Power BI
- AI Builder
- Governance
- Security
- Administration
- Application Lifecycle Management (ALM)

📄 Instructions: [`PowerPlatformAdvisor/Instructions.md`](PowerPlatformAdvisor/Instructions.md)

#### Example Questions

- How do I create a Power App from a SharePoint list?
- What licensing is required for Dataverse?
- How do I implement ALM for Power Platform?
- What is the difference between managed and unmanaged solutions?
- How do I secure a Copilot Studio agent?
- How do Managed Environments work?

---

### 2. Microsoft 365 Helper

A specialized Microsoft 365 advisor focused on:

- Microsoft 365 Copilot
- Copilot Chat
- Microsoft Teams
- SharePoint Online
- OneDrive
- Outlook
- Word
- Excel
- PowerPoint
- Planner
- To Do
- Forms
- Loop
- OneNote
- Viva

📄 Instructions: [`M365Helper/Instructions.md`](M365Helper/Instructions.md)

#### Example Questions

- How do I enable Microsoft 365 Copilot?
- How do I create a SharePoint site?
- How do I share files from OneDrive?
- What are Teams shared channels?
- How does Microsoft 365 Copilot use Microsoft Graph?
- What licenses are required for Microsoft 365 Copilot?

---

## How to Create Your Own Agent (Step-by-Step for Beginners)

You don't need to know how to code. Follow these steps to create either agent in a few minutes.

### Step 1 — Open the agent builder

1. Go to **Microsoft 365 Copilot Chat** (`https://m365.cloud.microsoft/chat` or the Copilot app in Teams/Outlook).
2. In the left sidebar, select **Create agent** (sometimes shown as **Agents → Create**).
3. Choose **Skip to configure** (or **Describe**, then skip the guided questions) so you land on the manual configuration screen with **Name**, **Description**, and **Instructions** fields.

### Step 2 — Name and describe the agent

- **Name**: `Power Platform Advisor` or `Microsoft 365 Helper` (or your own name).
- **Description**: A short sentence, e.g. *"Helps with Power Platform design, governance, and troubleshooting using official Microsoft documentation."*

### Step 3 — Copy and paste the instructions

Open the matching file in this repo and paste its **entire contents** into the **Instructions** box in the agent builder:

- [`PowerPlatformAdvisor/Instructions.md`](PowerPlatformAdvisor/Instructions.md)
- [`M365Helper/Instructions.md`](M365Helper/Instructions.md)

These instructions already tell the agent:

- What its role and mission is
- Which products are in scope
- Which Microsoft websites to prioritize
- How to format answers (step-by-step, beginner-friendly, etc.)
- What it must **never** do (no blogs, Reddit, YouTube, guessing, etc.)

No edits are required — copy, paste, and move to the next step.

### Step 4 — Add knowledge sources (websites)

Instructions alone tell the agent to *prefer* Microsoft sources, but adding the actual websites as knowledge sources makes the agent retrieve and cite real content from them. To do this manually:

1. In the agent builder, scroll to the **Knowledge** section.
2. Select **Add knowledge → Public website** (or **Web content**).
3. Paste each URL one at a time from the list below (matching the agent you're building), then save.

**Power Platform Advisor sources:**

- https://learn.microsoft.com/en-us/power-platform/
- https://learn.microsoft.com/en-us/power-apps/
- https://learn.microsoft.com/en-us/power-automate/
- https://learn.microsoft.com/en-us/microsoft-copilot-studio/
- https://learn.microsoft.com/en-us/power-pages/
- https://learn.microsoft.com/en-us/power-bi/
- https://support.microsoft.com/
- https://adoption.microsoft.com/

**Microsoft 365 Helper sources:**

- https://learn.microsoft.com/en-us/microsoft-365/
- https://learn.microsoft.com/en-us/microsoft-copilot/
- https://learn.microsoft.com/en-us/sharepoint/
- https://learn.microsoft.com/en-us/microsoftteams/
- https://support.microsoft.com/
- https://adoption.microsoft.com/

> 💡 If your Copilot Chat plan doesn't support adding public websites as knowledge sources, that's fine — the instructions text alone will still steer the agent toward Microsoft-only guidance and away from blogs, forums, and unofficial sites.

### Step 5 — Save and publish

1. Select **Create** (or **Save**).
2. Choose who can use the agent (just you, or share with your organization).
3. The agent will now appear in your Copilot Chat agent list.

### Step 6 — Test it

Ask a few sample questions to confirm it behaves as expected:

- "How do I create a Power App from a SharePoint list?"
- "How do I enable Microsoft 365 Copilot?"

Check that the answers:

- Reference Microsoft Learn / Support / Adoption content
- Are step-by-step and beginner-friendly
- Avoid blogs, Reddit, or YouTube as sources
- Say *"I could not verify this information from an official Microsoft source"* when it doesn't know something for certain

---

## Repository Structure

```text
M365Agents/
│
├── README.md
│
├── PowerPlatformAdvisor/
│   ├── Instructions.md
│   └── SampleQuestions.md
│
└── M365Helper/
    ├── Instructions.md
    └── SampleQuestions.md
```

---

## Official Knowledge Sources

Both agents should use only Microsoft-owned public websites.

### Primary Sources

#### Microsoft Learn

Official product documentation, architecture guidance, training resources, implementation guidance, and learning paths.

- [Microsoft Learn](https://learn.microsoft.com)

#### Microsoft Support

Official troubleshooting and support documentation.

- [Microsoft Support](https://support.microsoft.com)

#### Microsoft Adoption

Official adoption, enablement, and change-management guidance.

- [Microsoft Adoption](https://adoption.microsoft.com)

#### Microsoft Product Documentation

Official documentation hosted on Microsoft Learn for Microsoft products and services.

#### Microsoft Tech Community

Microsoft-authored blogs, articles, technical updates, and announcements.

- [Microsoft Tech Community](https://techcommunity.microsoft.com)

---

## Source Priority

When multiple sources exist, agents should prioritize information in the following order:

1. Microsoft Learn
2. Microsoft Support
3. Microsoft Adoption
4. Microsoft Product Documentation
5. Microsoft Tech Community

---

## Agent Design Principles

All agents should:

- Use only official Microsoft information
- Provide accurate and supportable answers
- Be beginner friendly while supporting advanced users
- Offer step-by-step guidance
- Explain both how and why
- Recommend Microsoft best practices
- Highlight prerequisites and dependencies
- Include governance considerations when appropriate
- Include security considerations when appropriate
- Include compliance considerations when appropriate
- Identify licensing requirements when documented by Microsoft
- Clearly distinguish Preview features from Generally Available (GA) features

---

## Agent Constraints

The agents must not:

- Use non-Microsoft websites as authoritative sources
- Use Reddit as a source of truth
- Use personal blogs as official references
- Use YouTube videos as authoritative documentation
- Invent product capabilities
- Guess feature availability
- Guess licensing requirements
- Recommend unsupported solutions
- Provide unverified information
- Speculate about future roadmap items

If information cannot be verified using Microsoft documentation, the agent should respond with:

> I could not verify this information from an official Microsoft source.

---

## Responsible AI

These agents are intended to:

- Promote accurate information
- Reduce misinformation
- Encourage secure deployment practices
- Support governance and compliance objectives
- Improve product adoption
- Improve user education and self-service capabilities

All responses should be grounded in verifiable Microsoft documentation and clearly communicate when information cannot be confirmed.

---

## Contributing

Contributions are welcome.

When updating agent instructions or knowledge sources:

- Prefer Microsoft Learn whenever possible
- Validate all links before publishing
- Remove outdated references
- Avoid adding non-Microsoft sources
- Verify content against current Microsoft documentation

---

## Disclaimer

This repository is a community resource designed to help users create Microsoft 365 Copilot agents that are grounded in official Microsoft public documentation.

Always validate recommendations against the latest Microsoft documentation before implementing solutions in production environments.

Microsoft trademarks, product names, and documentation remain the property of Microsoft Corporation.
