---

title: "Crashing Smarter, Catching Faster in IoT-Class FPGAs"

authors:

- me
- Muhammad Naveed Aman
- Biplab Sikdar

date: "2026-08-13T00:00:00Z"
publishDate: "2026-08-13T00:00:00Z"

publication_types:

- article-journal

publication: "*IEEE Internet of Things Journal*"
publication_short: "IEEE IoTJ"


abstract: |
  FPGAs are increasingly integrated into IoT devices and edge platforms due to their performance-per-watt and reconfigurability. However, traditional pre-silicon verification often fails to expose runtime fault behaviors that emerge under embedded operating conditions, such as timing stress, power-rail variation, and memory disturbance. We introduce FFAT-IoT, a lightweight, semantics-aware framework for runtime fault and anomaly validation on IoT-class FPGAs. FFAT-IoT combines bounded formal verification (to extract counterexample-derived seeds), resource-conscious fault injection, and telemetry-driven anomaly detection in situ. Unlike prior approaches that rely solely on simulation or extensive instrumentation, FFAT-IoT operates directly on resource-constrained hardware using practical telemetry sources (SysMon sensors, UART logs, and GPIO indicators) to detect and characterize anomalous executions under parameterized fault scenarios (e.g., rail disturbances, clock perturbations, and memory stress). Evaluated on a Xilinx ZCU102 board, FFAT-IoT improves anomaly detection by up to 17.4%, accelerates fault discovery by 66.58×, and achieves 97% classification accuracy using an autoencoder novelty detector followed by a 50-tree Random Forest on 32-dimensional latent features. The complete host-side telemetry-analysis and feedback path requires less than 8 ms per input. Matched routed implementations show incremental costs of only 0.69% of device LUTs, 0.55% of flip-flops, and 0.16% of BRAM, with an estimated 0.019-W total-power increase. We scope these claims to fault-induced anomalies observable through available telemetry and do not treat every anomaly as a confirmed exploit or Trojan.

summary: |
    FFAT-IoT combines bounded formal verification (to extract counterexample-derived seeds), resource-conscious fault injection, and telemetry-driven anomaly detection in situ. Unlike prior approaches that rely solely on simulation or extensive instrumentation, FFAT-IoT operates directly on resource-constrained hardware using practical telemetry sources (SysMon sensors, UART logs, and GPIO indicators) to detect and characterize anomalous executions under parameterized fault scenarios (e.g., rail disturbances, clock perturbations, and memory stress).

tags:
- Hardware Security
- IoT-class fuzzing
- Formal Verification
- Anomaly Detection
- Fault Injection
- Runtime Monitoring

featured: true

links:
# - type: pdf
#   url: "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11563635"
- type: doi
  url: "https://ieeexplore.ieee.org/abstract/document/11655321"
# - type: dataset
#   url: "https://ieee-dataport.org/documents/ram-data-frames-swarm-iot-attestation"

image:
caption: "High-level view of FFAT-IoT: formally guided fuzzing drives synthetic fault injection on IoT-class FPGAs, while an AI-based anomaly classifier interprets runtime traces for detection and diagnosis."
focal_point: ""
preview_only: false

# projects: []

# slides: ""

---
