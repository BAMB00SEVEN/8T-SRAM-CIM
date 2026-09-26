# 08 — RESEARCH

This folder is the literature and research-intelligence layer of the capstone:

**Design and Analysis of a Leakage-Optimized 8T SRAM Bit-Cell with Compute-in-Memory Extension for Low-Power Edge AI Inference**

The literature set is deliberately split across four connected questions:

1. **Why 8T SRAM?** — read/write decoupling, stability, low-voltage operation.
2. **Why leakage optimization?** — standby power, subthreshold leakage, threshold/body-bias and power-gating techniques.
3. **Why CIM?** — reducing memory movement and enabling parallel MAC/logic operations inside SRAM.
4. **Why an 8T + CIM combination?** — decoupled read paths can improve CIM robustness, but area, leakage, sensing, ADC/DAC and variation remain trade-offs.

## Folder map

```text
08_RESEARCH/
├── README.md
├── papers/                  # citation records; original PDFs intentionally omitted
├── paper-notes/             # one research note per selected paper
├── literature-matrix/       # cross-paper comparison
├── synthesis/               # literature-review narrative and research gap
└── references/              # BibTeX and citation list
```

## Important scope rule

The repository stores **research notes and bibliographic metadata, not copyrighted paper PDFs**. Numerical results are included only as concise, attributed literature facts and should not be treated as results of our own design.

## How this connects to the capstone

```text
Literature
    ↓
6T reference problem
    ↓
8T architecture
    ↓
leakage-control mechanism
    ↓
Cadence implementation
    ↓
SRAM verification
    ↓
CIM extension
    ↓
edge-AI-oriented evaluation
```

## Suggested reading order

Start with:
- `02_low-voltage-low-leakage-8t`
- `04_energy-efficient-8t-wide-frequency`
- `05_low-leakage-sram-bitcell`
- `09_sram-imc-survey`
- `12_8t-cim-65nm`
- `13_8t-cim-bnn`

Then use the remaining papers to support specific design choices.

## Literature-review rule

Do not write:

> "Paper X proves our proposed cell is better."

Write:

> "Paper X demonstrates that [documented technique] can reduce [metric] under [documented conditions]. This motivates investigating a related mechanism in our proposed cell."

This keeps published evidence separate from our own simulation results.
