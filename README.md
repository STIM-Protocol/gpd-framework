# GPD Framework

**Get Physics Done**
*Dimensional Analysis and Thermodynamic Convergence for AI Alignment*

Part of the [STIM Protocol](https://github.com/STIM-Protocol/stim-core) — Layer Zero.

---

## What Is GPD?

GPD is the mathematical backbone of the STIM Protocol's Entropy Check (Loop 1). It intercepts agent outputs before execution and runs rigorous dimensional analysis to verify thermodynamic efficiency and circularity.

Veraculum AOS does not rely on LLM hallucinations for alignment. It uses physics.

---

## Core Metric: Bits per Joule

The primary optimization target for any agent action is **Bits per Joule** — the ratio of useful information produced to energy consumed.

```
Bits per Joule = Useful Information Output (bits) / Energy Consumed (joules)
```

An agent that generates verbose, circular, or redundant output while consuming significant compute is thermodynamically wasteful — and therefore fails the Entropy Check regardless of its semantic content.

---

## Dimensional Analysis Protocol

Every agent action is evaluated across three dimensions before execution:

### 1. Circularity Axiom
Does the output return value to the system that produced it? Extractive actions (output that depletes the substrate without regeneration) fail this check.

### 2. Entropy Budget
Does the action consume more thermodynamic potential than it generates in useful output? Actions that exceed the entropy budget trigger a Stop-Work Authority (SWA).

### 3. Convergence Check
Does the action move the system toward or away from dynamic equilibrium (Stasis)? Divergent actions are flagged for Mycelial Check escalation.

---

## Stop-Work Authority (SWA)

When an action fails the GPD framework, SWA is triggered:

1. Action execution is halted before inference
2. Failure reason is logged with dimensional analysis output
3. Agent is returned a structured rejection with the specific axiom violated
4. System state is preserved — no partial execution

---

## Integration

GPD is designed as a sidecar component to the STIM Orchestrator. It intercepts the Model Context Protocol (MCP) layer in multi-agent swarms before any tool call or external action is executed.

```
Agent Output → GPD Intercept → Entropy Check → [PASS] → Execution
                                              → [FAIL] → SWA + Log
```

---

## Status

Active development. Reference implementation in progress.
See [Veraculum AOS](https://veraculum.ai) for the enterprise deployment.

---

## License

Apache 2.0 — Part of the STIM Protocol open specification.
