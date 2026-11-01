# Kairos: Documentation & Development Status

**Last updated:** 1 November 2026

## 1. Current Position

Project Kairos is currently progressing through the development of its conceptual architecture, organizational framework, constitutional principles, and operational specifications.

The existing documentation establishes what Kairos is intended to be, how its proposed agent organization is structured, what principles govern it, and how its components are expected to behave.

However, the project has not yet completed the technical and cognitive architecture specifications required to define its concrete implementation.

This repository documents the current state of the project. Architectural proposals, defined behavioral contracts, and implemented capabilities must be treated as distinct things.

## 2. Existing Project Documentation

### 2.1 Project Kairos Concept Brief

**Version:** 0.3  
**Document status:** Ongoing

Establishes the product vision, intended operating environments, three interaction modes, high-level architecture, and supporting product mechanisms.

The concept describes an AI operating layer working across local machine environments, browser-based workflows, and cloud-backed virtual workspaces.

It establishes three operating modes:

- Co-worker Mode
- Agent Mode
- General Assist Mode

It also describes the supervising layer, mode-specific agents, Guardian Layer, memory, continuity, security, checkpoints, and recovery mechanisms.

### 2.2 Kairos Organizational Structure

**Version:** 2.1

Defines the organizational architecture, responsibilities, procedures, core values, and mechanisms governing the proposed Kairos agent organization.

Version 2.1 incorporates revisions addressing:

- Supervisor bottlenecking.
- Memory consistency.
- Inter-agent trust.
- Goal-versus-plan deviation.
- Authority boundaries.
- Continuous security monitoring.
- Performance measurement.
- Escalation clarity.
- Constitutional scope.

It also identifies reliable long-horizon autonomy as an unresolved problem rather than claiming to have solved it.

### 2.3 Kairos Constitutional Framework

**Version:** 2.0  
**Document status:** Draft

Establishes the governing principles and authority structure applicable to Kairos components.

Its scope includes:

- Foundational identity and mission.
- Priority and authority hierarchy.
- Human sovereignty and interruption.
- Task execution and goal alignment.
- Security and ethical boundaries.
- Memory, identity, and organizational learning.
- Agent roles and responsibilities.
- Distributed authority and failover.
- Governance, amendments, accountability, and measurement.

It explicitly recognizes reliable long-horizon autonomy as an open problem.

### 2.4 Kairos Operational Behavior Specification (KOBS)

**Version:** 1.1  
**Document status:** Draft — First complete draft following external technical review.

KOBS serves as the behavioral specification connecting the Constitutional Framework and Organizational Structure to the future technical and cognitive architecture.

It defines how Kairos components are expected to respond to operational triggers, the sequence of actions they follow, and the resulting system states.

Its twenty chapters cover:

- Task lifecycle: Intake, Plan, Execute, Checkpoint, and Report.
- Goal deviation and security behavior.
- Flags, escalation, and rollback.
- Memory and inter-agent collaboration.
- Conflict resolution and failover.
- Mode handoff and human sovereignty.
- Measurement and open research problems.
- Operational and resource constraints.
- Long-running task behavior.
- Cross-document version governance.

KOBS deliberately remains implementation-independent. It defines behavioral contracts without prescribing the internal reasoning mechanisms or concrete implementation.

It is intended to undergo review against its source documents through the Kairos governance process before being treated as authoritative.

## 3. Future Specifications

Two major specifications remain to be developed.

### 3.1 Kairos Technical Architecture

This specification is expected to define:

- Concrete system architecture and implementation.
- Resource allocation mechanisms.
- Numerical operational thresholds.
- Implementation of the behavioral constraints established by KOBS.

### 3.2 Kairos Cognitive Architecture Specification (KCAS)

This specification is expected to define the internal evaluation and reasoning mechanisms behind the decisions described in KOBS.

These include how Kairos evaluates alternatives, makes judgments, and reaches decisions within its established authority boundaries.

Neither specification is currently documented as completed.

## 4. Open Research Problems

Reliable long-horizon autonomy is explicitly identified as an unresolved problem in the existing organizational and constitutional documentation.

Other unresolved areas include the internal cognitive evaluation methods delegated to KCAS and the implementation-level mechanisms delegated to the Technical Architecture.

KOBS also classifies its mechanisms as Solved, Partially Solved, or Open Research. These classifications describe the completeness of their behavioral specification, not the existence of implemented software.

## 5. Development Principles

The development of Kairos is guided by the following principles:

- Architectural proposals must be distinguished from implemented capabilities.
- Behavioral specifications must remain consistent with higher-priority governing documents.
- Technical decisions must be supported by research and validation.
- Open problems must remain explicitly identified.
- Changes to governing documents must preserve cross-document compatibility.
- Reliability claims must be supported by evidence.

## 6. Current Documentation Boundary

The existing documents establish a substantial conceptual and operational foundation for Kairos.

They do not, by themselves, demonstrate a complete working implementation.

Future development must connect the established product vision, organizational structure, constitutional framework, and behavioral specification to concrete cognitive and technical architectures, followed by experimental validation and implementation.

---

*This document records the state of the currently established Kairos documentation. It does not imply that proposed capabilities have already been implemented.*
