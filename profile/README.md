![Localizeflow banner](../assets/banner.png)

# Localizeflow

Localizeflow is a GitHub-native localization infrastructure
built to remove the operational burden of multilingual documentation.

We help developers, open-source maintainers,
and early-stage teams adopt localization
without reviewers, vendors, or complex workflows.

🌐 https://localizeflow.com

---

## The problem

Localization is not difficult because of translation quality.

It is difficult because of operations.

Most localization platforms are built on a single assumption:

**Every translation must be reviewed and managed by humans.**

This assumption leads to:
- reviewer seat management
- approval workflows and QA gates
- vendor coordination
- dedicated dashboards and project management overhead
- expensive enterprise licensing

As a result, localization becomes slow, costly,
and accessible only to large enterprises.

Most teams simply choose not to localize at all.

---

## Who Localizeflow is for

Localizeflow is designed for teams that:
- do not have dedicated reviewers
- cannot justify vendor contracts
- ship documentation frequently
- want localization to run automatically in the background

This includes:
- open-source maintainers
- indie developers
- early-stage startups
- fast-moving product teams

These teams need localization the most,
yet are least able to sustain traditional localization workflows.

---

## Our approach

Localizeflow treats localization as infrastructure,
not as a human-centric workflow.

Once installed, Localizeflow continuously:
- detects documentation changes
- identifies outdated translations
- regenerates them deterministically
- delivers language-scoped pull requests via GitHub

There are no reviewers to assign.
No workflows to manage.
No dashboards you are required to monitor.

If you never open the UI again,
Localizeflow is working as intended.

---

## Installation philosophy

Most localization tools require:
- API keys
- YAML configuration
- custom GitHub Actions
- ongoing operational maintenance

Localizeflow does not.

Install the GitHub App.
Select the documentation paths.
Localization runs continuously.

Localization should be something you *enable* once,
not something you *operate* forever.

---

## Relationship to Co-op Translator

Localizeflow is built on top of **Co-op Translator**,
a Microsoft open-source translation engine
maintained under the Azure GitHub organization.

Co-op Translator provides the core translation capabilities.

Localizeflow adds:
- orchestration and scheduling
- execution reliability
- GitHub-native delivery
- operational abstraction

Together, they enable localization
that scales without human maintenance.

https://github.com/Azure/co-op-translator

---

## How it works

Localizeflow runs as a background automation layer
that keeps translations continuously in sync
as source documentation evolves.

Documentation changes.
Translations stay aligned.

![Localizeflow architecture](../assets/architecture.png)
