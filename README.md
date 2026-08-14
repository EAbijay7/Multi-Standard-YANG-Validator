# Multi-Standard YANG Validator

A standards-aware YANG validation framework for Common/YANG, IETF, BBF, IEEE, and ITU-T workflows.

This repository contains the cleaned final project implementation, validation engine, standard-specific rules, plugins, sample YANG modules, reporting utilities, documentation, and CI configuration.

## Overview

The framework provides a structured validation workflow around YANG models, standard-specific rules, plugin adapters, and machine-readable/human-readable reporting.

## Project Structure

- `yangval/` – validation engine, discovery, rules, reporting, and CLI
- `plugins/` – standard-specific pyang plugin adapters
- `samples/` – sample YANG modules and demos
- `docs/` – architecture, rules, project documentation, demo and verification notes
- `.github/workflows/` – CI workflow

## Supported Standards

- Common/YANG
- IETF
- BBF
- IEEE
- ITU-T

## 📸 Screenshots & Visuals

The repository includes an architecture diagram under `docs/diagrams/architecture.svg`. A dedicated screenshots area is reserved for validation output, reports, UI captures, and other project visuals as they are added.

## Verification

Python syntax checks and CLI/package checks are included. Full pyang-dependent validation is exercised by the CI workflow in an environment with the required dependency.

## Documentation

See:

- `docs/RULES.md`
- `docs/PROJECT_DOCUMENTATION.md`
- `docs/DEMO.md`
- `docs/VERIFICATION.md`

## License

See the repository files for project-specific licensing information.
