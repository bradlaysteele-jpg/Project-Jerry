# Security Baseline — Project Jerry

## Mission
Security before automation.  
Contain agents before granting capability.  
Log everything. Trust nothing by default.

---

## Core Principles

### 1. Least Privilege Always
No system, identity, or financial access unless explicitly granted.

### 2. Human In The Loop
All agent outputs reviewed before execution in early phases.

### 3. Full Audit Logging
Every action must be traceable.

### 4. Isolation First
Agents operate in sandbox until proven safe.

---

## Access Restrictions (Default Deny)

Agents CANNOT access:
- Root / system level commands
- Authentication systems
- Financial tools or accounts
- Personal vault / private data
- External APIs without approval

---

## Phase Model

Phase 1 — Containment  
Phase 2 — Supervised Automation  
Phase 3 — Scoped Autonomy  
Phase 4 — Production Delegation

---

## Threat Model Focus

We design against:
- Prompt Injection
- Data Exfiltration
- Privilege Escalation
- Supply Chain Poisoning
- Silent Agent Drift

---

## Enforcement

Security rules override:
- Speed
- Convenience
- Automation goals

Security is non-negotiable.
