---
layout: page
title: "STR-SCHEMA — Structural Schema Module"
---

# STR-SCHEMA — Structural Schema Module
*Module defining UMA’s structural schema types and canonical schema composition rules.*

---

# 1. Purpose
The STR-SCHEMA module defines how structural entities, relations, constraints, and identifiers combine into composite structures.

This module:
- defines schema categories  
- defines schema formats  
- defines schema composition rules  
- defines schema-level constraints  
- anchors composite structural representations  

It does not define semantic schemas, behavioral schemas, or developmental workflows.

---

# 2. Scope
STR-SCHEMA applies to:
- all composite structural objects  
- all schema registries  
- all modules that reference schema structures  
- all documentation that describes schemas  

If a composite structure appears in UMA, it must be defined here or in a child schema module.

---

# 3. Schema Categories

## 3.1 Core Schemas
These schemas apply universally across the Structural Plane.

- **Entity Schema** — defines a structured set of entity definitions  
- **Relation Schema** — defines a structured set of relation definitions  
- **Constraint Schema** — defines a structured set of constraint definitions  
- **Composite Schema** — defines a multi‑object structural configuration  

Core schemas must remain domain‑neutral and non‑interpretive.

---

## 3.2 Plane‑Specific Schemas
Each plane may define its own schema types, but they must:
- inherit from Core Schemas  
- remain within their plane’s domain  
- avoid cross‑domain contamination  

Examples (non‑exhaustive):
- Documentation Plane: *document schema, view schema*  
- Governance Plane: *rule schema, permission schema*  
- Developmental Plane: *stage schema, sequence schema*  
- Dynamic Plane: *state schema, transition schema*  
- Integrative Plane: *validation schema, alignment schema*  

These are structural schemas, not semantic models.

---

## 3.3 Composite Structural Schemas
Composite schemas
