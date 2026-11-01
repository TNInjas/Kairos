# Kairos

### Exploring what a reliable AI operating layer could look like.

AI agents are becoming increasingly capable of carrying out individual tasks. But getting them to work together, maintain context, respect permissions, recover from interruptions, and remain under meaningful human control is a much bigger challenge.

**Kairos is an attempt to explore that challenge.**

I'm developing Kairos as an independent research and engineering initiative focused on designing an AI operating layer that can coordinate specialised agents and help users work across their digital environments.

This project is still evolving. The architecture is being developed, the specifications are being refined, and many of the underlying technical problems remain open.

That's precisely why I'm interested in building it in public.

## What are we trying to explore?

The current vision for Kairos includes:

- **Multi-agent coordination:** How should specialised agents collaborate on complex tasks?
- **Supervision and governance:** How can a system coordinate its agents without allowing them to exceed their approved authority?
- **Persistent memory:** How can useful context and task continuity be maintained across sessions and environments?
- **Bounded autonomy:** How much independence should an AI agent have, and how should that independence be controlled?
- **Security and reliability:** How should the system handle untrusted information, failures, interruptions, and unexpected behaviour?
- **Long-horizon execution:** How can agents work on complex tasks without silently drifting away from their original objectives?

These aren't solved problems in Kairos. They are the problems we're trying to investigate.

## How we currently envision Kairos

The conceptual design explores three interaction modes:

- **Co-worker Mode:** The user and AI work together, dividing responsibilities.
- **Agent Mode:** AI carries out approved tasks with greater independence.
- **General Assist Mode:** The system handles everyday assistance.

A supervising and governing agent provides coordination and oversight. A Guardian Layer addresses the screening of incoming information, while specialised agents handle different responsibilities.

The underlying principles include human sovereignty, explicit permissions, transparency, memory boundaries, checkpoints, and recovery mechanisms.

## Where the project stands

Kairos currently has a collection of foundational design documents:

| Document | Purpose |
|---|---|
| Concept Brief | Defines the vision and proposed system |
| Constitutional Framework | Establishes governance and authority |
| Organizational Structure | Describes the proposed agent roles |
| KOBS | Defines operational behaviour and system rules |

The Technical Architecture Specification and Kairos Cognitive Architecture Specification (KCAS) are yet to be developed.

**There is no complete working implementation of Kairos at this point.** This repository currently represents the project's research and design stage.

## Why build in public?

I don't think a project of this complexity should develop inside a closed notebook, with every architectural decision going unchallenged.

I'd like to bring together people interested in AI systems, agent architectures, systems engineering, and related research.

That means more than simply finding people to write code.

I want people who are willing to question assumptions, examine existing research, identify weaknesses, propose alternatives, and eventually turn promising ideas into working experiments.

## How can you contribute?

There are several ways to get involved:

- Review existing specifications and identify inconsistencies.
- Investigate technical approaches to unresolved research problems.
- Challenge architectural decisions and propose alternatives.
- Develop small experiments and prototypes.
- Contribute to the implementation as the technical architecture takes shape.

You don't need to be an expert in every area. A well-researched criticism of one architectural decision can be just as valuable as a new implementation.

## A work in progress

Kairos is an ambitious undertaking, and there is a substantial amount of research and engineering ahead.

This repository will evolve as the project does. Ideas may change, specifications may be rewritten, and experiments may prove some of our assumptions wrong.

That's part of the process.

**Research. Question. Experiment. Build.**


