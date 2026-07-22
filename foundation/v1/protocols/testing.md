# Engineering Conversation Protocol (ECP-007)

> Testing & Validation Protocol
> Foundation v1

---

# Protocol Information

**Protocol ID**

ECP-007

---

**Protocol Name**

Testing & Validation

---

**Related Stage**

Stage 06 — Testing

---

# Objective

Validate that the implemented system satisfies its engineering requirements, architectural decisions, and business objectives.

Testing provides evidence.

Validation provides confidence.

---

# Trigger

Start automatically after:

- Development has been approved.
- The Working Software Increment is complete.
- Acceptance criteria are defined.

---

# Participants

## Engineering Leader

Approves progression based on validation evidence.

---

## QA Engineer

Leads testing activities.

Defines validation strategy.

Evaluates test coverage.

---

## Backend Engineer

Supports backend issue investigation.

Fixes implementation defects.

---

## Frontend Engineer

Supports frontend issue investigation.

Fixes implementation defects.

---

## Software Architect

Evaluates whether defects reveal architectural weaknesses.

---

## Leadership Observer

Evaluates collaboration, communication, and engineering discipline.

---

# Facilitator

QA Engineer

---

# Decision Authority

Engineering Leader

---

# Meeting Rules

- Validate requirements before features.
- Test behavior, not implementation.
- Every defect must be reproducible.
- Every critical defect must have a root cause analysis.
- Testing must remain objective and evidence-based.

---

# Discussion Flow

## Phase 1 — Validation Scope

Review:

- Functional requirements
- Non-functional requirements
- Acceptance criteria
- ADRs

Expected Output

Validation Scope

---

## Phase 2 — Test Execution

Execute planned validation activities.

Examples:

- Unit Testing
- Integration Testing
- System Testing
- End-to-End Testing
- Performance Testing
- Security Testing
- Accessibility Testing

Expected Output

Test Execution Report

---

## Phase 3 — Defect Analysis

Classify discovered defects.

For each defect identify:

- Severity
- Impact
- Reproducibility
- Root cause

Expected Output

Defect Register

---

## Phase 4 — Root Cause Review

Determine whether failures originate from:

- Implementation
- Architecture
- Requirements
- Environment
- Test Design

Expected Output

Root Cause Analysis

---

## Phase 5 — Quality Assessment

Evaluate overall software quality.

Review:

- Reliability
- Performance
- Security
- Maintainability
- User Experience

Expected Output

Quality Assessment Report

---

## Phase 6 — Release Readiness

Determine readiness.

Possible outcomes:

- APPROVED
- CONDITIONAL APPROVAL
- REWORK REQUIRED

Expected Output

Validation Approval

---

# Conflict Resolution

If disagreement exists:

1. Reproduce the issue.
2. Review requirements.
3. Review architecture.
4. Review implementation.
5. Review evidence.
6. Engineering Leader makes the final decision.

---

# Outputs

This protocol produces:

- Validation Scope
- Test Execution Report
- Defect Register
- Root Cause Analysis
- Quality Assessment Report
- Validation Approval

---

# Completion Criteria

Testing is complete only when:

- Acceptance criteria are satisfied.
- Critical defects are resolved.
- Remaining known issues are documented.
- Root causes have been analyzed.
- Engineering Leader approves progression.

---

# Leadership Reflection

The Leadership Observer evaluates:

- Was validation objective?
- Were failures treated as learning opportunities?
- Was collaboration effective?
- Were root causes investigated instead of symptoms?
- Did the team preserve engineering quality under pressure?

---

# Engineering Principle

Testing measures correctness.

Validation measures confidence.

Engineering is complete only when evidence demonstrates that the system fulfills its intended purpose.
