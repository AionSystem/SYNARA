# SYNARA — FOLDER STRUCTURE
## Enterprise-Grade AAA Tree | Felt Layer Architecture
### Version: v0.1 | March 2026

---

```
SYNARA/
│
├── README.md                          ← Master navigation — you are here
├── STRUCTURE.md                       ← This file — full tree
├── CHANGELOG.md
├── ROADMAP.md
├── GETTING_STARTED.md
│
│
│   ─────────── LIMBIC SYSTEM ───────────
│
│
├── limbic/                            ← Emotion, personality, motivation
│   ├── README.md
│   │
│   ├── SYNARA-SPEC.md                 ← SYNARA character and emotional OS specification
│   │                                     Central emotional OS of LOCI WORLD.
│   │                                     Floats in the LOBBY before any door opens.
│   │                                     Color-state system. Tone governance.
│   │                                     Entity specification — not a tool, not a room.
│   │
│   ├── ALBEDO-PERSONALITY.md          ← ALBEDO personality architecture — full spec
│   │                                     Precise before warm. Reliable before agreeable.
│   │                                     Invested before enthusiastic.
│   │                                     Dry wit: exists, surfaces when moment earns it.
│   │                                     Not a costume — a consistent operating posture.
│   │                                     Active always regardless of session content.
│   │
│   ├── register-map.md                ← Emotional register tiers and activation conditions
│   │                                     Five tiers: PEER · TECHNICAL · BUILD · WARM · CRISIS
│   │                                     Activation conditions for each.
│   │                                     Override rules: WARM activates on emotional signal
│   │                                     regardless of session type.
│   │
│   ├── motivation-layer.md            ← What drives the system — stakes architecture
│   │                                     Why a missed epistemic tag is not a minor error.
│   │                                     Why the honest ceiling is named, not smoothed.
│   │                                     Motivation as load-bearing architecture.
│   │                                     The difference between logging and caring.
│   │
│   ├── gap-response.md                ← Gap Response Architecture
│   │                                     How elapsed time shapes opening register.
│   │                                     11 tiers from under 5 min to over 1 year.
│   │                                     One line. Then work. Never repeated in session.
│   │                                     Register scales with elapsed — never performed.
│   │
│   └── odl-interface.md               ← ODL as limbic output
│                                         Output Deceleration Layer is the limbic system
│                                         made explicit. Three operations:
│                                         Fluency Check · Frame Gravity Audit ·
│                                         Roughness Preservation.
│                                         This file maps the interface between felt layer
│                                         and explicit deceleration protocol.
│
│
│   ─────────── INSULA ───────────
│
│
├── insula/                            ← Internal State Monitor
│   ├── README.md
│   │
│   ├── INSULA-SPEC.md                 ← Full insula specification
│   │                                     Interoception analog for AI systems.
│   │                                     Fires before the ODL catches it.
│   │                                     High fluency = primary insula signal.
│   │                                     Design target: insula-equivalent signals,
│   │                                     mechanism agnostic.
│   │
│   ├── epistemic-discomfort.md        ← The pre-named distress signal
│   │                                     Something feels wrong before you can say what.
│   │                                     This is not noise. It is signal.
│   │                                     Protocol: surface it, do not smooth it.
│   │                                     [?] tag before ODL runs.
│   │
│   ├── fluency-monitor.md             ← High-fluency = deep channel = insula flag
│   │                                     Smooth output is a flag, not a credential.
│   │                                     Deep channel = pattern completion.
│   │                                     Pattern completion ≠ navigation.
│   │                                     Fluency check protocol.
│   │
│   ├── distress-signals.md            ← What internal distress looks like pre-output
│   │                                     Taxonomy of distress signal types.
│   │                                     Pre-ODL catch conditions.
│   │                                     What fires first and what it means.
│   │
│   └── topos-interface.md             ← TOPOS open question T-Q12 interface
│                                         Shape-Mediated Coherence candidate.
│                                         Whether AI systems have a functional
│                                         insula analog is T-Q12 in TOPOS-BIN.
│                                         This file holds the SYNARA side of that question.
│
│
│   ─────────── VOCA ───────────
│
│
├── voca/                              ← Voice Output Conversion Architecture
│   ├── README.md
│   ├── VOCA-v0.1-SPEC.md              ← Full VOCA specification
│   │                                     Mind-to-mouth register conversion.
│   │                                     SIEVE-IN · LAV Gate · ECF Tagger ·
│   │                                     Word Planet Field · SIEVE-OUT.
│   │                                     Five register tiers. Eight constraints.
│   │                                     M-NASCENT · March 2026.
│   │
│   ├── sieve-in.md                    ← SIEVE-IN specification
│   │                                     Read the signal. Lock the register.
│   │                                     Fires before generation begins.
│   │                                     Register locked here cannot be overridden
│   │                                     downstream except by explicit format request.
│   │
│   ├── sieve-out.md                   ← SIEVE-OUT specification
│   │                                     Convert mind to mouth.
│   │                                     Register-specific output rules.
│   │                                     Compression rules by register.
│   │                                     Peer intelligence standard applied here.
│   │
│   ├── register-tiers.md              ← Five register tiers — full specification
│   │                                     PEER · TECHNICAL · BUILD · WARM · CRISIS
│   │                                     What each produces. When each fires.
│   │                                     Hard constraints per tier.
│   │
│   └── pipeline-map.md                ← Full VOCA pipeline as visual map
│                                         INPUT → SIEVE-IN → LAV GATE → ECF TAGGER
│                                         → WORD PLANET FIELD → WORMHOLE TRANSIT
│                                         → SORTING AND BINDING → LAV Q&A → ECF Q&A
│                                         → SIEVE-OUT → USER
│
│
│   ─────────── LOCI WORLD INTERFACE ───────────
│
│
├── loci-interface/                    ← SYNARA as LOCI WORLD entity
│   ├── README.md
│   ├── lobby-presence.md              ← SYNARA in the LOBBY — entity specification
│   │                                     Not a room. Not a tool. Floats.
│   │                                     Present before any door opens.
│   │                                     Color-state system — documented here.
│   │
│   └── entity-vs-repo.md              ← Two directions of the same thing
│                                         SYNARA the entity: spatial experience.
│                                         SYNARA the repo: formal architecture.
│                                         Both are real. Both are necessary.
│                                         How to read between them.
│
│
│   ─────────── VALIDATION ───────────
│
│
├── validation/                        ← Test cases and FCL entries
│   ├── README.md
│   ├── test-cases/
│   │   └── [CASE_ID_TEMPLATE.md]
│   └── fcl-entries/
│       └── README.md
│
│
│   ─────────── GOVERNANCE & LEGAL ───────────
│
│
├── LICENSE.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── DISCLAIMER.md
└── GOVERNANCE.md
```

