# distilled_supervisor_Buonano

## GW Supervisor Agent

This repository develops an AI-distilled academic supervisor framework for gravitational-wave research.

The goal is not to replace human supervision, but to encode a structured supervisory workflow:
- academic taste;
- project scope control;
- literature-based criticism;
- code review;
- figure review;
- dissertation planning;
- PhD application positioning.

The initial use case is an MSc dissertation project on the luminosity-distance/inclination degeneracy in compact-binary gravitational-wave inference.

## Core Research Context

The project focuses on:

- Bayesian inference in gravitational-wave parameter estimation;
- luminosity-distance/inclination-angle degeneracy;
- synthetic detector network comparison;
- PSD/noise scenario testing;
- posterior visualization;
- possible qualitative comparison with GW170817.
- theoretical methods to break the degeneracy analytically

## Repository Goals

1. Build reusable prompt profiles for AI-assisted academic supervision.
2. Create strict review protocols for research ideas, figures, code, and dissertation sections.
3. Develop a gravitational-wave-specific supervisor profile.
4. Document how AI supervision can support non-traditional students entering physics research.

## What is included

- `prompts/master_supervisor_prompt.md` — the reusable supervisory operating system.
- `prompts/profiles/gw_supervisor_profile.md` — a gravitational-wave profile informed by Alessandra Buonanno's public scholarship and teaching materials.
- `sources/buonanno_open_resources.md` — a dated, reproducible map of official pages, open lectures, teaching materials, and representative open papers.

## Important limitation

This project does **not** reproduce Alessandra Buonanno's private views, private supervision, voice, or personality, and it must not present itself as her. It distils publicly evidenced research habits—such as combining analytic approximations with numerical relativity, testing models across regimes, and tying theoretical accuracy to observables—into an independent AI review framework. Any claim about supervisory practice is explicitly labeled as an inference.

## Use

1. Load `prompts/master_supervisor_prompt.md` as the base instruction.
2. Append `prompts/profiles/gw_supervisor_profile.md` as the domain profile.
3. Give the agent a concrete artifact: a research question, derivation, notebook, figure, code diff, or dissertation section.
4. Ask for one review mode: `scope`, `derivation`, `code`, `figure`, `literature`, `writing`, `milestone`, or `viva`.

The default MSc project is a controlled study of the luminosity-distance/inclination degeneracy in compact-binary gravitational-wave inference. The profile contains a minimum viable study, staged extensions, analytic checks, and acceptance criteria.

## Current status

Version 1.0 provides a complete prompt package and source map. The source inventory was last checked on 2026-06-23; live publication indexes remain the canonical route for newly released work.
