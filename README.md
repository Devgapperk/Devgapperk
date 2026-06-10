<div align="center">

```
╔════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║      ██╗  ██╗ ██████╗ ███████╗███╗   ██╗   ██╗   ██╗██╗                  ║
║      ██║ ██╔╝██╔═══██╗██╔════╝████╗  ██║   ██║   ██║██║                  ║
║      █████╔╝ ██║   ██║█████╗  ██╔██╗ ██║   ██║   ██║██║                  ║
║      ██╔═██╗ ██║   ██║██╔══╝  ██║╚██╗██║   ╚██╗ ██╔╝██║                  ║
║      ██║  ██╗╚██████╔╝███████╗██║ ╚████║    ╚████╔╝ ███████╗             ║
║      ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═══╝     ╚═══╝  ╚══════╝             ║
║                                                                          ║
║          T H E   A I   P L U M B E R   ·   a r c h i t e c t             ║
║                                                                          ║
╚════════════════════════════════════════════════════════════════════════╝
```

**Production-grade agentic AI for regulated enterprise.**  
Fractional CAIO · 20 years from zero to production · Haacht, Belgium

[koen@devgap.uk](mailto:koen@devgap.uk) · [aiplumber.dev](https://aiplumber.dev) · [devgap.uk](https://devgap.uk) · [LinkedIn](https://linkedin.com/in/koenvanlysebetten)

</div>

---

## ` ~ ` What I actually do

I step into zero and build the plumbing, the governance, the kill switches — so the team you hire next can actually scale the fundamentals.

```
                    ┌─────────────────────────────────────────┐
                    │           HUMAN-IN-THE-LOOP             │
                    │     (uncertain calls escalate here)     │
                    └────────────────────┬────────────────────┘
                                         │
   ┌──────────────┐    ┌─────────────────▼─────────────────┐    ┌────────────────┐
   │   INTAKE     │───▶│         AGENTIC LAYER             │───▶│   AUDIT TRAIL  │
   │   + RACI     │    │  LangGraph · RAG · function calls │    │  attributable  │
   │   + risk     │    │  retries · fallbacks · eval gates │    │   every action │
   └──────────────┘    └─────────────────┬─────────────────┘    └────────────────┘
                                         │
                       ┌─────────────────▼─────────────────┐
                       │       KILL SWITCHES               │
                       │  velocity · cost · error · drift  │
                       │   ──▶ auto-suspend & rollback     │
                       └─────────────────┬─────────────────┘
                                         │
                       ┌─────────────────▼─────────────────┐
                       │   OBSERVABILITY  (logs · metrics  │
                       │      traces · drift · SLOs)       │
                       └───────────────────────────────────┘
```

Every action logged and traceable. Uncertain calls go to a human. The whole system shuts itself down if something looks wrong. Codified as **PRIOR FIRE WIN** in *The AI Plumber* (2026).

---

## ` # ` Production cases

| # | Client | Scope | Outcome |
|---|---|---|---|
| 01 | **De Lijn** (BE) | Public transport · 5,000+ FTE · Accenture Song | **129% projected ROI**, ExCom approved, GDPR + EU AI Act baked in |
| 02 | **Najm Insurance** (SA) | Vision AI under SAMA · 40+ cities | **6,000+ daily cases**, OCR + damage detection in production |
| 03 | **US Restaurant Intelligence** | LangGraph 3-agent system | **~90% cost reduction**, replaced 200-person back-office; month → 10 min |
| 04 | **Government of India / NMML** | National heritage AI/AR/VR · 180+ endpoints | **€10M+ delivery**, 99.9% SLA on 5-year O&M contract |

---

## ` $ ` Capabilities

```
┌─ AGENTIC DEVELOPMENT ──────────────┐  ┌─ AIOps / MLOps ───────────────────┐
│  LangGraph multi-agent orchestrat. │  │  Containers (Docker, K8s)         │
│  Function calls · RAG · planning   │  │  Model registry · experiment trk  │
│  Retries · fallbacks · HITL gates  │  │  CI/CD (Azure DevOps, GH Actions) │
│  Eval suites · red teaming         │  │  IaC (Terraform) · rollback       │
│  Azure AI Foundry · Copilot Studio │  │  Notebook → production coaching   │
└────────────────────────────────────┘  └──────────────────────────────────┘

┌─ OBSERVABILITY & RELIABILITY ──────┐  ┌─ COMPLIANCE BY DESIGN ────────────┐
│  Logs · metrics · traces · drift   │  │  EU AI Act risk classification    │
│  Prometheus · Dynatrace · CloudW.  │  │  GDPR Article 9 (health data)     │
│  Kill thresholds (velocity, cost,  │  │  SAMA financial regulation        │
│   error rate, confidence)          │  │  RBAC · secrets · network seg.    │
│  Auto-suspension + rollback        │  │  Privacy-by-design                │
│  Runbooks · incident response      │  │  Audit-ready attribution traces   │
└────────────────────────────────────┘  └──────────────────────────────────┘

```
### Founder of KLEIBER OS

LEIBER ORCHESTRATION OS: ARCHITECTURE

Core Execution Engine Flow in ASCII

===================================================================================
                       KLEIBER RUNTIME RUN-LOOP INITIATION
===================================================================================

       [ User Terminal Command ]
                   │
                   ▼ (e.g., kleiber -loop "Write thread-safe mutex wrapper")
  ┌─────────────────────────────────┐
  │         main.go (CLI)           │ ◄── [ CLI Options: -loop, -build, -max ]
  └────────┬────────────────────────┘
           │
           ▼
  ┌─────────────────────────────────┐
  │    STAGE 1: Pre-Flight Hooks    │
  ├─────────────────────────────────┤
  │ ──► SessionStart.js             │ ──► (Loads API tokens, hydrates workspace)
  │ ──► PreToolUse.js               │ ──► (Pre-flight safety / Blocks rm -rf)
  └────────┬────────────────────────┘
           │
           ▼
  ┌─────────────────────────────────┐
  │ STAGE 2: Second Brain Hydration │ ◄── [ Env: $OBSIDIAN_VAULT_PATH ]
  ├─────────────────────────────────┤
  │  Uses brain.go / ripgrep (rg)   │
  │  Scans Obsidian Vault for:      │ ──► Injects target rules (e.g., Standard: Go-Threading.md)
  │  "Standards/*go*" or "*mutex*"  │     directly into volatile execution context.
  └────────┬────────────────────────┘
           │
           ▼
  ┌─────────────────────────────────┐
  │ STAGE 3: Context Resolve        │
  ├─────────────────────────────────┤
  │  Reads dynamic local files:     │ ──► Extracts Project ID (WPC/Codex), 
  │  ./AGENTS.md & ./CLAUDE.md      │     Priority boundaries, and Active Virtuosos.
  └────────┬────────────────────────┘
           │
           ▼
  ┌──────────────────────────────────────────────────────────────────────────────┐
  │                       STAGE 4: EXECUTION GATEWAY DECISION                    │
  └────────┬─────────────────────────────────────────────────────────────┬────────┘
           │                                                             │
           ▼ (If -loop flag is False)                                    ▼ (If -loop flag is True)
┌─────────────────────────────────────┐                       ┌─────────────────────────────┐
│      Standard Handover Path         │                       │    Smart Loop Engine        │
├─────────────────────────────────────┤                       │         (loop.go)           │
│ 1. Evaluates Prompt Complexity      │                       └──────────────┬──────────────┘
│ 2. Routes Model:                    │                                      │
│    - Haiku 4.5  (Low Latency)       │                                      │
│    - Sonnet 4.6 (Balanced Default)  │                                      │
│    - Opus 4.8   (High Reasoning)    │                                      │
│ 3. Execs: syscall.Exec("claude")    │                                      │
└─────────────────────────────────────┘                                      │
                                                                             ▼
===================================================================================
                       AUTONOMOUS SUPERVISOR LOOP (loop.go)
===================================================================================

                                 [ START ITERATION CYCLE ]
                                             │
                                             ▼
                                ┌─────────────────────────┐
                                │   Evaluate Current Step │
                                └────────────┬────────────┘
                                             │
                      ┌──────────────────────┴──────────────────────┐
                      ▼ (CurrentStep == 1)                          ▼ (CurrentStep > 1)
           ┌───────────────────────┐                     ┌───────────────────────┐
           │   Standard Routing    │                     │   Medic Escalation    │
           ├───────────────────────┤                     ├───────────────────────┤
           │ Routes to:            │                     │ Escales to:           │
           │ Claude Sonnet 4.6     │                     │ Claude Opus 4.8       │
           │ (Effort: High)        │                     │ (Effort: xhigh)       │
           └──────────┬────────────┘                     └──────────┬────────────┘
                      │                                             │
                      └──────────────────────┬──────────────────────┘
                                             │
                                             ▼ (Update Volatile Memory)
                                ┌─────────────────────────┐
                                │ Write .claude/context.md│ ◄── [ Prevents Model Amnesia ]
                                └────────────┬────────────┘
                                             │
                                             ▼
                                ┌─────────────────────────┐
                                │    Run Claude Agent     │ ──► Generates/edits files in project workspace
                                └────────────┬────────────┘
                                             │
                                             ▼
                                ┌─────────────────────────┐
                                │ Run Quality Gate Verification
                                ├─────────────────────────┤
                                │ Runs detected/custom    │ ──► (e.g. "go build ./" or "cargo build")
                                │ compiler assertions     │
                                └────────────┬────────────┘
                                             │
                                  [ Did Build Pass? ]
                                     /             \
                                    /               \
                             NO    /                 \   YES
                                  /                   \
                                 ▼                     ▼
                     ┌───────────────────────┐     ┌───────────────────────┐
                     │   Failure Intercept   │     │   Pass Handover       │
                     ├───────────────────────┤     ├───────────────────────┤
                     │ 1. Log Stack Trace    │     │ 1. Log Success        │
                     │    back to Obsidian   │     │    back to Obsidian   │
                     │ 2. Construct dynamic  │     │ 2. Loop Terminated    │
                     │    Self-Repair Prompt │     │    Successfully       │
                     └──────────┬────────────┘     └───────────────────────┘
                                │
                                ▼
                     [ Check Loop Guard Limit ]
                     - Step < Max Iterations? ──► YES ──► (Recycle & Loop with Medic)
                     - Step >= Max Iterations? ──► NO  ──► [ ABORT LOOP ] (Safety Gate Triggered)

===================================================================================
                       OBSIDIAN SECOND BRAIN INTEGRATION
===================================================================================

    [ Your Obsidian Vault ]
    ├── 📂 Standards/
    │   └── Go-Threading.md  ─────── (Read via ripgrep based on prompt matches)
    │
    ├── 📂 Daily/
    │   └── 2026-06-10.md    ◄────── (Appends execution status: Success / Fail / Abort)
    │
    └── 📂 Ventures/
        └── WPC/
            └── AGENTS.md    ◄────── (Symlinked directly to live project directories)



              ┌──────────────────────────────────────────────┐
              │ kleiber -loop "Write authentication wrappers"│
              └──────────────────────┬───────────────────────┘
                                     ▼
              ┌──────────────────────────────────────────────┐
              │           Kleiber Loop Supervisor            │
              ├──────────────────────────────────────────────┤
              │ [Iteration 1]: Run Claude Sonnet 4.6         │
              │ [Gate Check]: 'npm run build' Fail!          │
              │ [Diagnostics]: Fetch stack trace...          │
              └──────────────────────┬───────────────────────┘
                                     ▼
              ┌──────────────────────────────────────────────┐
              │              Self-Repair Cycle               │
              ├──────────────────────────────────────────────┤
              │ Escalation: Invoke Medic (Opus 4.8 / Fable 5)│
              │ Input: Prompt + Error trace + Vault guidelines│
              │ Action: Medic fixes code directly            │
              └──────────────────────┬───────────────────────┘
                                     ▼
              ┌──────────────────────────────────────────────┐
              │           Clean Build Verification           │
              ├──────────────────────────────────────────────┤
              │ [Gate Check]: 'npm run build' Success!       │
              │ [Log]: Post run reports back to Obsidian     │
              └──────────────────────────────────────────────┘

---

## ` & ` Enterprise stack fluency

`Salesforce (certified)` · `ServiceNow` · `SAP` · `Celonis` · `Genesys` · `Verint` · `Parloa` · `Azure` · `AWS`

---

## ` % ` Recent engagements

**Lead Data & AI Strategy** · Accenture Song for largest Belgium Transport company · *2025*  
Enterprise AI roadmap, four ExCom-approved use cases, compliance-by-design from day one.

**Fractional Head of Growth** · SD Worx (€1B+ payroll platform) & Reica · *2025–present*  
Platform migration, partner ecosystem connecting 75K customers and 5M+ employees.

**Chief AI Officer (Fractional) & Co-Founder** · DevGap · *2016–present*  
30+ FTE across EU / Middle East / India. Embedded CAIO for regulated enterprises — accountable for revenue, cost, risk and adoption.

**Earlier:** Deloitte Digital (Fast50 commerce lead, Richemont B2B migration) · TotalEnergies (Head Data & AI Delivery) · GIMBER (168% MRR growth, 6mo) · Jamalon · Kazidomi · VintoVino First custom .net Wine Marketplace in the US (co-founder, €2M ARR) · Kapaza (Number 3 employee and part of their 2008 €20M Schibsted exit) · MIVB (one of Belgium's first chatbots, before the word existed).

---

## ` * ` Publications

```
  ┌─────────────────────────────────────────────────────────────────┐
  │  📕  THE AI PLUMBER                                       2026  │
  │      Governance-first agentic AI · PRIOR FIRE WIN methodology   │
  ├─────────────────────────────────────────────────────────────────┤
  │  📘  MICRO MULTINATIONALS                                 2012  │
  │      Predicted distributed remote-first work · pre-COVID        │
  │      SaaS Staircase: €50K → €15M                               │
  └─────────────────────────────────────────────────────────────────┘
```

---

<div align="center">

```
> If your AI needs to survive the regulator AND the 3 AM page — let's talk.
```

**[koen@devgap.uk](mailto:koen@devgap.uk)** · **+32 469 41 31 52** · Haacht, Belgium

</div>
