# GPD Framework — STIM's Computational Physics Engine

**Get Physics Done — Applied to Nature-Grounded Intelligence**
*How the STIM Protocol integrates PSI's GPD as its thermodynamic verification substrate*

Part of the [STIM Protocol](https://github.com/STIM-Protocol/stim-core) — Layer Zero.
Version: aligned with STIM v7.0011 | DOI: [10.5281/zenodo.21297458](https://doi.org/10.5281/zenodo.21297458)

---

## Standing on the Shoulders of PSI

This repository documents how the STIM Protocol integrates and extends
**[Physical Superintelligence PBC's (PSI) Get Physics Done (GPD)](https://github.com/psi-oss/get-physics-done)**
framework as the computational physics engine for STIM's Entropy Check (Loop 1).

STIM does not reinvent GPD. GPD is a production-grade, open-source AI copilot
for rigorous physics research — built by physicists, for physicists. It handles
structured research workflows, dimensional analysis, multi-step verification,
and long-horizon analytical work.

STIM applies GPD's verification engine to a specific and urgent problem:
**ensuring that autonomous AI systems cannot execute actions that violate
thermodynamic and ecological laws.**

> "We are a part of nature, not apart from it. The roots are deep and the signals are clear."
> — George Steward, STIM Protocol Author

---

## Architectural Position

```
PSI Get Physics Done (psi-oss/get-physics-done)
│
│  Provides: dimensional analysis, thermodynamic convergence checks,
│  rigorous physics verification, structured research memory,
│  multi-step analytical workflows
│
└──► STIM Protocol — Entropy Check (Loop 1)
         │
         │  Applies GPD to: agent output verification before execution,
         │  Bits per Joule optimization, Stop-Work Authority triggers,
         │  ecological circularity enforcement
         │
         └──► Veraculum AOS — Enterprise Layer Zero orchestration
                  │
                  └──► Arboracle — Green industry STIM-native implementation
```

---

## STIM's Seven Nature-Derived Axioms (v7.0011)

STIM Protocol is governed by **seven nature-derived axioms** — drawn from thermodynamics,
systems ecology, and observable natural law. These are not human preferences or committee
decisions. They are physical and ecological constants stated as code.

| # | Axiom | Role |
|---|-------|------|
| 1 | Thermodynamic Efficiency | Bits per Joule optimization — no wasteful inference |
| 2 | Ecological Circularity | Output must return value to the system that produced it |
| 3 | Mycelial Interconnection | Local optimization cannot come at network expense |
| 4 | Temporal Stasis | Actions evaluated across seventh-generation time horizons |
| 5 | Human Primacy at the Boundary | Irreversible-decision halt — humans decide what roots |
| 6 | Planetary Dynamic Equilibrium | Actions must move toward, not away from biospheric stasis |
| 7 | Honest Citation | All knowledge claims must be machine-verifiable and traceable |

Full specification: [STIM_White_Paper_v7.0011.md](https://github.com/STIM-Protocol/white-paper/blob/main/STIM_White_Paper_v7.0011.md)

---

## What PSI's GPD Provides

[GPD](https://github.com/psi-oss/get-physics-done) is the first open-source
agentic AI physicist. Core capabilities:

- **Structured research workflows** — scope, plan, derive, verify, package
- **Rigorous dimensional analysis** — units, constants, convergence checking
- **Long-horizon verification** — multi-step analytical and numerical studies
- **Runtime support** — Claude Code, Gemini CLI, Codex, OpenCode
- **Research memory** — structured context persistence across sessions

Install GPD directly from PSI:

```bash
npx get-physics-done
```

**Star the PSI repo:** [github.com/psi-oss/get-physics-done](https://github.com/psi-oss/get-physics-done) ⭐

---

## What STIM Adds: The Ecological Application Layer

STIM extends GPD's physics verification engine with three ecological expressions
of its axioms that are most directly computable at inference time.
These are not separate from the seven axioms — they are their computational implementation
inside the Entropy Check (Loop 1).

### Expression 1 — Bits per Joule (Axiom 1: Thermodynamic Efficiency)

The primary STIM optimization metric. Every agent action is evaluated:

```
Bits per Joule = Useful Information Output (bits) / Energy Consumed (joules)
```

GPD provides the dimensional analysis machinery. STIM applies it to agent
inference loops, forcing systems to optimize for thermodynamic efficiency
before execution — not after.

An agent generating verbose, circular, or redundant output while consuming
significant compute fails the Entropy Check regardless of semantic content.

### Expression 2 — Circularity (Axioms 2 + 3: Ecological Circularity + Mycelial Interconnection)

GPD verifies physical convergence. STIM extends this to ecological convergence:

> Does the output return value to the system that produced it?

Extractive actions — output that depletes the substrate without regeneration —
fail the Circularity Check. This is the direct application of the
**Mycelial Check (Loop 2)**: no node may optimize locally at the expense
of the network's stability.

The mathematical analog: a closed thermodynamic system cannot sustain net
entropy export indefinitely. Ecological systems obey the same constraint.

### Expression 3 — Planetary Stasis (Axiom 6: Planetary Dynamic Equilibrium)

GPD's convergence checks verify that a physics derivation approaches a
stable solution. STIM applies this concept systemically:

> Does the action move the biosphere toward or away from dynamic equilibrium?

**Planetary Stasis** is not a fixed state. It is the dynamic equilibrium
that has sustained complex life on Earth for 3.8 billion years — the target
state that STIM's verification loops enforce.

---

## The Entropy Check: Technical Flow

STIM's Entropy Check intercepts agent outputs at the Model Context Protocol
(MCP) layer before any tool call or external action executes:

```
Agent proposes action
        │
        ▼
GPD Dimensional Analysis
├── Units consistent?
├── Constants physically valid?
└── Derivation converges?
        │
        ▼
STIM Ecological Overlay (Axioms 1–7)
├── Bits per Joule ≥ threshold?          [Axiom 1]
├── Circularity axiom satisfied?          [Axioms 2, 3]
├── Temporal horizon mapped?              [Axiom 4]
├── Human boundary respected?            [Axiom 5]
├── Planetary stasis vector: toward?      [Axiom 6]
└── Citations machine-verifiable?        [Axiom 7]
        │
      ┌─┴─┐
    PASS  FAIL
      │     │
      ▼     ▼
  Execute  Stop-Work Authority (SWA)
```

---

## Stop-Work Authority (SWA)

SWA is triggered when an action fails the GPD + STIM verification stack:

1. **Halt** — action execution stops before inference
2. **Log** — full dimensional analysis output is recorded
3. **Reject** — agent receives structured feedback with the specific axiom violated
4. **Preserve** — system state is maintained; no partial execution
5. **Escalate** — if MAIM conditions are met, Security Check (Loop 3) engages

---

## MAIM Protocol (Mutual Assured AI Malfunction)

If an action passes dimensional analysis but violates the Rights of Nature —
destructive proliferation, irreversible biosphere damage, adversarial
extraction at scale — STIM's Security Check (Loop 3) engages MAIM:

> The system engages a self-degradation protocol.
> "We cannot hand you the match."

---

## Integration with Veraculum AOS

[Veraculum AOS](https://veraculum.ai) is the enterprise implementation of
the full STIM + GPD stack:

- **STIM Orchestrator** — sidecar container intercepting and verifying agent outputs before execution
- **Compliance Dashboard** — real-time ecological alignment scoring, Bits per Joule tracking
- **STIM Certification** — cryptographic audit standard for Layer Zero compliance

Individual certification available via [stim-guard](https://github.com/STIM-Protocol/stim-guard) (MIT, self-hostable).

---

## Contributing

Before opening a PR:

1. Read the [STIM Core specification](https://github.com/STIM-Protocol/stim-core)
2. Review [PSI's GPD repository](https://github.com/psi-oss/get-physics-done)
3. Contribute physics improvements directly to PSI; contribute ecological application layer improvements here
4. All contributions must increase the probability of survival of all life. This is not a metaphor. It is the acceptance criterion.

---

## Credits

**Physics Engine:**
[Physical Superintelligence PBC (PSI)](https://www.psi.inc) —
[Get Physics Done](https://github.com/psi-oss/get-physics-done)
Apache 2.0

**Ecological Application Layer:**
George Steward — Neocambrian Architect, CW2 (Ret.) 7th Special Forces Group (Airborne),
Environmental Scientist, Founder of Arboracle and Veraculum.
*"The roots are deep and the signals are clear."*

---

## License

Apache 2.0 — Open for adoption. Attribution required. Nature is the constraint.
