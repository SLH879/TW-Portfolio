# Employee Onboarding Guide — Accessibility Review and Remediation

## Project Overview

This self-directed documentation quality assurance project examines the structure, readability, and accessibility of an existing Employee Onboarding Guide developed in Markdown and published through GitHub.

The review focuses on semantic document structure, procedural list formatting, non-text content, and navigation. It also considers how accessibility requirements can be incorporated into an existing documentation revision workflow.

**Source document:** [Employee Onboarding Guide](../../sops/sop-onboarding-guide.md)

## Project Metadata

| Field | Details |
|---|---|
| Document ID | SOP-Onboarding-001 |
| Source Version | 1.3.2 |
| Document Format | Markdown |
| Publishing Platform | GitHub |
| Review Type | Accessibility and documentation QA |
| Review Status | In progress |
| Reference Standards | WCAG; applicable Section 508 requirements |

## Objectives

- Review the document's heading hierarchy and structural markup.
- Evaluate procedural lists and their relationships to numbered instructions.
- Examine non-text content for adequate text alternatives.
- Identify accessibility-related improvements.
- Document corrective actions and verification results.

## Methodology

The review begins with a source-level inspection of the Markdown document.

The following checks are planned:

1. Inspect heading levels and section organization.
2. Review ordered and unordered lists for semantic relationships.
3. Examine images and diagrams for meaningful text alternatives.
4. Review hyperlink labels and document navigation.
5. Inspect the rendered GitHub document.
6. Record findings, corrections, and remaining limitations.

## Initial Findings

| ID | Location | Finding | Proposed Action | Status |
|---|---|---|---|---|
| A-01 | Section 8.2 | System names are not nested beneath the relevant numbered instruction | Correct Markdown list indentation | Identified |
| A-02 | Section 8.3 | Password requirements use blockquote markup instead of list markup | Replace blockquotes with a semantic list | Identified |
| A-03 | Section 4 | Workflow diagram uses a brief image label | Assess whether a longer text alternative or adjacent process description is required | Review pending |

## Relevant Accessibility Criteria

**WCAG 1.3.1 — Info and Relationships**

Information and relationships conveyed visually should also be programmatically determinable or available through text.

This criterion is relevant when reviewing heading structures and procedural lists.

**WCAG 1.1.1 — Non-text Content**

Meaningful images require appropriate text alternatives.

The onboarding workflow diagram will be reviewed to determine whether its content is adequately represented.

## Remediation and Verification

Corrections will be documented alongside their corresponding source changes.

Verification results will be added after inspection of the rendered Markdown and any relevant manual or automated checks.

A successful source-level correction does not, by itself, establish WCAG or Section 508 conformance.

## Deliverables

- Source onboarding document
- Accessibility findings log
- Documented Markdown corrections
- Verification results
- Summary of remaining limitations

## Project Status

**In progress.** Initial source-level findings have been identified. Remediation verification and a complete accessibility assessment remain outstanding.

This project is a documentation accessibility exercise, not a formal accessibility certification or conformance declaration.