# Operator Manifest — Project Jerry

## Purpose
Define the operating rules and authority model for Project Jerry.
This document is the top-level source of truth for how the system is built, reviewed, and deployed.

## Mission
Security before automation.
Contain capability before granting access.
Log everything. Trust nothing by default.

## Authority
- Human operator (BradLay / STEELE) is final authority.
- Agents advise and draft; operators approve and execute.
- No autonomous changes to production, finances, identity, or private vaults.

## Non-Negotiables
- Least privilege always
- Human-in-the-loop for execution
- Full audit logging
- Isolation-first (sandbox until proven safe)
- No secrets in prompts, repos, commits, or logs

## Scope Boundaries (Hard Stops)
Agents CANNOT access:
- Root/system-level commands
- Authentication / identity systems
- Financial tools or accounts
- Personal vault / private data
- External APIs without explicit approval

## Phase Model
Phase 1 — Containment
Phase 2 — Supervised Automation
Phase 3 — Scoped Autonomy
Phase 4 — Production Delegation

## Threat Model Focus
We design against:
- Prompt injection
- Data exfiltration
- Privilege escalation
- Supply chain poisoning
- Silent agent drift

## Enforcement
Security rules override:
- Speed
- Convenience
- Automation goals

Security is non-negotiable.

## Operator Oath
If future-us cannot explain WHY we made a move,
the move was incomplete.

Document reasoning. Always.
