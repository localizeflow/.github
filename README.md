# Localizeflow

**GitHub-native automation for maintaining multilingual documentation at scale.**

Localizeflow is a GitHub-first localization automation platform designed to help documentation remain accessible and up to date across multiple languages.  
It focuses on reliability, maintainability, and alignment with open-source governance practices.

---

## Purpose

Open-source documentation evolves continuously.  
As content changes, translations often lag behind due to manual workflows and limited reviewer availability.

Localizeflow addresses this challenge by enabling **automated, repeatable localization workflows** that integrate directly with GitHub and existing contribution models.

---

## Design principles

### GitHub-native by design
Localizeflow operates using standard GitHub primitives:

- Repositories and branches
- Commits and pull requests
- GitHub Apps and Actions

This ensures compatibility with established open-source review, audit, and contribution processes.

### Automation with transparency
Automation is applied to reduce operational overhead while preserving visibility:

- All changes are proposed via pull requests
- Translation updates are fully traceable in Git history
- Maintainers retain full control over merge decisions

### Built for large repositories
Localizeflow is designed to support:

- Documentation-heavy repositories
- Multiple target languages
- Parallel and long-running translation workloads

The system is not constrained by single-run execution limits common in traditional CI-based approaches.

---

## What Localizeflow provides

- Automated detection of source documentation changes
- Regeneration of translated content when updates occur
- Consistent pull request–based delivery of translation updates
- Support for markdown, notebooks, and documentation assets
- Scalable execution using container-based job infrastructure

---

## Relationship to Co-op Translator

Localizeflow builds upon the experience and learnings from **Co-op Translator**, a Microsoft open-source project used across educational and documentation repositories.

- Co-op Translator repository:  
  https://github.com/Azure/co-op-translator

Localizeflow extends this approach to support broader use cases and larger-scale execution, while maintaining compatibility with GitHub-based workflows commonly used in Microsoft OSS projects.

---

## Usage context

Localizeflow is well suited for:

- Large open-source repositories, including Microsoft OSS projects, with global audiences
- Educational and learning-focused documentation
- Projects that require translations to stay synchronized with frequent source updates
- Repositories where manual localization processes are not sustainable

---

## Project status

Localizeflow is under active development and is used in production documentation pipelines.

This organization hosts:
- Core automation and orchestration components
- Supporting libraries and tooling
- Infrastructure code for scalable execution

---

## Additional resources

- Project website:  
  https://localizeflow.com/
- Co-op Translator (Microsoft OSS):  
  https://github.com/Azure/co-op-translator

---

## Participation

Feedback and contributions are welcome through standard GitHub mechanisms, including issues and pull requests.

Localizeflow aims to support sustainable, transparent localization workflows within the open-source ecosystem.
