# Project Documentation

## Purpose

The Multi-Standard YANG Validator provides a standards-aware workflow for validating YANG models against common/YANG, IETF, BBF, IEEE, and ITU-T rules.

## Main Components

- `yangval/` contains discovery, environment handling, validation, rule evaluation, findings, reporting, and CLI logic.
- `plugins/` contains standard-specific pyang adapters.
- `samples/` contains example YANG modules and demonstrations.
- `docs/RULES.md` documents the rule catalogue and sources.
- `docs/diagrams/architecture.svg` presents the overall architecture.

## Workflow

YANG model → discovery/standard detection → validation engine → standard rules/plugins → findings → HTML/JSON/CSV reports.

## Reproducibility

Install dependencies from `requirements.txt` and run `./run.sh --help` or the documented validation commands.
