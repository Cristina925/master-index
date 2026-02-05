# AI-Mediated Security Action — Recognition Kernel

## Status
Recognition-level reference  
Non-normative  
Not guidance, not controls, not advice

---

## Purpose

This page describes a recurring governance exposure that arises when **security actions are executed or triggered by AI-mediated systems**.

It does not prescribe how systems should be built, operated, or controlled.  
It exists solely to make a specific failure pattern **recognisable at the moment it occurs**, rather than reconstructed later under scrutiny.

---

## The Problem This Kernel Isolates

AI systems are increasingly permitted to **execute or trigger security actions** (e.g. access restriction, account blocking, containment, enforcement).

At the same time, governance models often continue to treat AI as **decision-support**, not as an **acting intermediary**.

This creates a structural gap at the moment of action:

- who is recognised as acting,  
- what authority exists *at that moment*, and  
- whether the action can later be reconstructed evidentially.

When this gap exists, organisations are forced to **reconstruct legitimacy after the fact**, using incomplete records, inference, or narrative.

This exposure is independent of:
- model quality,  
- intent,  
- correctness of outcome, or  
- technical performance.

---

## The AMSA Kernel (Three Recognition Invariants)

The AMSA Kernel consists of three invariants that must be **recognisable** at the moment an AI-mediated security action occurs.

These are **recognition requirements**, not implementation requirements.

---

### 1. Agency Recognition

At the moment a security action is executed, it must be possible to state:

**Who is recognised as the acting authority**, even if execution is automated.

Key distinction:
- execution ≠ agency  
- automation ≠ authority

Failure pattern:
- the system acted, but agency must be inferred later.

---

### 2. Authority Validity at Time-of-Action

At the moment the action occurs, it must be possible to recognise:

**That authority to act was valid under current conditions**, not merely inherited from prior delegation or configuration.

Key distinction:
- historical permission ≠ current legitimacy  
- delegated authority does not persist by default

Failure pattern:
- systems act under stale or assumed authority.

---

### 3. Traceability Minimum

At the moment the action occurs, it must be possible for the organisation to later reconstruct:

**Why the action occurred, under which authority, using first-party records rather than inference or narrative.**

This does not require full explainability or full signal retention.  
It requires only that legitimacy is **not reconstructed after the fact**.

Failure pattern:
- logs exist, but they do not support legitimacy assessment.

---

## What This Kernel Does *Not* Do

To preserve neutrality and portability, this kernel explicitly does **not**:

- define AI safety requirements  
- define human-in-the-loop thresholds  
- prescribe logging architectures  
- specify security controls  
- assign responsibility or blame  
- assert compliance with any law or standard  

It recognises **where legitimacy collapses**, not how to engineer systems.

---

## Why This Appears Across Regulatory Regimes

Although expressed differently, the same expectations now appear across major regimes:

- record-keeping and traceability requirements,  
- governance and accountability expectations,  
- human oversight duties,  
- separation of decision and enforcement functions.

This kernel makes the **shared assumption** behind those requirements explicit, without restating or operationalising them.

---

## Positioning

This artefact:
- sits upstream of outcome assessment,  
- is usable under investigation or audit,  
- does not conflict with existing standards, and  
- does not require adoption to be referenced.

It may be cited as a **recognition reference** when analysing AI-mediated security actions.

---

## Boundary Statement

**This page recognises legitimacy exposure arising from AI-mediated security action.  
It does not prescribe how to eliminate that exposure.**

---

## Version

- AMSA Kernel v1.0  
- Recognition-complete  
- Clarification-only changes if reactivated
