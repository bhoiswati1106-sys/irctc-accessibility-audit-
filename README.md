# IRCTC Accessibility Audit

## Project Overview

This project focuses on conducting an accessibility audit of the IRCTC website.
The purpose of this audit is to identify accessibility barriers that may affect users with disabilities,
including users who depend on keyboards, screen readers, and other assistive technologies.

The project also organizes audit evidence, findings, and testing resources in a structured repository.

## Objectives

- Identify accessibility issues on the IRCTC website.
- Review website components against WCAG accessibility guidelines.
- Document accessibility issues with screenshots and evidence.
- Record the impact and severity of each issue.
- Provide recommendations for improving accessibility.
- Maintain a structured repository for future development and testing.

## Audit Scope

The audit focuses on the following areas:

- Form fields and input controls
- Dropdown and menu controls
- Accessible names and ARIA attributes
- Alternative text for images
- Form labels
- Button and text color contrast
- Keyboard and assistive technology accessibility

## Audit Findings

The audit findings are documented in the `tests/accessibility-audit.xlsx` file.

Each finding includes relevant information such as:

- Issue ID
- Affected website component
- Accessibility problem
- WCAG reference
- Evidence
- Severity
- User impact
- Recommended fix
- Issue status

## Evidence

Screenshots and Lighthouse evidence are stored in the `docs` directory.

The documented issues include:

- `WEB-001.png`
- `WEB-002.png`
- `WEB-003.png`
- `WEB-004.png`
- `WEB-005.png`

## Repository Structure

    irctc-accessibility-audit/
    ├── client/
    ├── docs/
    │   ├── lighthouse-evidence/
    │   ├── WEB-001.png
    │   ├── WEB-002.png
    │   ├── WEB-003.png
    │   ├── WEB-004.png
    │   └── WEB-005.png
    ├── server/
    ├── tests/
    │   ├── .gitkeep
    │   └── accessibility-audit.xlsx
    ├── package.json
    └── README.md

## Tools and Technologies

- HTML
- CSS
- JavaScript
- Lighthouse
- WCAG Accessibility Guidelines
- Git
- GitHub
- Microsoft Excel

## Project Status

The initial repository architecture and accessibility audit documentation have been completed.

The audit findings are documented and require further review, implementation of fixes, and re-testing.

## Future Work

- Review and fix the identified accessibility issues.
- Perform manual keyboard accessibility testing.
- Test the website using screen readers.
- Re-test the website using Lighthouse.
- Update the audit spreadsheet after fixes.
- Add automated accessibility testing.
- Maintain accessibility documentation and evidence.
