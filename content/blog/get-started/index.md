---

title: "What I'm Working On Right Now"
summary: "Preparing for my PhD oral defence, beginning my postdoctoral research on RF and cognitive-device security, and advancing new work on FPGA and IoT security."
date: 2026-06-21

# Featured image

image:
  caption: "NUS College of Design and Engineering – where many of these ideas were born and continue to evolve."

cover:
  image: "https://images.unsplash.com/photo-1557682250-33bd709cbe85?q=80&w=2560"
  position:
    x: 50
    y: 40
  overlay:
    enabled: true
    type: "gradient"
    opacity: 0.4
    gradient: "bottom"
  fade:
    enabled: true
    height: "80px"
  icon:
    name: "🧠"

authors:
  - "me"

tags:
  - Research
  - PhD Life
  - Postdoctoral Research
  - Hardware Security
  - Wireless Security
  - Updates

content_meta:
  trending: false
---

This is a snapshot of what my research life looks like right now: my PhD thesis has been submitted, I am preparing for my oral defence, and I have started a new chapter as a postdoctoral researcher at NUS.

I am now working with Prof. Massimo Alioto’s group on the security of **RF, wireless, and cognitive devices**, while continuing to develop research on **FPGA security, hardware faults, runtime validation, and IoT swarm attestation**.

{{< toc mobile_only=true is_open=true >}}

## 1. Preparing for My PhD Oral Defence

After several years of experiments, writing, revisions, and a great deal of LaTeX, I have now **submitted my PhD thesis**.

The thesis brings together my work on:

* **FPGA and hardware security**
* **hardware fuzzing and runtime anomaly detection**
* **software-triggerable FPGA fault effects**
* **IoT swarm attestation**
* **machine-learning-based security mechanisms**

Submitting the thesis was a major milestone, but the PhD journey is not quite over yet. I am currently waiting for my **oral defence** and revisiting the central arguments, technical contributions, and broader implications of the work.

This stage feels different from writing the thesis itself. Instead of trying to fit several years of research into one coherent document, I am now thinking about how to explain and defend the most important ideas clearly:

* What problems does the thesis solve?
* Why do these problems matter in practical systems?
* What assumptions and limitations should be made explicit?
* What new research directions emerge from the results?

It is a useful opportunity to step back from the details and see the work as a complete research story.

## 2. Starting My Postdoctoral Research at NUS

I have also started working as a **postdoctoral researcher at the National University of Singapore**, in Prof. Massimo Alioto’s group.

My current research is expanding into the security of:

* **radio-frequency systems**
* **wireless devices and communication**
* **cognitive and adaptive devices**
* **resource-constrained and edge-connected systems**
* **hardware-software interactions in emerging devices**

This direction builds naturally on my previous work in FPGA, embedded-system, and IoT security, while introducing new challenges associated with wireless communication and cognitively adaptive systems.

These systems increasingly sense their environments, change their operating behaviour, and make decisions based on observed signals. That adaptability creates exciting opportunities, but it also introduces new attack surfaces and security questions.

<!-- Some of the broader questions I am interested in include:

* How can we detect malicious or abnormal behaviour in adaptive RF and wireless devices?
* How can security mechanisms operate under strict power, latency, and hardware constraints?
* What happens when an attacker manipulates the physical, communication, or computational behaviour of a device?
* How can hardware-level observability support trustworthy runtime validation?
* How should security mechanisms adapt when the underlying device or environment is itself dynamic? -->

I am still exploring this space, but I am excited about connecting my background in hardware and IoT security with RF, wireless, and cognitive-device research.

## 3. Recently Published Work

Two projects that occupied a large part of my PhD have now been accapted and published.

### ENVOT

**ENVOT**, our framework for the secure attestation of IoT swarms using ensemble learning, has been published in the **IEEE Open Journal of the Computer Society**.

The work investigates how ensemble-learning techniques can support the identification of compromised devices in an IoT swarm while accounting for practical considerations such as:

* attestation latency
* energy consumption
* detection robustness
* device heterogeneity
* scalability across larger swarms

Seeing ENVOT progress from an initial research idea, through experiments and revisions, to a published paper has been especially rewarding.

### Crashing Smarter, Catching Faster in IoT-Class FPGAs

