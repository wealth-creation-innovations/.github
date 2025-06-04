# Contributing to MetaMirror

Thank you for your interest in contributing to MetaMirror, a project of Wealth Creation Innovations LLC d/b/a MetaMirror.

## How to Contribute
- **Search existing issues** before submitting a new one to avoid duplicates.
- For bug reports, feature requests, and user stories, use the appropriate issue template.
- For questions or support, see [SUPPORT.md](./SUPPORT.md).
- Pull requests should be linked to an open issue and follow our coding standards.

---

## SAFe-Aligned Issue Management & Templates

MetaMirror uses the Scaled Agile Framework (SAFe) for all issue management. All contributors must use the provided issue templates and follow these requirements:

### Issue Types & Required Fields

| Type        | Required Fields                                                                                 |
|-------------|-----------------------------------------------------------------------------------------------|
| **Epic**    | Business Value (1-100), Epic Owner (@username), PI Assignment, Epic Summary, Acceptance Criteria, Child Features |
| **Feature** | Business Value (1-100), Story Points (Fibonacci), Feature Owner (@username), Parent Epic (#), Summary, User Stories, Acceptance Criteria |
| **User Story** | Story Points (Fibonacci), Story Owner (@username), Parent Feature (#), User Story (As a..., I want..., so that...), Acceptance Criteria, Definition of Done (Checklist) |
| **Task**    | Task Owner (@username), Parent Story/Feature (#), Task Description, Acceptance Criteria, Definition of Done (Checklist) |
| **Bug**     | Bug Owner (@username), Parent Story/Feature (#), Bug Description, Acceptance Criteria (Checklist), Steps to Reproduce, Environment |

- **All fields marked required in the template must be completed.**
- Use GitHub usernames (e.g., @johndoe) for Owner fields.
- Use issue numbers or links (e.g., #123) for Parent/Child references.
- Story Points must use the Fibonacci sequence: 1, 2, 3, 5, 8, 13, 21.
- Business Value is a 1-100 score for prioritization.
- Definition of Done must be a checklist.

### Labeling Conventions
- Each issue type is automatically labeled: `type: epic`, `type: feature`, `type: story`, `type: task`, `type: bug`.
- Do not use legacy or custom type labels.
- Additional labels (priority, team, etc.) may be added as appropriate.

### Parent/Child Links
- Features must reference their parent Epic.
- User Stories must reference their parent Feature.
- Tasks and Bugs must reference their parent Story or Feature.
- Use the issue number or link (e.g., #123) in the appropriate field.

### Definition of Done
- All User Stories and Tasks must include a Definition of Done as a checklist.
- Bugs must include a fix validation checklist in Acceptance Criteria.

### Compliance & Audits
- Issues missing required fields, labels, or links will be flagged for correction.
- Regular audits are performed to ensure SAFe compliance.
- Contributors are responsible for updating issues if requirements change.

For more details, see the issue templates in `.github/ISSUE_TEMPLATE/`.

---

## Code of Conduct
All contributors must adhere to our Code of Conduct. By participating, you agree to abide by these guidelines.

## Review Process
- All contributions are reviewed by maintainers.
- Please ensure your code is well-documented and tested.
- We reserve the right to reject contributions that do not align with our goals or standards.

## Legal
By contributing, you agree that your contributions are owned by Wealth Creation Innovations LLC d/b/a MetaMirror and may be incorporated into the project under the project's license.