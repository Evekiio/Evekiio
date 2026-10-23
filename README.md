![Sanders Riddle — software engineering, applied AI, and game design and development. Original abstract artwork connects modular systems with an arena sightline.](assets/profile-banner.svg)

# Sanders Riddle

**Software engineering · Applied AI · Game design & development**

I build practical software and interactive experiences around how people work and play. My work connects backend systems, workflow automation and AI-assisted engineering with game design and real-time gameplay development—from defining the rules to integrating and validating what runs.

**Security is non-negotiable.** I consider access boundaries, input validation, sensitive-data handling and privacy from the start. Clear ownership, reviewable changes and honest acceptance criteria matter in both business software and games.

[Game development](#game-design--development) · [Software & AI](#software--ai-work) · [Approach](#engineering-approach) · [Technologies](#technologies) · [Background](#background) · [Connect](#connect)

## Game design & development

### Rail Arena

**Public source · Windows pre-alpha · Unity 6.6 / URP · C#**

A precision-focused sci-fi arena shooter built to make aim practice feel like play. One railgun, momentum-driven movement and a compact battlefield put timing, positioning and readable feedback at the center of the experience.

- **Gameplay systems:** solo practice, configurable bots, combat, jump pads, health pickups, scoring and match/rematch flow. Shared movement and combat rules support offline play and online duels.
- **Multiplayer foundations:** two-human direct-IP duels with host-owned movement and damage. Client prediction and reconciliation keep local movement responsive while correcting it to the host's state; bounded hit rewind checks shots against recent target positions.
- **Design and asset integration:** arena layouts, weapon handling, first-person presentation, editable Blender sources and Unity authoring tools. Concept references, third-party asset provenance and installed game content are documented separately.
- **Inspectable engineering:** C# simulation and networking tests, malformed-input checks, lifecycle tests and build-specific validation records. AI-assisted workflows support implementation and asset development; the in-game bots use gameplay logic, not language models.

**Current stage:** a playable, unfinished Windows pre-alpha is available. Automated evidence covers defined local scenarios; final human input/audio review, real-internet duel acceptance and measured rendering performance remain open. The newer arena, portal and gameplay-rule designs include pending work and should not be read as features already in the released client.

[Explore Rail Arena](https://github.com/Evekiio/rail-arena) · [Windows pre-alpha](https://github.com/Evekiio/rail-arena/releases/tag/v0.1.0-pre-alpha.1) · [Design direction](https://github.com/Evekiio/rail-arena/blob/main/docs/DESIGN.md) · [Implementation & validation](https://github.com/Evekiio/rail-arena/blob/main/docs/VALIDATION.md)

## Software & AI work

### Windows System Audit

**Public source · Implemented local utility · PowerShell**

A local Windows reporting tool for comparing PCs and planning development or local-AI workloads. It turns hardware, operating-system, GPU, storage and network information into readable text and structured JSON reports. Reports can contain identifying machine details, so review them before sharing. This is a planning utility, not a security assessment or an actual language-model benchmark.

[Repository](https://github.com/Evekiio/windows-system-audit) · [Script](https://github.com/Evekiio/windows-system-audit/blob/main/full_system_audit.ps1) · [Run guide](https://github.com/Evekiio/windows-system-audit#how-to-run)

### Standing Orders

**AI-agent role manuals · Reusable guidance**

A library of detailed role manuals for AI agents, with versioned PDF/source editions, team-composition guidance and a catalog. The focus is clearer responsibilities, stronger engineering standards and coordinated work, with security and human verification central to the process.

### Morrow

**Planned business ecosystem · Documentation first**

A modular, self-hosted software ecosystem for small businesses, covering a shared foundation, business websites, customers, appointments and checkout, with focused uses such as farmstead shops and print-on-demand stores. Go with HTML, CSS and JavaScript is the planned foundation. These are architecture and product plans, not implemented application releases.

Standing Orders and Morrow are summarized at the concept level; public source links are provided for publicly available work.

## Engineering approach

1. **Start with purpose and interaction.** Define the workflow or player decisions, the constraints and the feedback people need. Turn the intended experience into explicit rules and a manageable scope.
2. **Keep authority and boundaries clear.** Decide which system owns each result, validate untrusted inputs and limit data access. Prefer readable code, explicit interfaces and documented asset provenance.
3. **Make progress reviewable.** Use focused changes, automated checks and recorded evidence. Keep implemented behavior, approved designs and unverified assumptions distinct. Human judgment about usability, game feel and creative quality remains essential.

## Technologies

| Area | Tools and experience |
| --- | --- |
| **Game development** | C#, Unity 6.6, URP, Blender and NUnit |
| **Backend and automation** | Go, Python, PowerShell, REST APIs and JSON workflows |
| **Web applications** | HTML, CSS, JavaScript, React, PHP, WordPress and MySQL |
| **AI and documents** | AI-assisted development, document processing, retrieval-augmented generation (RAG), Ollama and local AI integrations |
| **Enterprise background** | SAP Fiori, UI5, ABAP and OData services |

## Background

**United States Air Force · December 2007–April 2021 · Approximately 13 years, 4 months**

Before moving into software, I maintained F-15 aircraft and led maintenance teams. That experience shaped how I troubleshoot, document technical work and follow careful procedures under real operating constraints.

I hold an **MBA in Information Systems Management**, which supports how I connect technical decisions with business requirements and organizational needs.

## Connect

For software engineering, game systems or AI-assisted development, connect on [LinkedIn](https://www.linkedin.com/in/sandersriddle/) or explore my [public repositories](https://github.com/Evekiio?tab=repositories&type=public).
