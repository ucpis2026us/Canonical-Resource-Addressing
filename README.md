# Canonical Resource Addressing (CRA)

**Status:** Early public draft  
**Purpose:** Foundational identity & namespace discipline for cyber-physical environments.

---

## What is CRA?

Canonical Resource Addressing (CRA) defines how participants in a cyber-physical system
refer to the same thing without ambiguity.

CRA provides durable, portable, and machine-resolvable identifiers for facilities,
equipment, software, people, processes, and events.

If two systems share a CRA identifier, they are talking about the same resource.

---

## Why this exists

Modern industrial and autonomous environments suffer from constant friction caused by:

- incompatible naming schemes  
- vendor-specific identifiers  
- brittle integration mappings  
- lifecycle breaks when assets move or are renamed  

CRA introduces a stable reference layer so higher systems can interoperate reliably.

Identity first.  
Everything else builds on that.

---

## Core Concept: Resource Identifier (RID)

A **Resource Identifier (RID)** is the canonical string defined by CRA
that uniquely names a resource within an authority domain.

Example:

ucpis://us.mn.delano.a1/robot/r7


RIDs are intended to be:

- human readable  
- machine parseable  
- stable across time  
- resolvable to metadata  

---

## What CRA Standardizes (in progress)

The CRA workstream is actively developing specifications for:

- identifier grammar  
- namespace authority & delegation  
- canonicalization rules  
- lifecycle & non-reuse  
- alias mapping  
- minimum resolution behavior  

These documents are under active construction.

---

## What CRA Does NOT Attempt

CRA does not define:

- transport protocols  
- authentication or authorization  
- data schemas  
- UI or visualization  
- safety policy  
- embodiment rules  

Other specifications — including those in the UCPIS constellation —
consume CRA identifiers.

---

## Relationship to UCPIS

CRA is foundational infrastructure for the Universal Cyber-Physical Interoperability Stack (UCPIS).

UCPIS depends on stable identity.  
CRA provides that identity.

CRA is designed to remain implementation-neutral and independently adoptable.

---

## Maturity

This repository represents the beginning of a long-term effort.

Expect:

- rapid iteration  
- vocabulary refinement  
- grammar formalization  
- compatibility profiles  
- reference tooling  

Contributions, critique, and implementation experiments are welcome.

---

## Near-Term Goals

- Publish CRA v0.1 grammar
- Provide normalization rules
- Define resolver expectations
- Establish example namespaces
- Release reference libraries

---

## Guiding Principle

Identifiers must survive:

- software change  
- vendor change  
- organizational change  
- physical relocation  
- time

If identity breaks, interoperability breaks.

---

## Contact & Attribution

Part of the UCPIS ecosystem.

Inventor: Michael James Malecek (2026)  
Delano, Minnesota, United States

---

**CRA begins with naming.  
Agreement follows.**
