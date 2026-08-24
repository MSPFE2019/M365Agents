# M365Agents
# Microsoft 365 Copilot Agents

A collection of Microsoft 365 Copilot agents designed to help users learn, implement, troubleshoot, and govern Microsoft technologies using **only official Microsoft public documentation**.

These agents are optimized for **Microsoft 365 Copilot Chat** and can be created using the free agent capabilities available in Microsoft 365 Copilot. They are intentionally designed to use public Microsoft websites as their only authoritative knowledge sources.

---

## Why This Repository Exists

Many AI agents pull information from blogs, forums, social media, or unofficial websites, which can lead to inaccurate or unsupported recommendations.

The goal of this repository is to provide reusable agent instructions that:

- Ground responses in official Microsoft content
- Promote Microsoft-supported guidance
- Deliver accurate and supportable answers
- Provide step-by-step implementation assistance
- Help users learn Microsoft technologies faster
- Encourage governance, security, and compliance best practices

---

## Included Agents

### Power Platform Advisor

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

#### Example Questions

- How do I create a Power App from a SharePoint list?
- What licensing is required for Dataverse?
- How do I implement ALM for Power Platform?
- What is the difference between managed and unmanaged solutions?
- How do I secure a Copilot Studio agent?
- How do Managed Environments work?

---

### Microsoft 365 Helper

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

#### Example Questions

- How do I enable Microsoft 365 Copilot?
- How do I create a SharePoint site?
- How do I share files from OneDrive?
- What are Teams shared channels?
- How does Microsoft 365 Copilot use Microsoft Graph?
- What licenses are required for Microsoft 365 Copilot?

---

## Repository Structure

```text
Microsoft365-Copilot-Agents/
│
├── README.md
│
├── PowerPlatformAdvisor/
│   ├── Instructions.md
│   ├── KnowledgeSources.md
│   └── SampleQuestions.md
│
└── M365Helper/
    ├── Instructions.md
    ├── KnowledgeSources.md
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

## Recommended Knowledge Sources

### Power Platform Advisor

- https://learn.microsoft.com/power-platform/
- https://learn.microsoft.com/power-apps/
- https://learn.microsoft.com/power-automate/
- https://learn.microsoft.com/microsoft-copilot-studio/
- https://learn.microsoft.com/power-pages/
- https://learn.microsoft.com/power-bi/

### Microsoft 365 Helper

- https://learn.microsoft.com/microsoft-365/
- https://learn.microsoft.com/microsoft-copilot/
- https://learn.microsoft.com/sharepoint/
- https://learn.microsoft.com/microsoftteams/

### Shared Sources

- https://support.microsoft.com
- https://adoption.microsoft.com
- https://techcommunity.microsoft.com

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
