# Nemesis

> An autonomous coding agent engineered to comprehend, modify, execute, and iteratively rectify software systems.

Nemesis is an agentic software engineering system designed to transcend conventional code-generation paradigms.

Rather than functioning as a passive conversational assistant that merely proposes code, Nemesis operates directly upon a software repository. It analyzes the existing codebase, establishes contextual dependencies, decomposes the requested objective into executable subtasks, performs code modifications, invokes development tools, executes tests, interprets failures, and iteratively refines its implementation.

The fundamental objective is simple:

**Give Nemesis a software problem. Let it investigate, implement, execute, and rectify the solution.**

---

## Overview

Contemporary coding assistants predominantly optimize for code generation. However, software engineering is inherently iterative. A generated implementation is only useful when it integrates correctly with the surrounding system and satisfies its execution and testing constraints.

Nemesis is designed around this complete development cycle:

```text
User Objective
      |
      v
Repository Reconnaissance
      |
      v
Contextual Analysis
      |
      v
Task Decomposition
      |
      v
Implementation
      |
      v
Execution & Verification
      |
      v
Failure Analysis
      |
      v
Iterative Rectification
      |
      +----------------------+
      |                      |
      | Verification Failed  |
      |                      |
      +----------<-----------+
      |
      v
Verified Implementation
