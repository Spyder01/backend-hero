# 📋 Tasksmith — Java Backend Track  
## Progressive Engineering Roadmap

## Introduction

**Tasksmith** is a **single backend application built progressively**, where each step improves the same Java codebase instead of starting over.

This is the **Java track** of the Tasksmith roadmap.

The goal is not to build a flashy app, but to **develop confidence as a backend engineer** by experiencing how real systems evolve under new requirements.

There will be:
- refactoring
- schema changes
- broken assumptions
- design tradeoffs

And that is intentional.

---

## Core Philosophy

> **One codebase. No rewrites. Only evolution.**

Each task introduces a **real-world constraint** that forces the system to adapt:
- data that must persist
- features that break earlier assumptions
- correctness rules that can’t be ignored
- operational concerns that appear naturally

This mirrors how production systems actually grow.

---

## What This Project Is

- A **backend-first** Java application
- Designed as a **modular monolith**
- Focused on:
  - API design
  - data modeling
  - correctness
  - operability
  - deployment

UI is intentionally not the priority.

---

## What This Project Is *Not*

- ❌ A tutorial-following exercise  
- ❌ A microservices playground  
- ❌ A frontend-heavy project  
- ❌ A “rewrite it properly later” experiment  

Everything built here is meant to be **extended, not discarded**.

---

## End Goal

By the end of this roadmap, Tasksmith should have:
- a non-trivial domain model
- historical data handling
- file and metadata storage
- task dependency graph
- authentication and authorization
- task sharing
- a **self-built deployment pipeline**
- a reproducible **Docker Compose setup**

More importantly, the developer should be able to **explain every architectural and implementation decision** made along the way.

---

## Ground Rules

- Prefer clarity over cleverness
- No premature optimization
- No unnecessary abstractions
- Every feature must justify its existence
- Refactoring is expected, not avoided

---

## How to Use This Roadmap

Each task is added as its own Obsidian entry, containing:
- intent
- requirements
- constraints
- expected learning outcomes

Tasks must be completed **in order**, using the same evolving codebase.
