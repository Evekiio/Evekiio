<picture>
  <source media="(max-width: 600px)" srcset="assets/portfolio-banner-mobile.svg">
  <img src="assets/portfolio-banner.svg" alt="Evekiio - AI Solutions Engineer. Practical software, thoughtful systems." width="1120">
</picture>

**AI Solutions Engineer** � Consultant � Builder

I build document workflows, automation tools and real-time game systems. As a consultant, I start with the work people need to get done, then design software they can understand and maintain.

[Selected work](#selected-work) � [How I build](#how-i-build) � [Technical toolkit](#technical-toolkit)

## Selected work

### 01 / Rail Arena

**Game systems � Public source � Windows pre-alpha**  
C# � Unity 6.6 / URP � Blender � NUnit

A railgun-only sci-fi arena shooter built around aim, momentum and positioning. Current source includes solo and target practice, offline bot matches and two-player direct-IP duels.

- **Simulation and networking:** a host-authoritative model with client prediction, reconciliation and bounded hit rewind.
- **Player experience:** saved aim, reticle, comfort and audio settings, appearance selection, combat feedback and arena traversal cues.
- **Evidence:** project documentation records build-specific tests and their limits. AI assists development and concept exploration; the in-game bots use gameplay logic.

[Explore source](https://github.com/Evekiio/rail-arena) � [Download pre-alpha](https://github.com/Evekiio/rail-arena/releases/tag/v0.1.0-pre-alpha.1) � [Design](https://github.com/Evekiio/rail-arena/blob/main/docs/DESIGN.md) � [Validation](https://github.com/Evekiio/rail-arena/blob/main/docs/VALIDATION.md)

> **Development boundary:** The downloadable Windows checkpoint predates current source. Physical-input and audio review, real-internet duel acceptance and measured rendering performance remain open. Foundry v2, portals and revised match rules are planned, not integrated.

<details>
<summary><strong>Visual development</strong></summary>

Character and Foundry concept studies are AI-generated design references, not gameplay captures. Character artwork represents an approved appearance direction; Foundry v2 remains a proposed arena and review candidate.

[Character concept and provenance](https://github.com/Evekiio/rail-arena/blob/f805fbd32129999955c31fa659e5ea0092102ba5/docs/STYLIZED-CONTENDERS.md) � [Foundry sources and review limits](https://github.com/Evekiio/rail-arena/blob/f805fbd32129999955c31fa659e5ea0092102ba5/ArtSource/Original/Foundry-Arena-v2/References-v1/README.md)

</details>

---

### 02 / Windows System Audit

**Systems tooling � Public source � Local utility**  
PowerShell � Windows � JSON

A local PC inspection tool that turns hardware and Windows information into readable text and structured JSON for inventory, troubleshooting and workload planning. Collection gaps are shown explicitly; disk benchmarking is opt-in. Reports include hardware inventory and Windows versions and should be reviewed before sharing.

[Explore source](https://github.com/Evekiio/windows-system-audit) � [Run guide](https://github.com/Evekiio/windows-system-audit#quick-start) � [Privacy & limitations](https://github.com/Evekiio/windows-system-audit#privacy-and-security)

---

### 03 / Morrow

**Architecture � High-level overview**

Morrow is a modular, self-hosted business ecosystem intended to bring websites, customers, appointments and checkout together around a shared foundation.

## How I build

1. **Understand the problem:** start with the people, workflow and outcome that matter.
2. **Design the boundaries:** make ownership, inputs, failure paths and security considerations clear.
3. **Make the work inspectable:** validate the behavior, record its limits and distinguish implemented work from plans.

## Technical toolkit

- **Systems & automation:** Go, Python, PowerShell, REST APIs and JSON.
- **AI & documents:** AI-assisted development, document processing, RAG, Ollama and local AI integrations.
- **Games & real-time:** C#, Unity 6.6, URP, Blender and NUnit.
- **Web:** HTML, CSS, JavaScript, React, PHP, WordPress and MySQL.

[Browse public repositories](https://github.com/Evekiio?tab=repositories)
