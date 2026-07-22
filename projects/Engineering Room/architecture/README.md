# Engineering Room Architecture

> Foundation v1

---

# Purpose

This document defines the architecture of the Engineering Room.

The objective is to describe the responsibilities of the system.

It does not define technologies.

It does not define implementation details.

Architecture answers only one question:

> Who is responsible for what?

---

# System Goal

The Engineering Room coordinates specialized engineering agents to solve software engineering problems through structured conversations.

The user interacts with a single system.

The system coordinates the team.

---

# Core Principle

The Engineering Room coordinates.

Agents think.

The user decides.

---

# System Components

The architecture is composed of four elements.

```
                 User
                   │
                   ▼
          Engineering Room
                   │
        ┌──────────┴──────────┐
        ▼                     ▼
     Agents              Project
```

---

# Components

## User

The user is responsible for:

- Presenting the problem.
- Answering questions.
- Approving important decisions.

The user never coordinates the agents directly.

---

## Engineering Room

The Engineering Room is the coordinator.

Responsibilities:

- Receive user requests.
- Select the current stage.
- Select the active protocol.
- Decide which agent speaks next.
- Coordinate the discussion.
- Produce the final response.

The Engineering Room never replaces the agents.

Its responsibility is coordination.

---

## Agents

Agents are specialists.

Each agent has a specific engineering role.

Examples:

- Engineering Leader
- Problem Analyst
- Research Engineer
- Software Architect
- Backend Engineer
- Frontend Engineer
- QA Engineer
- Leadership Observer

Agents never coordinate the conversation.

Agents respond only when requested by the Engineering Room.

---

## Project

The Project stores all engineering information.

Examples:

- Context
- Decisions
- Documents
- Artifacts
- History

The Project preserves knowledge throughout the engineering lifecycle.

---

# Conversation Flow

Every conversation follows the same structure.

```
User

↓

Engineering Room

↓

Select Stage

↓

Select Protocol

↓

Select Agent

↓

Agent Response

↓

Engineering Room

↓

Next Agent

↓

Final Response
```

The Engineering Room is responsible for controlling the flow.

---

# Engineering Principle

The user talks to the Engineering Room.

The Engineering Room talks to the agents.

Agents never communicate directly with the user.

---

# Responsibilities

| Component | Responsibility |
|------------|----------------|
| User | Present the problem and make final decisions |
| Engineering Room | Coordinate the engineering process |
| Agents | Analyze, reason and provide engineering expertise |
| Project | Preserve engineering knowledge |

---

# Design Principles

The architecture follows five principles.

## 1. Simplicity

Simple is better than complex.

---

## 2. Single Responsibility

Each component has one responsibility.

---

## 3. Coordination

Only the Engineering Room coordinates the system.

---

## 4. Collaboration

Agents collaborate through the Engineering Room.

---

## 5. Human Leadership

The user remains responsible for final engineering decisions.

---

# Scope

This architecture defines responsibilities only.

Technology selection and implementation are documented separately.

---

# Architecture Summary

The Engineering Room is the single point of interaction.

It coordinates specialized engineering agents.

Each agent contributes within its own expertise.

The Project preserves all engineering knowledge.

The user remains the Engineering Leader throughout the engineering process.
