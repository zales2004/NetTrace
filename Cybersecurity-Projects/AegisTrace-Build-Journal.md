# AegisTrace — Build Journal

> **Tagline:** Detect the threat. Trace the evidence. Verify the response.

## Project goal

Build a small, demonstrable SOC investigation tool that ingests security events, detects suspicious sequences, builds evidence-linked timelines, separates observed facts from inferred explanations, maps supported behavior to MITRE ATT&CK, and recommends defensive next steps.

## Status

**Planning / implementation journal.** Features below are goals until there is a working implementation and a reproducible test.

## Intended milestones

### Milestone 1 — Define the event schema
- [ ] Define a normalized event structure: timestamp, host, username, source IP, event type, outcome, raw evidence reference.
- [ ] Add sanitized sample events and document their origin.
- [ ] Validate required fields and timestamp parsing.

### Milestone 2 — Implement baseline detections
- [ ] Detect repeated SSH authentication failures using a configurable threshold.
- [ ] Detect a successful login following repeated failures.
- [ ] Include the matching event IDs and time window in every finding.
- [ ] Test both positive and negative examples.

### Milestone 3 — Build an evidence-linked timeline
- [ ] Correlate events by host, account, source address, and time.
- [ ] Keep observed events separate from inferred attack steps.
- [ ] Link every timeline statement to one or more evidence records.
- [ ] Show missing telemetry and alternative explanations.

### Milestone 4 — Add explanation and ATT&CK mapping
- [ ] Map only behavior supported by observed evidence.
- [ ] Treat AI-written explanations as hypotheses, not raw evidence.
- [ ] Validate generated claims against the event set.
- [ ] Record confidence rationale and uncertainty.

### Milestone 5 — Recommend and validate responses
- [ ] Recommend prioritized, proportionate defensive actions.
- [ ] Make disruptive actions require explicit approval.
- [ ] If automated blocking is implemented, restrict it to an isolated lab, use a verified expiry, and test rollback.
- [ ] Record expected outcome and validation evidence.

## Session log

### Session template

- **Date:**
- **Objective:**
- **Changes made:**
- **Commands / tests run:**
- **Evidence produced:**
- **Result:**
- **What failed or remains uncertain:**
- **Next step:**

## Safety and evidence rules

- Use only owned systems, isolated lab VMs, or explicitly authorized targets.
- Do not commit passwords, API keys, personal network captures, or unredacted sensitive logs.
- Never present simulated data as real-world incident evidence.
- Do not label an event malicious without supporting context.
- Keep AI-generated hypotheses distinguishable from observed facts.
