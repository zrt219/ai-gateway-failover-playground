# AI Gateway Failover Playground

This repository is the public-facing landing page for an AI gateway failover playground.

## What this project is for

The goal is to explore how request routing, provider fallback, and failure handling should work when an AI application needs resilience.

## What this project should demonstrate

- provider routing and fallback behavior
- failover and retry strategy design
- error handling that is explicit and reviewable
- boundaries between live calls and simulation
- safe engineering around upstream instability

## Employer-facing framing

A reviewer should see this as a reliability-focused systems demo: the point is not just to call a model, but to keep the application usable when a gateway or provider fails.

## Status

- Public repo scaffold: yes
- Employer-facing README: yes
- Production status: not claimed unless separately verified

## Good next additions

- architecture diagram
- routing/failover examples
- local test instructions
- recorded failure scenarios and expected behavior
