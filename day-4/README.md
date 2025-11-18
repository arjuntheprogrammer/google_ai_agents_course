# Day 4 – Observability & Evaluation

## Overview
Day 4 zooms in on measuring agent quality. You will instrument observability signals, set up evaluation harnesses, and analyze failure modes before shipping.

## Contents
- `day-4a-agent-observability.ipynb`: Captures traces, structured logs, and key metrics for every agent step.
- `day-4b-agent-evaluation.ipynb`: Builds automated eval suites plus human spot-check workflows to score agent responses.
- `4. Agent Quality.pdf`: Slides outlining reliability KPIs and checklists for debugging live agents.

## How to use this day
1. Use the PDF to align on the metrics and heuristics that matter for your deployment.
2. Execute notebook A with your tracing provider (OpenTelemetry, LangSmith, etc.) enabled to see rich traces.
3. Finish notebook B to script regression tests that catch hallucinations or unsafe tool calls early.
