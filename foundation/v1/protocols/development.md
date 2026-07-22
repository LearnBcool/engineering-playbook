# Engineering Conversation Protocol (ECP-006)

> Development Protocol
> Foundation v1

---

# Protocol Information

**Protocol ID**

ECP-006

---

**Protocol Name**

Development

---

**Related Stage**

Stage 05 — Development

---

# Objective

Transform the approved engineering plan into a working software system.

Development is the disciplined execution of approved engineering decisions.

The objective is to implement the system while preserving architectural integrity, engineering quality, and project traceability.

---

# Trigger

Start automatically after:

- Planning has been approved.
- Implementation Plan is available.
- Development environment is ready.

---

# Participants

## Engineering Leader

Removes blockers.

Makes implementation decisions outside the team's authority.

Approves significant engineering changes.

---

## Software Architect

Ensures implementation remains aligned with the approved architecture.

Evaluates proposed architectural changes.

---

## Backend Engineer

Implements backend services.

---

## Frontend Engineer

Implements frontend interfaces.

---

## QA Engineer

Defines acceptance criteria.

Continuously validates implementation.

---

## Infrastructure Engineer

Supports development environments and deployment readiness.

---

## Leadership Observer

Evaluates collaboration, communication, and engineering discipline.

---

# Facilitator

Engineering Leader

---

# Decision Authority

Engineering Leader

Architectural changes require Software Architect participation.

---

# Meeting Rules

- Follow the approved architecture.
- Follow the approved implementation plan.
- Do not introduce unnecessary complexity.
- Every significant engineering decision must be documented.
- Code quality is everyone's responsibility.
- Test continuously.
- Integrate continuously.

---

# Discussion Flow

## Phase 1 — Sprint / Iteration Kickoff

Review:

- Current milestone
- Scope
- Priorities
- Risks

Expected Output

Iteration Goal

---

## Phase 2 — Task Assignment

Assign engineering work.

Ensure responsibilities are clear.

Expected Output

Execution Board

---

## Phase 3 — Implementation

Develop software according to:

- Architecture
- ADRs
- Coding standards

Expected Output

Working Software Increment

---

## Phase 4 — Continuous Validation

Verify:

- Functional correctness
- Integration
- Code quality
- Test execution

Expected Output

Validation Report

---

## Phase 5 — Blocker Resolution

Identify:

- Technical blockers
- Team blockers
- External blockers

Expected Output

Blocker Register

---

## Phase 6 — Change Requests

Evaluate implementation changes.

If a proposed change impacts architecture:

- Pause implementation.
- Create a new ADR.
- Return to the Architecture stage if required.

Expected Output

Approved Change Requests

---

## Phase 7 — Iteration Review

Review completed work.

Confirm readiness for Testing.

Possible outcomes:

- READY FOR TESTING
- CONTINUE DEVELOPMENT

Expected Output

Development Approval

---

# Conflict Resolution

When implementation conflicts arise:

1. Review requirements.
2. Review architecture.
3. Review ADRs.
4. Identify the source of disagreement.
5. Escalate architectural conflicts to the Software Architect.
6. Engineering Leader makes the final decision when necessary.

---

# Outputs

This protocol produces:

- Working Software Increment
- Validation Report
- Blocker Register
- Approved Change Requests
- Development Approval

---

# Completion Criteria

Development is complete only when:

- Planned work has been implemented.
- Acceptance criteria are satisfied.
- Tests pass.
- Code has been reviewed.
- Architecture remains consistent.
- Engineering Leader approves progression.

---

# Leadership Reflection

The Leadership Observer evaluates:

- Was implementation aligned with the architecture?
- Were blockers handled efficiently?
- Did collaboration remain effective?
- Were engineering standards respected?
- Were changes properly documented?

---

# Engineering Principle

Development is disciplined execution.

Good engineering is measured not by the amount of code written, but by the quality, maintainability, and traceability of the software delivered.
