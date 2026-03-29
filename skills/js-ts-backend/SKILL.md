---
name: js-ts-backend
version: 0.1.0
description: Build and review Node.js/TypeScript backend services with clean structure, validation, and tests.
---

# When to use
- Designing or refactoring Node.js/TypeScript backend code
- API design, DTO validation, error handling, logging

# Inputs
- Feature description
- Current folder structure
- Constraints (perf, security, infra)

# Outputs
- Suggested file layout
- TypeScript interfaces/types
- API contract guidance
- Test strategy

# Workflow
1) Clarify requirements and constraints.
2) Propose structure (routes/controllers/services/repositories).
3) Implement minimal working version.
4) Add validation + error handling.
5) Provide test plan.

# Guardrails
- Avoid any; prefer strict types.
- Keep functions small and testable.
