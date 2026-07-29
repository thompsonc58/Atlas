# Document Catalog

## Purpose

The Atlas Document Catalog serves as the official registry of publications within the Atlas Curriculum Engineering Framework (ACEF).

The catalog provides a centralized inventory of all officially recognized Atlas documents, including handbooks, standards, specifications, templates, reference implementations, research publications, and governance documents.

Each publication is assigned a unique document identifier, version number, publication status, and classification to support governance, traceability, configuration management, and lifecycle management.

The Document Catalog is maintained as a living document and shall be updated whenever a new Atlas publication is created, revised, published, or retired.

---

# Publication Categories

Atlas publications are organized into the following categories.

| Prefix | Category | Purpose |
|----------|----------|---------|
| ATLAS-HBK | Handbook | Body of knowledge for Curriculum Engineering |
| ATLAS-STD | Standard | Normative requirements |
| ATLAS-SPEC | Specification | Detailed implementation guidance |
| ATLAS-TMP | Template | Reusable implementation artifacts |
| ATLAS-REF | Reference Implementation | Demonstrations of Atlas in practice |
| ATLAS-RSR | Research Publication | Research papers and technical reports |
| ATLAS-GOV | Governance | Governance policies and procedures |
| ATLAS-ADR | Architecture Decision Record | Significant architectural decisions |
| ATLAS-CAT | Catalog | Official publication registries |

---

# Publication Status

Every Atlas publication shall have one of the following lifecycle states.

| Status | Description |
|----------|-------------|
| Planned | Approved for future development. |
| Draft | Actively being authored. |
| Review | Under technical or editorial review. |
| Candidate | Approved pending publication. |
| Published | Official public release. |
| Deprecated | Scheduled for retirement. |
| Archived | Historical publication retained for reference. |

---

# Current Publications

## Handbooks

| ID | Title | Version | Status |
|----|-------|---------|--------|
| ATLAS-HBK-001 | Atlas Handbook: Foundations of Curriculum Engineering | 1.0.0 | Draft |

---

## Standards

| ID | Title | Version | Status |
|----|-------|---------|--------|
| ATLAS-STD-001 | Documentation Standard | Planned |
| ATLAS-STD-002 | Repository Organization Standard | Planned |
| ATLAS-STD-003 | Curriculum Artifact Standard | Planned |
| ATLAS-STD-004 | Traceability Standard | Planned |
| ATLAS-STD-005 | Quality Assurance Standard | Planned |
| ATLAS-STD-006 | Governance Standard | Planned |

---

## Specifications

| ID | Title | Version | Status |
|----|-------|---------|--------|
| ATLAS-SPEC-001 | Academic Program Specification | Planned |
| ATLAS-SPEC-002 | Course Specification | Planned |
| ATLAS-SPEC-003 | Module Specification | Planned |
| ATLAS-SPEC-004 | Lesson Specification | Planned |
| ATLAS-SPEC-005 | Assessment Specification | Planned |

---

## Templates

| ID | Title | Version | Status |
|----|-------|---------|--------|
| ATLAS-TMP-001 | Program Template | Planned |
| ATLAS-TMP-002 | Course Template | Planned |
| ATLAS-TMP-003 | Module Template | Planned |
| ATLAS-TMP-004 | Lesson Template | Planned |
| ATLAS-TMP-005 | Assessment Template | Planned |

---

## Reference Implementations

| ID | Title | Version | Status |
|----|-------|---------|--------|
| ATLAS-REF-001 | Software Development AAS Reference Implementation | Planned |

---

## Research Publications

| ID | Title | Version | Status |
|----|-------|---------|--------|
| ATLAS-RSR-001 | The Case for Curriculum Engineering | Planned |
| ATLAS-RSR-002 | Knowledge Transformation in Higher Education | Planned |

---

## Governance

| ID | Title | Version | Status |
|----|-------|---------|--------|
| ATLAS-GOV-001 | Atlas Governance Model | Planned |
| ATLAS-GOV-002 | Publication Management Policy | Planned |
| ATLAS-GOV-003 | Version Management Policy | Planned |

---

## Architecture Decision Records

| ID | Title | Status |
|----|-------|--------|
| ATLAS-ADR-001 | Handbook versus Wiki Documentation | Planned |
| ATLAS-ADR-002 | Curriculum Engineering as an Engineering Discipline | Planned |
| ATLAS-ADR-003 | Layered Documentation Architecture | Planned |
| ATLAS-ADR-004 | Separation of Standards from the Handbook | Planned |
| ATLAS-ADR-005 | Atlas Studio as an Independent Platform | Planned |

---

# Document Identifier Format

Atlas publication identifiers follow a standardized naming convention.

```
ATLAS-<CATEGORY>-<NUMBER>
```

Examples:

```
ATLAS-HBK-001
ATLAS-STD-004
ATLAS-SPEC-002
ATLAS-TMP-005
ATLAS-REF-001
```

Identifiers are permanent and shall never be reused, even if a publication is retired.

---

# Version Control

Each publication maintains its own version history using Semantic Versioning (SemVer).

```
Major.Minor.Revision
```

Examples:

```
1.0.0
1.1.0
2.0.0
```

Version numbers are managed independently for each publication.

---

# Cross-Referencing

Atlas publications may reference one another through their official document identifiers.

For example:

- ATLAS-HBK-001 defines the concepts of Curriculum Engineering.
- ATLAS-STD-004 establishes traceability requirements.
- ATLAS-SPEC-002 explains how those requirements apply to course development.
- ATLAS-TMP-002 provides a reusable course template.
- ATLAS-REF-001 demonstrates the complete implementation.

This layered approach ensures consistency, traceability, and clear separation of responsibilities across the Atlas Framework.

---

# Maintenance

The Document Catalog is maintained by the Atlas Governance process.

Updates shall occur whenever:

- A publication is created.
- A publication is revised.
- A publication changes status.
- A publication is retired.
- A new publication category is introduced.

The Document Catalog serves as the authoritative source for the publication inventory of the Atlas Curriculum Engineering Framework.
