# Day 2 – Agent Tools & MCP

## Overview
Day 2 drills into tool-augmented agents and shows how the Model Context Protocol (MCP) simplifies interoperability. Expect to register tools, route calls, and adopt best practices for resilient tool plans.

## Contents
- `day-2a-agent-tools.ipynb`: Demonstrates registering tools, validating schemas, and letting the agent choose the optimal tool sequence.
- `day-2b-agent-tools-best-practices.ipynb`: Applies guardrails, retries, and human-in-the-loop fallbacks for safer tool executions.
- `2. Agent Tools & Interoperability with Model Context Protocol (MCP).pdf`: Reference slides explaining MCP concepts and integration checklists.

## How to use this day
1. Review the MCP PDF for vocabulary and architectural diagrams.
2. Run notebook A to connect a sample tool stack (REST, MCP servers, or mock tools) and watch the planner route calls.
3. Finish with notebook B to harden the workflow using validation hooks and telemetry suggested in the reading.
