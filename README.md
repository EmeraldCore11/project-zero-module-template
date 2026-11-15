# Project Zero — Module Template

This repository will hold the reusable starter template and authoring guidance for Project Zero modules.

## Purpose

Provide a consistent starting point for future modules while keeping modules independently understandable, versioned, permission-aware, and compatible with Project Zero's documented interfaces.

## Planned template elements

The exact starter files will be derived from the approved module infrastructure and module lifecycle specifications. Likely areas include:
- module manifest and stable identity;
- module purpose, ownership, provenance, and version;
- declared dependencies and compatibility;
- requested capabilities and permissions;
- public interfaces and extension contracts;
- configuration and default settings;
- validation and test guidance;
- documentation and change history.

Do not treat this list as a finalized manifest schema. The approved specifications must define the actual fields and validation rules.

## Guardrails

- A module must not bypass protected core or platform authorization.
- Dependencies must be declared; installation or dependency changes must never happen silently.
- Creator rights and derivative permissions must be respected.
- Compatibility and version requirements must be explicit.
- Template changes must remain aligned with the master repository's approved documentation.

See the master repository: https://github.com/EmeraldCore11/project_zero