Our work on **crashing smarter and catching faster in IoT-class FPGAs** has been accepted for publication in the **IEEE Internet of Things Journal**.

This research examines attacks and defensive monitoring mechanisms for resource-constrained FPGA-based IoT systems. It explores how carefully designed test inputs can expose security-relevant behaviour and how lightweight runtime mechanisms can detect the resulting anomalies.

The work connects several themes that have shaped my PhD:

* FPGA security
* dynamic analysis
* anomaly detection
* hardware fuzzing
* practical protection for constrained IoT platforms

The publication is an important milestone, but it has also raised several new questions about how runtime security mechanisms can be made more explainable, scalable, and robust.

## 4. Papers Currently Under Review

Alongside the published work, I am continuing to develop and submit research on FPGA fault validation and IoT swarm attestation.

### You Can’t Hide the Fault

***You Can’t Hide the Fault: Formal-Guided Runtime Validation of Software-Triggerable FPGA Fault Effects*** is currently under review at **NDSS**.

This work studies software-triggerable fault effects in FPGA-based systems and explores how formal guidance can be combined with runtime validation to identify security-relevant behaviour.

The central idea is to bridge the gap between formal reasoning and practical runtime observation. Formal analysis can identify potentially dangerous behaviours, while runtime validation can determine whether and how those behaviours manifest in a deployed system.

The work examines questions such as:

* Which FPGA fault effects can be triggered through software-accessible interfaces?
* How can formal methods guide the search for security-relevant runtime behaviours?
* What evidence is required to validate that a suspected fault effect is practically exploitable?
* How can these behaviours be detected without introducing excessive runtime overhead?

### RAM-Guard

***RAM-Guard: Lightweight Anomaly-Based Attestation for IoT Swarms*** is currently under review at the **2026 IEEE Global Communications Conference**, in the **IoT and Sensor Networks** track.

RAM-Guard explores lightweight anomaly-based attestation for resource-constrained devices operating as part of an IoT swarm.

The work focuses on balancing security with the operational limitations of embedded and IoT devices, including:

* limited memory and computational capacity
* communication overhead
* energy constraints
* changing device and network behaviour
* the need to identify compromised devices efficiently

This project continues my interest in swarm-level security, particularly the challenge of designing attestation mechanisms that are practical enough for real deployments while remaining robust against evolving attacks.

## 5. Continuing the FPGA Security Research

Although my postdoctoral work is expanding into RF, wireless, and cognitive-device security, I am continuing to work on open problems in FPGA security.

I remain particularly interested in:

* semantics-guided FPGA fuzzing
* software-triggerable hardware faults
* formal and dynamic analysis
* runtime anomaly detection
* hardware-assisted attestation
* security validation for resource-constrained platforms

One recurring question across these projects is how to move from simply observing unexpected behaviour to understanding whether that behaviour has meaningful security consequences.

Finding a crash or anomaly is useful, but it is often only the beginning. The harder questions are:

* What caused it?
* Can an attacker trigger it reliably?
* Does it affect confidentiality, integrity, or availability?
* Can the effect cross hardware-software boundaries?
* How can it be detected or mitigated efficiently at runtime?

These questions continue to shape both my current work and the research directions I want to pursue next.

## 6. Outside the Research: Reading and Thinking

When I am not preparing for the oral defence, running experiments, or revising papers, I am usually reading about:

* the **neuroscience of decision-making and communication**
* how humans coordinate and develop shared understanding
* how people reason about uncertainty and risk
* how adaptive systems make decisions from incomplete information
* how complex technical risks can be communicated more clearly

These interests may seem separate from hardware and wireless security, but I increasingly see connections between them.

Both secure systems and human decision-making involve limited information, uncertain environments, competing objectives, and the need to distinguish trustworthy signals from misleading ones.

Exploring these connections keeps me curious and encourages me to think about security beyond individual attacks and defences—as a broader problem of observation, adaptation, communication, and trust.

---

This stage feels like both an ending and a beginning.

My PhD thesis has been submitted, but the oral defence still lies ahead. Two major pieces of work have now been published, while new papers are under review. At the same time, my postdoctoral research is taking me into RF, wireless, and cognitive-device security.

I am looking forward to seeing how these research directions come together—and where they lead next.

If you are working on related problems in hardware, FPGA, IoT, RF, wireless, or cognitive-device security, feel free to reach out.
