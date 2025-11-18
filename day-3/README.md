# Day 3 – Sessions & Memory

## Overview
Day 3 focuses on context engineering: keeping long-lived agent conversations coherent, summarizing state, and persisting memory safely across sessions.

## Contents
- `day-3a-agent-sessions.ipynb`: Implements short- and long-running sessions, threading metadata, and configuring storage policies.
- `day-3b-agent-memory.ipynb`: Experiments with vector stores, recap summaries, and selective recall patterns.
- `3. Context Engineering_ Sessions & Memory.pdf`: Conceptual guide for balancing recall fidelity with privacy and cost.

## How to use this day
1. Read the PDF for diagrams on session stitching and recap strategies.
2. Work through notebook A to understand how session IDs and transcripts flow through the agent loop.
3. Use notebook B to plug in your own memory backend (Weaviate, Pinecone, etc.) and compare recall strategies.