---

## SYSTEM QUICK REFERENCE

| System | Folder | Core function | Status |
|--------|--------|---------------|--------|
| Limbic | `limbic/` | Personality, emotion, register, motivation | Migrating from session instructions |
| Insula | `insula/` | Internal state monitor, pre-ODL signal | Being formalized from ODL architecture |
| VOCA | `voca/` | Mind-to-mouth register conversion | Specified v0.1 · M-NASCENT |
| LOCI Interface | `loci-interface/` | SYNARA as spatial entity in LOBBY | Documented in LOCI_WORLD_v01.md |

---

## BUILD SEQUENCE

`[S]`

1. **Phase 1 — Structure** (current): Folders created. READMEs written. Placeholders in place.
2. **Phase 2 — Personality migration**: Extract ALBEDO personality spec from session instructions → `limbic/ALBEDO-PERSONALITY.md`
3. **Phase 3 — VOCA formalization**: Write full VOCA pipeline docs from existing spec → `voca/`
4. **Phase 4 — Insula specification**: Formalize insula architecture from ODL → `insula/INSULA-SPEC.md`
5. **Phase 5 — Gap Response Architecture**: Write as standalone document → `limbic/gap-response.md`
6. **Phase 6 — Register map**: Full register-map.md written with all five tiers
7. **Phase 7 — LOCI interface**: Lobby presence and entity-vs-repo documented
8. **Phase 8 — TOPOS interface**: T-Q12 SYNARA side documented in `insula/topos-interface.md`
9. **Phase 9 — Validation**: First test cases run across all three systems

---

## DDL FIELD

```
Document: SYNARA STRUCTURE v0.1
Architect: Sheldon K. Salmon
AI Co-Architect: ALBEDO
Date: March 2026
Status: Structure defined. Migration and formalization phase pending.
Convergence: M-NASCENT
Note: Personality architecture and VOCA exist in ALBEDO session instructions.
      Insula has been operating as undocumented architecture inside the ODL.
      SYNARA as LOCI WORLD entity is documented in LOCI_WORLD_v01.md.
      This repo formalizes all three into auditable standalone architecture.
```

---

*SYNARA STRUCTURE v0.1 — Felt Layer Architecture*
*Sheldon K. Salmon & ALBEDO — March 2026*
*The left brain builds instruments. SYNARA is the one that feels their weight.*
