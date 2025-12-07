# OctoAcme Project Management Documentation

This repository contains comprehensive documentation for OctoAcme's project management practices and processes. It serves as a central knowledge base for team members to understand how we deliver projects effectively and collaboratively.

## Repository Structure

- **docs/** - Project management process documentation and guides
- **.github/** - GitHub workflows, issue templates, and automation
- **.devcontainer/** - Development environment configuration

## Getting Started

1. Browse the process documents in the `docs/` folder to understand OctoAcme's project management approach
2. Review relevant guides based on your role (Developer, Product Manager, or Project Manager)
3. Refer to the [Project Management Overview](octoacme-project-management-overview.md) for a comprehensive introduction
4. See the [Roles and Personas](octoacme-roles-and-personas.md) document for role-specific responsibilities

## Project Management Processes

OctoAcme uses Agile practices with **2-week sprints** and maintains a prioritized backlog managed by a Product Manager. Our workflow includes regular backlog grooming, sprint planning, daily standups, and retrospective meetings.

We follow **PR-driven development** with required code review from at least one reviewer. All PRs must pass automated CI checks (GitHub Actions) before merging. We use labels and milestones to track work, follow semantic versioning for releases, and maintain ADRs (architecture decision records) in the docs/ folder for institutional knowledge.

**Onboarding** includes an onboarding checklist, shared documentation, and pairing sessions to help new team members integrate quickly.

## Contribution & PR Process

1. **Open an issue** to discuss new features or changes using the GitHub issue templates
2. **Create a branch** following the naming convention: `feature/description` or `fix/description`
3. **Link PRs to issues** by including "Closes #issue-number" or "Refs #issue-number" in the PR description
4. **Add reviewers** - at least one reviewer is required for all PRs
5. **Pass required checks** - automated CI/CD tests and linting must pass before merging
6. **Keep PRs small** (≤400 lines when possible) for easier review and faster merging

## Documentation & Resources

### Process Documents
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

### Team Contacts
For questions or support, reach out to:
- **Project Managers** - for delivery coordination and timeline questions
- **Product Managers** - for feature prioritization and roadmap inquiries
- **Repository maintainers** - for technical questions and code reviews

---

*This documentation is maintained by the OctoAcme team. Please keep it updated as processes evolve.*
