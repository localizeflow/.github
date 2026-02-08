![Localizeflow banner](../assets/banner.png)

# Localizeflow

Effortless localization automation for documentation.

Localizeflow is a GitHub-native automation infrastructure
that removes the operational burden of multilingual documentation.

Built for developers, open-source maintainers,
and early-stage teams who want localization to run
without reviewers, vendors, or complex workflows.

🌐 https://localizeflow.com

---

## The problem

Localization is not blocked by translation quality.

It is blocked by operations.

Most localization platforms assume one thing:

**Every translation must be reviewed and managed by humans.**

That assumption creates:
- reviewer management
- approval workflows and QA gates
- vendor coordination
- dashboards and project overhead
- enterprise-grade pricing

As a result, localization becomes slow, expensive,
and inaccessible to most teams.

So teams decide not to localize at all.

---

## Who this is for

Localizeflow is for teams that:
- do not have reviewers
- do not want vendor contracts
- ship documentation frequently
- do not want to spend time setting up localization workflows
- want localization to run automatically

This includes:
- open-source maintainers
- indie developers
- early-stage startups
- fast-moving product teams

These teams need localization the most,
but cannot afford to operate or configure it.

---

## Our approach

Localizeflow treats localization as infrastructure.

Not as a workflow.
Not as a project.
Not as a dashboard.

During setup, you connect your repository
and choose the documentation paths and languages.

After that, Localizeflow continuously:
- detects documentation changes
- identifies outdated translations
- regenerates them deterministically
- opens language-scoped pull requests

No reviewers.
No workflows.
No ongoing management.

Once setup is complete,
if you rarely need to open the UI again,
it is working as intended.

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



