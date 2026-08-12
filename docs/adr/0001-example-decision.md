# ADR 0001: Example Architectural Decision

## Status
Accepted

## Context
This is a placeholder ADR used to validate that the Drift Detector's
"Fetch ADRs" step can successfully retrieve content from the
`docs/adr` directory of this repository.

## Decision
We will maintain architectural decisions in `docs/adr/` using
lightweight ADR files like this one.

## Consequences
The Drift Detector workflow can fetch this directory without
receiving a 404, allowing the full pipeline (README + OpenAPI + ADRs)
to reach the Drift Agent.
