# Localizeflow

Localizeflow is a GitHub-native automation organization
focused on operating and scaling multilingual documentation workflows
for large, fast-moving repositories.

This organization maintains infrastructure and automation
that keep documentation translations continuously in sync
as source content evolves.

---

## What this organization does

Documentation changes constantly.
Translations often don’t.

We run automated localization workflows that:
- detect documentation changes,
- identify outdated translations,
- regenerate them deterministically,
- and deliver language-scoped pull requests via GitHub.

The goal is to keep multilingual documentation accurate
without adding manual maintenance overhead
to contributors or maintainers.

---

## Relationship to Co-op Translator

The automation in this organization is built on
**Co-op Translator**,
a Microsoft open-source project under the Azure GitHub organization.

Localizeflow provides orchestration, scheduling,
and operational layers around this open-source core,
enabling continuous translation updates
for large and fast-moving repositories.

- https://github.com/Azure/co-op-translator
