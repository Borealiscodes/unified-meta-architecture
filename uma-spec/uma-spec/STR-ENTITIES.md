---
   layout: page
   title: "STR-ENTITIES — Structural Entities Module"
---

   # STR-ENTITIES — Structural Entities Module
   *Module defining UMA’s structural entities and their canonical representations.*
# 1. Purpose
The STR-ENTITIES module defines UMA’s structural entities and their canonical representations.  
Entities are the fundamental objects that appear in the Structural Plane and are referenced across all other planes.

This module:
- defines entity categories  
- defines entity formats  
- defines entity identifiers  
- defines entity-level constraints  
- anchors all structural references  

It does not define behavior, development, or governance.

---

# 2. Scope
STR-ENTITIES applies to:
- all structural objects  
- all entity registries  
- all modules that reference entities  
- all documentation that describes entities  

If an object appears in UMA, it must be defined here or in a child entity module.

---

# 3. Entity Categories

## 3.1 Core Entities
These are the foundational objects of UMA’s architecture.

- **Entity** — the base structural object  
- **Relation** — a defined connection between entities  
- **Constraint** — a structural limitation on entities or relations  
- **Identifier** — a stable reference to an entity  

Core entities must remain domain‑neutral and non‑interpretive.

---

## 3.2 Plane‑Specific Entities
Each plane may define its own entity types, but they must:
- inherit from Core Entities  
- remain within their plane’s domain  
- avoid cross‑domain contamination  

Examples (non‑exhaustive):
- Documentation Plane: *Document, View, Anchor*  
- Governance Plane: *Rule, Invariant, Permission*  
- Developmental Plane: *Stage, Sequence, Prerequisite*  
- Dynamic Plane: *State, Transition, Process*  
- Integrative Plane: *Check, Alignment, Validation*  

These are structural categories, not behaviors.

---

## 3.3 Composite Entities
Composite entities are structures built from multiple entities.

Examples:
- **Schema** — a structured collection of entity definitions  
- **Registry** — a canonical list of entities  
- **Map** — a structured representation of relationships  

Composite entities must not introduce interpretation or narrative.

---

# 4. Entity Representation Rules

## 4.1 Canonical Format
All entities must include:
- a **name**  
- a **type**  
- a **description** (non‑interpretive)  
- an **identifier**  
- optional **attributes** (structural only)  

Descriptions must not infer meaning beyond structure.

---

## 4.2 Identifier Rules
Identifiers must be:
- stable  
- unique  
- non‑semantic  
- non‑interpretive  
- persistent across versions  

Identifiers must not encode meaning, intent, or narrative.

---

## 4.3 Attribute Rules
Attributes must:
- describe structure only  
- avoid interpretive content  
- avoid behavioral logic  
- avoid developmental logic  

Attributes are structural metadata.

---

# 5. Entity‑Level Constraints

Entities must not:
- infer user intent  
- encode narrative meaning  
- collapse domains  
- override governance  
- introduce behavior  
- introduce developmental sequencing  

Entities define *what exists*, not *what it does* or *how it changes*.

---

# 6. Cross‑Module Relationships

STR-ENTITIES interacts with:
- **STR-RELATIONS** — entities are the nodes in relations  
- **STR-CONSTRAINTS** — constraints apply to entities  
- **STR-IDENTIFIERS** — identifiers are assigned to entities  
- **DOC-SCHEMA** — documentation describes entities  
- **INT-VALIDATION** — entities are validated for coherence  

Entities are the foundation of the Structural Plane.

---

# 7. Operational Signature
STR-ENTITIES ensures:
- canonical entity definitions  
- stable structural objects  
- non‑interpretive representations  
- cross‑plane referential stability  
- structural clarity across UMA  

It is the module that defines *what exists* in UMA’s architecture.
