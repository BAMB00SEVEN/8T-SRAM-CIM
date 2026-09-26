# Master Literature Matrix

| ID | Paper | Year | Cell / Macro | Main Theme | Leakage | Stability / Variation | CIM | Technology | Direct Use in Project |
|---|---|---:|---|---|---|---|---|---|---|
| P01 | A novel low-leakage 8T differential SRAM cell | 2011 | 8T | Low leakage | ✓ | ✓ | — | 65 nm bulk CMOS | Baseline leakage/topology motivation |
| P02 | An 8T Low-Voltage and Low-Leakage Half-Selection Disturb-Free SRAM | 2014 | 8T | Low voltage + leakage | ✓ | ✓ | — | 90 nm CMOS / FinFET study | Read/write/half-select methodology |
| P03 | An evaluation of 6T and 8T FinFET SRAM cell leakage currents | 2014 | 6T/8T | Device-level leakage | ✓ | ✓ | — | FinFET | Leakage mechanisms and device effects |
| P04 | An improved energy efficient SRAM cell for access over a wide frequency range | 2016 | 8T variants | Leakage + energy | ✓ | ✓ | — | 45 nm | HVT/topology optimization |
| P05 | Design of Low Leakage SRAM Bitcell | 2019 | 8T | Leakage reduction | ✓ | ✓ | — | 14 nm FinFET | Leakage-oriented 8T comparison |
| P06 | Leakage reduction in DT8T SRAM cell using body biasing technique | 2017 | DT8T | Body bias | ✓ | ✓ | — | 45 nm | Alternative optimization knob |
| P07 | Half-selection disturbance free 8T low leakage SRAM cell | 2022 | 8T | Low leakage + half-select | ✓ | ✓ | — | CMOS | Robustness and write methodology |
| P08 | X-SRAM | 2017 | 6T/8T | In-memory Boolean compute | — | ✓ | ✓ | Predictive models | CIM concept |
| P09 | A survey of SRAM-based in-memory computing techniques and applications | 2021 | 6T/8T/10T+ | SRAM-IMC survey | — | ✓ | ✓ | Multiple | CIM taxonomy and trade-offs |
| P10 | Compute-in-Memory Chips for Deep Learning | 2021 | SRAM/RRAM | CIM survey | — | ✓ | ✓ | Multiple | Edge-AI system context |
| P11 | A Dual-Split 6T SRAM-Based CIM Unit-Macro | 2019 | 6T | Binary DNN CIM | — | ✓ | ✓ | CMOS | Binary MAC reference |
| P12 | A 65-nm 8T SRAM CIM Macro With Column ADCs | 2022 | 8T | Neural MAC | — | ✓ | ✓ | 65 nm | Direct 8T-CIM architecture |
| P13 | A Novel Ultra-Low Power 8T SRAM-Based CIM Design for BNNs | 2021 | 8T | Voltage-mode CIM | ✓ | ✓ | ✓ | CMOS simulation | Directly relevant 8T+CIM+leakage |
| P14 | A 16K Current-Based 8T SRAM CIM Macro | 2020 | 8T | Current-mode CIM | — | ✓ | ✓ | CMOS | Column ADC/current accumulation |
| P15 | Design Methodology and Trends of SRAM-Based CIM Circuits | 2022 | SRAM-CIM | Methodology survey | — | ✓ | ✓ | Multiple | Architecture/trade-off framework |

## Reading clusters

### Cluster A — 8T and leakage
P01–P07

### Cluster B — CIM foundations
P08–P11

### Cluster C — 8T CIM
P12–P14

### Cluster D — methodology
P15

## Important interpretation

No single paper establishes the complete capstone contribution. The literature instead supplies separate pieces:

**8T topology + leakage optimization + isolated read path + CIM computation + edge-AI motivation**

The capstone should explicitly state that the project investigates the integration of these concerns at the bit-cell level.
