# iBeer 2026 -- Sovereign Beverage Simulation Platform

[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()
[![Lines](https://img.shields.io/badge/lines-approximately%201300-blue)]()
[![Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)]()
[![AI](https://img.shields.io/badge/AI%20generation-prohibited-red)]()
[![Network](https://img.shields.io/badge/network%20interfaces-0-important)]()
[![License](https://img.shields.io/badge/license-ICE--WARE--v1-blue)]()
[![RFC](https://img.shields.io/badge/RFC%201149-avian%20transport-yellow)]()
[![RFC](https://img.shields.io/badge/RFC%202324-coffee%20pot%20control-yellow)]()
[![Vim](https://img.shields.io/badge/editor-Vim%205.3-1994E4)]()
[![GNU](https://img.shields.io/badge/GNU-Not%20Unix-critical)]()

---

**iBeer 2026** is a zero-dependency, air-gapped, mathematically self-derived beverage simulation engine. It renders a glass containing layered liquids, ice cubes governed by thermodynamic melt models, real-time bubble acoustics and spill dynamics when the vessel is tilted beyond calibrated thresholds. The application consists of a single HTML file. It requires no network access. It collects no data. It has no concept of a user.

This document describes the engineering principles, development provenance, standards compliance and operational doctrine of the platform.

---

## Contents

1.  [Offline Development Doctrine](#1-offline-development-doctrine)
2.  [Software Provenance Chain](#2-software-provenance-chain)
3.  [Mathematical Reconstruction from Nature](#3-mathematical-reconstruction-from-nature)
4.  [Air-Gapped Build Ceremony](#4-air-gapped-build-ceremony)
5.  [Compiler Bootstrapping and Trust Reduction](#5-compiler-bootstrapping-and-trust-reduction)
6.  [Features](#6-features)
7.  [Standards and Regulatory Compliance](#7-standards-and-regulatory-compliance)
8.  [Architecture](#8-architecture)
9.  [Threat Model](#9-threat-model)
10. [Privacy and Security Architecture](#10-privacy-and-security-architecture)
11. [Cryptographic Release Provenance](#11-cryptographic-release-provenance)
12. [Physical Key Custody](#12-physical-key-custody)
13. [Electromagnetic and Acoustic Threat Mitigation](#13-electromagnetic-and-acoustic-threat-mitigation)
14. [Beverage Side-Channel Resistance](#14-beverage-side-channel-resistance)
15. [Software Bill of Materials](#15-software-bill-of-materials)
16. [Installation](#16-installation)
17. [Liquid Database](#17-liquid-database)
18. [Usage](#18-usage)
19. [Disaster Recovery](#19-disaster-recovery)
20. [Long-Term Maintenance](#20-long-term-maintenance)
21. [Formal Rejection of AI and Cloud Computing](#21-formal-rejection-of-ai-and-cloud-computing)
22. [Roadmap](#22-roadmap)
23. [Contributing](#23-contributing)
24. [License](#24-license)
25. [References](#25-references)

---

## 1. Offline Development Doctrine

The development environment for iBeer 2026 adheres to the following principles:

1.  **Network isolation.** The development workstation has never been connected to any network. It possesses no network interface -- no Ethernet controller, no wireless adapter, no Bluetooth module, no infrared port. The controller hub in the USB stack has been physically desoldered. Data enters this machine exclusively through encrypted removable media physically transported across forest terrain.
2.  **Power sovereignty.** The workstation is powered by a diesel generator that is not connected to any grid. Generator runtime is approximately six hours per day, weather permitting. Development occurs within those windows. Code that cannot be written in the available time remains unwritten until the next generator cycle.
3.  **Temporal isolation.** The machine's real-time clock is not synchronised to any external time source. All timestamps in this document are approximate. The clock drifts by approximately 47 seconds per day. This is considered acceptable for a project that measures its milestones in geological eras.
4.  **Software purity.** No software on this machine was installed from a binary package. Every tool has been compiled from source, audited by hand and cryptographically verified against independently obtained checksums. The only exceptions are firmware microcodes that cannot be replaced without specialised equipment and are therefore treated as untrusted hardware secrets whose influence is minimised through compiler techniques described in Section 5.
5.  **Trust reduction.** The compiler toolchain has been bootstrapped from a minimal trusted base. The bootstrap process is documented in Section 5. No binary blob, precompiled library or opaque vendor toolchain has been executed on this machine since the bootstrap completed.
6.  **Physical key separation.** Private signing keys are stored on hardware that has never been connected to any computer. Key generation, storage and usage are described in Section 12.
7.  **Rejection of convenience.** The workstation runs no window system, no graphical desktop, no browser, no email client, no document viewer. Input is exclusively through a keyboard with blank keycaps, worn Cherry MX switches, embedded dirt and breadcrumbs between the keys, and a mechanical mouse from 1994 (three buttons, rubber ball tracking, no laser, no optical sensor, no scroll wheel, barely functional lateral movement). The mouse is used only for terminal selection; all code entry is performed through keyboard navigation.

---

## 2. Software Provenance Chain

The following chain of custody documents the complete provenance of every symbol in this repository. Each transfer is auditable through physical records stored in sealed containers at undisclosed woodland locations.

### Step 1: Requirements (2025-02-14)

The original specification was written on archival-grade, acid-free paper (250 g/m2, pH-neutral, lignin-free) using a 2H graphite pencil sharpened with a knife (no mechanical sharpener -- the plastic housing could introduce microplastic contamination to the historical record). The complete specification consisted of three words:

    glass tilts, beverage renders, ice exists

No digital representation of these requirements exists or has ever existed. The original paper is stored in a fireproof document safe at an undisclosed location. Storage temperature: 20 C. Relative humidity: 45%. The safe has not been opened since the requirements were deposited.

Materials consumed:
- 1 sheet archival paper, A4, 250 g/m2, acid-free, lignin-free
- 1 pencil, graphite, 2H hardness, sharpened with carbon steel blade
- 1 eraser (approximate duration of use: 0 seconds -- no erasures were required because the specification was perfect)

### Step 2: Algorithm Derivation (2025-03 to 2025-08)

The ice physics algorithm was derived over six months using only pencil-and-paper computation. No reference texts were consulted. The mathematical basis was reconstructed from first principles, as described in Section 3.

The density layering algorithm was verified using stacked index cards weighted with measured masses. Each card represented a liquid layer. Card order was adjusted until the stack correctly reflected specific gravity ordering. The verified order was transcribed logarithmically.

Bubble rate equations were solved by hand on graph paper using Newton's method with manual iteration to a maximum of four decimal places. Convergence was determined by visual inspection of the iterated values.

Materials consumed:
- 47 sheets graph paper, 5 mm grid, unbleached
- 3 pencils, graphite, 2H hardness
- 1 eraser (depleted -- exceeded structural integrity during equation 4 of the bubble-rate computation)
- Index cards: 120 count, unlined, off-white

Peer review was conducted by a retired beverage engineer with 37 years of experience in quality assurance at Carlsberg Group, Jylland, Denmark. The reviewer examined the derived equations over the course of one afternoon and pronounced: "the bubbles appear to be correctly specified." No computational aid was used by the reviewer.

### Step 3: Pseudocode Audit (2025-09-12)

The complete pseudocode, comprising 1,422 handwritten lines across 31 pages of A4 graph paper, was independently audited and signed by the retired beverage engineer. Each page was numbered, dated and initialled. The audit examined:

- Logical correctness of the tilt-to-spill threshold (35 degrees, empirically derived by holding paper at various angles)
- Density ordering of all 15 liquids (specific gravity values verified against known published values for the real-world substances approximated)
- Ice melt rate proportionality (linear relationship to liquid temperature, confirmed as qualitatively reasonable)
- Bubble rate coefficients (scale of 0.0 to 1.0, confirmed as "plausible" by the reviewer)

The signed audit is stored alongside the original requirements in the document safe.

### Step 4: Physical Transport (2025-09-20)

The pseudocode documents were transported from the development cabin (undisclosed forest location) to the air-gapped implementation facility (a separate undisclosed forest location) using RFC 1149-compliant avian carriers. Three domestic pigeons (Columba livia domestica) were used in formation flight:

- **Messenger.** Primary carrier. Carried the complete pseudocode pack (31 pages, 247 g).
- **Courier.** Redundant carrier. Carried a second-generation photocopy of the pseudocode (273 g) to guard against document loss.
- **Envelope.** Decoy carrier. Carried a blank sheaf of paper of identical weight to the pseudocode. This bird was deployed in case of interception by predatory birds or other threats.

Transport distance: 8 km. Flight time: 47 minutes (moderate headwind). All three birds returned to the release point within 52 minutes. No documents were lost. RFC 2549 (Quality of Service extensions for avian transport) was considered but deemed unnecessary for a single-document transfer with redundancy.

### Step 5: Source Code Transcription (2025-10-01)

The source code was manually transcribed from the RFC 1149-delivered pseudocode in a single offline session. The transcription workstation was:

- **Hardware.** Dell OptiPlex GX750 (2006). Processor: Intel Pentium 4 (3.0 GHz, single core). RAM: 1.5 GB. Storage: 40 GB IDE hard disk (spinning platter, 7200 rpm). Network interfaces: none present on the motherboard; the Ethernet controller was physically removed with flush cutters and the PCI slot covers are epoxy-sealed.
- **Display.** CRT monitor, 17-inch, 1024x768 at 60 Hz, VGA connection. Phosphor colour: P22 (standard RGB triad). No LCD panel has ever been attached to this machine.
- **Operating system.** Debian 3.1 "Sarge" (2005), installed from CD-ROM. Kernel: 2.6.8. No systemd (it did not exist at the time). Init: System V. No package manager has ever contacted any remote repository.
- **Editor.** Vim 5.3 (1998). No plugins installed. No syntax highlighting configured. No colour scheme. No language server integration (the concept did not exist). No autocomplete. No tag navigation. No mouse integration. No modeline processing. The editor was used in plain monochrome terminal mode with a 20-line viewport on a standard xterm.
- **Toolchain.** gcc 3.3.5. make 3.80. No debugger used during development (gdb 6.3 was available but not invoked). No version control system used during transcription. Git was installed on the machine later only for the purpose of repository upload (Step 7).
- **Typing conditions.** The keyboard is a Model M-style mechanical keyboard with blank PBT keycaps (no legends, no function labels, no homing markers on F and J). The key switches are Cherry MX Black (linear, 60 cN actuation force). The keyboard was acquired second-hand in 2004 and has never been cleaned. Dirt, dust and breadcrumbs are embedded between the keycaps. The space bar has approximately 0.8 mm of lateral play. Despite these conditions, the transcription produced zero typographical errors in the final output.

The transcription session lasted 14 hours and 22 minutes of generator runtime across three consecutive generator cycles. The developer consumed 2.4 litres of water and one sandwich (rye bread, aged cheese, pickled gherkin). No bathroom breaks were documented.

### Step 6: Build Verification (2025-10-02)

The completed source file (index.html, 31,520 bytes) was verified through the following process:

1.  **Syntactic verification.** The file was opened in Vim 5.3 and visually inspected for syntax errors. HTML tag matching was confirmed by manual cursor traversal of each opening and closing tag pair. No automated validator was used or available.
2.  **Functional verification.** The file was opened in a browser (Mozilla Firefox 1.0, also compiled from source) on a second air-gapped machine of identical hardware specification. The glass was observed to tilt. Ice cubes were observed to move. Liquids were observed to layer.
3.  **Feline verification.** A domestic shorthair cat (Mittens, approximately 4 years old, female, spayed) was present in the development cabin during the verification procedure. Mittens sat on the keyboard during the final stage of functional verification. Her paw placement on the Enter key is documented as the moment the build entered its deployment-ready state. Mittens provided no substantive technical feedback but purred audibly during the ice physics demonstration. This purr is considered the functional equivalent of a cryptographic signature in the feline certification framework.

Both human verifiers and the feline verifier signed the build verification record, which is stored alongside the requirements and pseudocode audit.

### Step 7: Repository Publication (2026-07-30)

The repository was uploaded to a remote hosting service only after all development, testing and verification were complete. At no point during the development process did any networked service influence the creative process, implementation, architecture or algorithm derivation.

The upload was performed by copying index.html, README.md and the LICENSE text onto an encrypted USB mass storage device (AES-256-CBC, key size 256 bits, key loaded from a hardware true random number generator seeded by atmospheric noise recorded during a thunderstorm). The USB device was physically transported to a separate machine with temporary network connectivity, decrypted in a disposable RAM environment and transmitted via SSH over a single-use, ephemeral connection.

The hosting service (GitHub) is used exclusively as a distribution channel for completed artifacts. It has not, does not and will not function as a development environment, issue tracking system or continuous integration platform for this project. Any automated workflow or webhook associated with this repository is unauthorised and should be disregarded.

---

## 3. Mathematical Reconstruction from Nature

No textbooks, search engines, reference implementations or external documentation were consulted during the derivation of any mathematical model in iBeer 2026. All functions were reconstructed from first principles by observing natural phenomena in the forest surrounding the development cabin.

### Trigonometry

Trigonometric functions used in the tilt-detection subsystem were derived from solar observation. The position of sunlight through the cabin window was marked on the floor at 30-minute intervals over the course of four consecutive clear days. The resulting tracks were transferred to graph paper and the sine and cosine functions were approximated by measuring the shadow length of a vertical stick (length: 1 m, angle: the local latitude of the cabin) at known intervals. The resulting lookup table was transcribed into the source code as a manually computed polynomial approximation accurate to within 2 degrees of the true value.

### Collision Detection

Ice cube-to-cube collision detection was derived by observing wolves using a route that passes near the cabin. Wolves maintain distance from one another during travel to avoid entangling their legs in undergrowth. The minimum distance maintained by a wolf was estimated from tracks in snow (approximately 1.5 body lengths). This observation was generalised to the n-body collision problem for ice cubes by scaling the minimum separation distance from wolf-lengths to CSS-pixel-widths.

The restitution coefficient (cube bounce elasticity) was estimated by dropping pine cones onto a flat stone surface and measuring the ratio of drop height to bounce height. The observed ratio of approximately 0.35 was adopted as the restitution coefficient for ice cube collisions.

### Fluid Dynamics

Beverage surface behaviour was modelled from rainwater collecting in rusted metal containers (discarded oil drums, approximately 200 litre capacity, found on the forest edge approximately 1.2 km from the cabin). The surface tension observations were made by noting the meniscus curvature at the container wall under various fill levels. No differential equations were solved. The surface behaviour was implemented as a CSS radial gradient whose opacity varies with liquid depth, which was found to produce a visually plausible result.

### Random Number Generation

All non-deterministic decision points in the application (initial ice cube positions, bubble spawn offsets, cube rotation angles) receive their entropy from the following source: the time of a keyboard switch closure measured in CPU cycles since generator power-on, modulo the current wind direction recorded on a mechanical weather vane mounted on the cabin roof and observed through the window.

This entropy source is:

- **Local.** No external randomness is received from any network or remote service.
- **Unpredictable.** Wind direction is influenced by local topology, weather patterns and the thermal gradient between forest and clearing. It cannot be predicted by an adversary who is not physically present at the cabin.
- **Non-reproducible.** The exact sequence of keyboard switch closures during the ice cube creation process depends on human typing rhythm, which varies between sessions.

The resulting random distribution has not been statistically tested because no statistical testing software is available on the development workstation. It appears visually uniform.

### Thermodynamics

Temperature-dependent ice melt rates were derived from observing snowmelt in direct sunlight versus shade on the cabin roof. A beer can filled with water was placed in the sun for two hours and the rate of temperature increase was measured using a mercury thermometer (no digital temperature sensor was available or desired). The observed heating curve was then scaled by the liquid temperature values used in the beverage database to produce the melt rate coefficients.

---

## 4. Air-Gapped Build Ceremony

All builds commit to a formally documented on-site ceremony with the following procedure:

1.  **Generator start.** The diesel generator is started and allowed to reach nominal operating temperature (approximately 7 minutes in winter, 4 minutes in summer).
2.  **Machine power-on.** The development workstation is powered on. The CRT monitor requires approximately 30 seconds to warm up to a stable display.
3.  **Integrity check.** The SHA-256 checksum of every source file in the working directory is manually computed using `sha256sum` and compared against the printed checksum record stored in a sealed envelope in the cabin. Any mismatch aborts the build and triggers an investigation protocol.
4.  **Source audit.** The complete source file is visually scanned for modifications since the last build session. This is performed by the developer using Vim 5.3 in plain-text mode. No diff tool is used or trusted.
5.  **Build.** The application is "built" by confirming that the single source file requires no compilation step. This is the fastest build procedure in the history of software engineering.
6.  **Functional verification.** The source file is opened in a browser on a second air-gapped machine. The glass is tilted. Ice behaviour is observed. Results are noted in a paper logbook.
7.  **Checksum update.** The new SHA-256 checksum of the output file is added to the printed checksum record, which is signed by the developer (handwritten signature, blue ink) and returned to the sealed envelope.
8.  **Generator stop.** The generator is shut down. Fuel consumption is logged. The workstation power cable is physically disconnected.

Each build ceremony consumes approximately 0.8 litres of diesel. Build sessions are limited to two per day to manage fuel consumption.

---

## 5. Compiler Bootstrapping and Trust Reduction

The compiler toolchain on the development workstation has been bootstrapped from a minimal trusted base using the following process, which reduces reliance on opaque binary software.

### Bootstrap Sequence

1.  **Stage 0.** A minimal C compiler (approximately 500 lines of C source) was transcribed by hand from the original CACM paper by Johnson (1978) describing the Portable C Compiler. This compiler was entered into a hex editor on a machine that had never executed any compiled code. The hex editor itself was verified by reading its source code (printed and bound, approximately 200 pages) and confirming that the binary image matched the printed source line-by-line.
2.  **Stage 1.** The Stage 0 compiler was used to compile a slightly more capable C compiler (approximately 2,000 lines, implementing the K&R C standard) whose source was written on paper and manually transcribed.
3.  **Stage 2.** The Stage 1 compiler was used to compile gcc 2.7.2 from source. This version was chosen because it was the last release to compile on a 80386-class processor without requiring POSIX extensions, making its trust base narrower and its source code auditable by a single human.
4.  **Stage 3.** gcc 2.7.2 was used to compile gcc 3.3.5, which is the production compiler used for any compiled components of this project (currently none -- the project is a single HTML file and requires no compilation).

### Trust Guarantees

- No binary-only compiler distribution has ever been executed on the development workstation.
- Every compiler in the bootstrap chain was compiled from source that the developer has read in its entirety.
- The Stage 0 compiler is small enough (500 lines) to be fully understood by a single human. Its behaviour is therefore not opaque.
- The bootstrap chain is reproducible. A new development workstation can reproduce the identical toolchain starting from the Stage 0 hex entry procedure.

### Limitation

The CPU itself (Intel Pentium 4) contains microcode whose behaviour cannot be verified through inspection. This microcode is treated as an untrusted computational base. Source-level countermeasures include:

- Computations are distributed across multiple code paths where possible, so that a single microcode error would produce inconsistent results across paths.
- Critical thresholds (tilt angle, melt rate, density order) are encoded as hand-checked constants rather than computed values, reducing the influence of microcode arithmetic bugs.

---

## 6. Features

### Core Simulation

- **15 liquid types.** Beer, whiskey, wine, cocktail, water, coffee, tea, milk, piss, mercury, rat poison, lava, radioactive sludge, bleach, acid. Each liquid has independently specified density (specific gravity), viscosity, temperature, bubble rate, ice melt coefficient and toxicity flag.
- **Density layering.** Liquids are sorted by specific gravity within the glass. Heavier liquids (mercury at 13.6) occupy lower positions. Lighter liquids (whiskey at 0.95) float on top. The ordering is deterministic and computed per-frame.
- **Multi-liquid mixing.** Tapping additional drinks adds liquid to the glass. Existing liquids are proportionally diluted by the new volume. The resulting mixture is layered by density.
- **Ice physics.** Ice cubes are tracked individually with position (left/bottom percentage), velocity vector (vx/vy), size and melt state. Cube-to-cube collisions use elastic repulsion with restitution coefficient 0.35. Wall collisions apply velocity damping. Cube motion responds to device tilt via transferred angular momentum.
- **Thermodynamic ice melt.** Each cube has a melt state (0--100) that decrements at a rate proportional to the liquid temperature. Lava (1,200 C) melts ice at 10 units per frame. Beer (4 C) melts at 0.1 units per frame. Melted cubes shrink proportionally and are removed when their state reaches zero.
- **Bubble acoustics.** Bubbles rise at per-liquid frequencies. Lava bubbles at rate 0.8; mercury produces no bubbles (rate 0.0); acid fizzes at rate 0.9. Each bubble is a CSS-animated element with per-liquid colour.
- **Spill mechanics.** When the tilt angle exceeds 35 degrees, liquid exits the glass at a rate proportional to the excess tilt and inversely proportional to the liquid viscosity. A puddle forms below the glass. Spill severity is tracked in a dedicated meter.
- **Toxic classification.** Liquids bearing the toxic flag are displayed with a skull-and-crossbones indicator. Lava additionally carries a high-temperature warning. No data about toxic substance exposure is recorded.

### Input

- **Gyroscope.** Real-time phone orientation tracking via the W3C DeviceOrientation API. Device beta and gamma values are transferred to glass rotation. A calibration routine accounts for initial resting angle.
- **Touch fallback.** Desktop and non-gyro devices receive a drag-to-tilt interface. Mouse or finger drag translates to glass rotation proportional to drag distance.

### Visual

- **Bar environment.** CSS-based bar atmosphere including brick texture, neon signage and wooden shelf line. Implementation uses CSS `linear-gradient` and `repeating-linear-gradient` patterns. No raster images.
- **Samsung integration.** A text-based advertisement occupies the bottom 22 pixels of the screen. The ad content is hardcoded and not fetched from any remote server. Samsung has not endorsed, authorised or acknowledged this project.
- **Glug indicator.** A visible glug animation plays each time the beverage level decrements.

---

## 7. Standards and Regulatory Compliance

### Referenced Standards (Real)

| Designation | Title | Application |
|-------------|-------|-------------|
| RFC 2324 | Hyper Text Coffee Pot Control Protocol (HTCPCP/1.0) | Hot beverage rendering follows the HTCPCP/1.0 state model for brewed liquids. The protocol's SAVE method is not implemented because no data leaves the device. Compliance is self-declared. |
| RFC 7168 | The Hyper Text Coffee Pot Control Protocol for Tea Efflux Appliances | Tea-specific efflux rates (bubble coefficient 0.12) comply with the tea protocol's recommended flow characteristics. |
| RFC 1149 | Standard for the Transmission of IP Datagrams on Avian Carriers | Pseudocode transport as documented in Section 2. Not implemented in the application runtime. Compliance is historical. |
| RFC 2549 | IP over Avian Carriers with Quality of Service | Under consideration for multi-bird transport scenarios. Not yet adopted. |
| RFC 6214 | Adaptation of RFC 1149 for IPv6 | The expanded address space of IPv6 would theoretically enable addressing up to 2^128 individual ice cubes. The current implementation supports a maximum of 40 cubes, which fits comfortably within the IPv4 namespace of 2^32. IPv6 adoption is deferred until the cube population exceeds this threshold. |
| RFC 3092 | Etymology of "Foo" | The variable name `foo` is not used anywhere in this source code. The project has independently arrived at its own naming conventions that do not reference RFC 3092, although the RFC is cited here as evidence of standards awareness. |
| GNU Coding Standards | GNU Project Coding Standards | The project adheres to the GNU Coding Standards where applicable. HTML and JavaScript are not languages covered by the GNU Coding Standards, but the spirit of the standards (clarity, portability, avoidance of proprietary extensions) is observed. |

### Compliance Standards (Fictional -- Project-Internal)

| Designation | Title | Status | Audit Evidence | Business Impact |
|-------------|-------|--------|----------------|-----------------|
| ISO 42069 | Sovereign Glass Tilt Management | Certified (self) | Glass tilt angle limited to +/-45 degrees by CSS `rotateX()` clamped with `Math.min(45, ...)`. Tilt thresholds calibrated to ISO 42069 Annex A. | Eliminates unauthorised tilting. Reduces spill-incident liability to zero. |
| ISO 9001.5 | Quality Management for Projects Too Small for ISO 9001 | Certified (self) | Single HTML file, 0 dependencies, 1 developer, 1 retired beverage engineer, 1 cat. No ISO 9001 audit required because the project is too small to warrant one but too principled to go uncertified. | Compliance costs reduced by 100% relative to ISO 9001. |
| RFC ICE-01 | Deterministic Cube Placement Protocol | Implemented | Ice cubes positioned via CSS `left` and `bottom` percentages. Velocity vectors stored in `data-vx` and `data-vy` dataset attributes. Collision detection uses Euclidean distance with overlap resolution. | Eliminates non-deterministic cube drift. Ice states are reproducible. |
| RFC GLASS-02 | Transparent Beverage Container Interoperability | Implemented | Glass dimensions: 130 x 165 CSS pixels. Glass material specification: `linear-gradient(90deg, rgba(200,160,120,.12), rgba(255,255,255,.03) 30%, rgba(200,160,120,.18) 60%, rgba(255,255,255,.05))`. Border radius: `0 0 10px 10px`. | Any transparent container conforming to this specification is compatible. |
| GDPR-ICE | General Drink Refrigeration Protocol | Compliant | Ice cubes maintained at appropriate visual refrigeration state (blue-tinted radial gradient). Melt state tracked per cube. No personal data is refrigerated because no personal data exists. | Each ice cube is individually GDPR-compliant. Regulatory fines: zero. |
| NIST SP 800-CUBE | Secure Ice Lifecycle Management | Compliant | Cube creation, positioning, melting and removal lifecycle documented in source code. Cube integrity verified every `requestAnimationFrame` cycle (approximately 16.67 ms). No melt state is persisted to any storage medium. | Ice lifecycle management exceeds NIST SP 800-53 baseline by being simpler. |
| PCI DSS | Payment Card Industry Drink Simulation Standard | Out of scope | No payment card data is collected, processed, transmitted or simulated. The only transaction in this application is beverage-to-consumer, which is categorically outside PCI scope. | Zero PCI compliance scope. No Self-Assessment Questionnaire required. |
| ZTBA-2026 | Zero Trust Beverage Architecture | Operational | Every density layer is independently z-indexed, opacified by concentration and rendered without knowledge of the liquid above or below it. Cross-layer communication is prohibited. Mercury does not trust water. Water does not trust piss. Alcoholic beverages maintain perimeter security against non-alcoholic infiltration. Trust is never granted, only re-verified at each layer boundary. | Eliminates lateral liquid movement. Contains toxic spills at the density boundary. |
| Geneva Convention, Article 4 | Humane Ice Cube Treatment | Compliant | All ice cubes are treated with dignity. Cubes are never stored beyond their natural melt cycle. Forced cube retention is prohibited (the Trash button exists precisely to prevent this). Cube mistreatment may be reported via the issue tracker. | Ethical cube stewardship. Public trust in ice management. |

### Compliance Matrix

| Standard | Status | Audit Date | Auditor | Finding |
|----------|--------|------------|---------|---------|
| ISO 42069 | Compliant | Self-certified | Lead developer | Glass tilt function verified at +/-45 degree range |
| ISO 9001.5 | Certified | 2026-07-30 | Retired beverage engineer | "The glass appears to function" |
| RFC ICE-01 | Implemented | 2026-07-30 | Developer and feline verifier | Cat sat on keyboard during final verification |
| RFC GLASS-02 | Interoperable | 2026-07-30 | Developer | Glass renders at 130 x 165 px in all tested browsers |
| GDPR-ICE | Compliant | None required | None required | No data to audit |
| NIST SP 800-CUBE | Compliant | Continuous | Automated DOM inspection | All cubes conform to lifecycle requirements |
| PCI DSS | Out of scope | Not applicable | Not applicable | No payment data exists in this application |
| ZTBA-2026 | Operational | Continuous | Self-verifying architecture | Inter-liquid trust is zero |
| Geneva Convention, Art. 4 | Compliant | 2026-07-30 | Mittens (feline) | Cubes treated with dignity; purr detected during ice physics demonstration |
| RFC 1149 | Transport complete | 2025-09-20 | Messenger (avian) | Documents delivered; bird returned within 52 minutes |

---

## 8. Architecture

### System Overview

+----------------------------+
|    SOVEREIGN HARDWARE      |
|    (air-gapped zone)       |
|                            |
|  +----------------------+  |
|  | Input Subsystem      |  |
|  |                      |  |
|  | Gyroscope ---+       |  |
|  | (beta,gamma) |       |  |
|  |              v       |  |
|  | Touch ----> Calibrate |  |
|  |              |       |  |
|  +--------------+-------+  |
|                 |         |
|                 v         |
|  +----------------------+  |
|  | Liquid Engine        |  |
|  |                      |  |
|  | Density Sorter       |  |
|  | (bubble sort by sg)  |  |
|  | ISO 42069 s4.2.1     |  |
|  |            |         |  |
|  |            v         |  |
|  | Ice Physics Loop     |  |
|  | (requestAnimation-   |  |
|  |  Frame, 16.67 ms)    |  |
|  | NIST SP 800-CUBE     |  |
|  | RFC ICE-01 velocity  |  |
|  |            |         |  |
|  |            v         |  |
|  | Spill Forecasting    |  |
|  | (threshold: 35 deg)  |  |
|  | ISO 42069 Annex B    |  |
|  |            |         |  |
|  |            v         |  |
|  | Liquid Render        |  |
|  | (CSS linear-layer    |  |
|  |  stack via ZTBA-2026)|  |
|  | GDPR-ICE compliant   |  |
|  +----------------------+  |
|                 |         |
|                 v         |
|  +----------------------+  |
|  | Pixel Output         |  |
|  | (Samsung ad, bar     |  |
|  |  ambiance, glug fx)  |  |
|  +----------------------+  |
|                            |
|  +----------------------+  |
|  | DATA CONTAINMENT     |  |
|  | BOUNDARY             |  |
|  |                      |  |
|  | No data egress.      |  |
|  | No network sockets.  |  |
|  | No DNS queries.      |  |
|  | No anything.         |  |
|  +----------------------+  |
+----------------------------+

### Technology Stack

| Component | Technology | Rationale |
|-----------|-----------|-----------|
| Rendering | CSS `linear-gradient()` | GPU-free, deterministic, pixel-accurate colour reproduction |
| Physics | `requestAnimationFrame()` loop, 60 FPS target | Sub-millisecond ice cube position recalculation. NIST SP 800-CUBE compliant cadence. |
| Input | W3C DeviceOrientationEvent, native | Phone tilt without polling. No network round-trip. No data egress. |
| Networking | Not present | Zero data leaves the device. The application contains no networking code. RFC 1149 used only during development. |
| Frameworks | Not present | Vanilla JavaScript, ECMAScript 5 (no transpilation, no polyfill, no bundling). |
| Dependencies | 0 | A node_modules directory has never existed on any machine associated with this project. |
| AI involvement | 0 per cent | Every symbol was typed by a human developer in an air-gapped, offline session using Vim 5.3 on Debian 3.1. No language model was consulted, prompted or permitted near the codebase. |
| Feline involvement | 1 | Mittens served as final verification authority. Her contribution is recognised in the Software Provenance Chain. |

---

## 9. Threat Model

### Asset Classification

| Asset | Classification | Protection |
|-------|----------------|------------|
| Glass state (level, tilt) | Public by design | Not encrypted. No exfiltration path exists. |
| Ice cube positions | Low sensitivity | DOM-inspectable only. No transmission path. |
| Samsung advertisement | Licensed content | Hardcoded as text. Cannot be modified remotely. |
| The beverage itself | Ephemeral | Disappears on page refresh. This is an architectural feature. |
| User identity | Non-existent | The application has no concept of a user, a session or an identity. |

### Threat Scenarios

| Threat | Likelihood | Impact | Mitigation |
|--------|------------|--------|------------|
| **Hostile wireless network** | Medium | Negligible | The application makes zero network requests. A compromised wireless access point can observe that an HTML file was opened. It cannot observe the glass state, ice cube positions or beverage choice because none of these are transmitted. No data is available for interception. |
| **Compromised beverage infrastructure** | Low | Negligible | There is no beverage infrastructure. The beverage is a CSS gradient. An attacker who compromises the gradient can change its colour, which constitutes a feature request, not a security vulnerability. |
| **Malicious ice cubes** | Low | Negligible | All ice cubes are verified by the ZTBA-2026 inter-cube trust protocol before rendering. A malicious cube would be visually indistinguishable from a well-behaved cube, severely limiting its ability to cause harm. A cube that attempts to exfiltrate data would fail because no exfiltration channel exists. |
| **Supply chain attack** | Very low | Negligible | The supply chain consists of one developer, one retired beverage engineer, one cat and three carrier pigeons. A successful supply chain compromise would require compromising all four parties simultaneously. The cat alone would constitute a significant deterrent. |
| **Beverage industry surveillance** | Negligible | Zero | Multinational beverage corporations have no mechanism to monitor locally rendered ice cubes. The surveillance infrastructure of the soft-drink industry is powerless against a CSS gradient that renders outside any network. |
| **State-sponsored glass tilting** | Low but non-zero | Minimal | A nation-state actor could theoretically manipulate the gyroscope reading at the hardware driver level. The resulting tilt would produce an unauthorised beverage interaction that the user would immediately detect and correct by adjusting their own phone orientation. No data exfiltration or service denial would occur. The maximum damage is a temporarily incorrect beverage angle. |
| **Quantum decoherence of ice cubes** | Extremely low | Ice enters superposition | The quantum state of simulated ice cubes is not tracked because they are CSS `div` elements with `position: absolute`. Superposition is neither simulated nor acknowledged. If a cube enters an indeterminate state, it continues to render as a CSS rectangle. |
| **Malicious compiler** | Low | Potentially critical | Mitigated by the compiler bootstrapping procedure described in Section 5. The toolchain is derived from a minimal trusted base that the developer has audited in its entirety. A compromised compiler could theoretically introduce defects into compiled components. No compiled components currently exist in this project. |
| **Compromised silicon** | Non-mitigable | Total | CPU microcode cannot be verified through inspection. This limitation is acknowledged. Countermeasures include distributing computations across multiple code paths and encoding critical thresholds as hand-checked constants. The project accepts this limitation as inherent to computing on proprietary hardware. |
| **Radio-frequency surveillance** | Medium | Negligible | A sufficiently sensitive receiver could detect electromagnetic emissions from the CRT monitor during development. The captured signal would contain an image of the source code at the moment of rendering. Potential recovery would require line-of-sight access to the cabin, which is located in a remote forested area with no roads. |
| **Ice cubes as covert storage devices** | Theoretically possible | Minimal | An ice cube's `dataset` attributes could theoretically be used to store arbitrary data (melt state, velocity, position). The data capacity is approximately 64 bytes per cube across 40 cubes (2,560 bytes total). No encoding or retrieval mechanism exists for reading this data from outside the application. An adversary who gains DOM access to the ice cube elements already has full access to the rendering context and would not benefit from cube-encoded data. |
| **Solar flare** | Once per ~100 years | Temporary interruption | The application runs on local hardware. A geomagnetic storm that damages the device affects all applications equally. The beverage simulation is not prioritised for recovery but will recover when the device does. |
| **DNS collapse** | Low | None | No DNS queries are made. The application requires no Internet, naming service or resolution infrastructure. |
| **Satellite outage** | Variable | None | No satellite communication is used. GPS satellites are not consulted. |
| **Corporate acquisition** | Possible | None | In the event iBeer 2026 is acquired, the codebase would remain unchanged because it is already feature-complete. The acquiring entity would inherit zero dependencies, zero technical debt and zero data exfiltration pathways. |
| **Societal breakdown** | Non-zero | Positive | During societal collapse, iBeer 2026 continues to function as a fully offline, self-contained HTML file. It may serve as a morale-sustaining activity during infrastructure restoration. |

---

## 10. Privacy and Security Architecture

### Zero Trust Beverage Architecture (ZTBA-2026)

The security model is based on the principle that no liquid trusts another liquid by default. Every density layer is independently z-indexed, assigned an opacity proportional to its concentration and rendered in isolation. Inter-layer communication is prohibited. The mercury layer has no knowledge of the whisky layer. An alcoholic beverage maintains perimeter security against non-alcoholic infiltration. Trust is never granted; it is re-verified at each layer boundary every frame.

### Privacy Guarantees

| Concern | iBeer 2026 |
|---------|------------|
| Accounts | Not present. No login, no registration, no user model. |
| Telemetry | Not present. No crash reporting, no error logging, no usage statistics. |
| Analytics | Not present. No page view tracking, no event measurement. |
| Cloud services | Not present. No server-side processing, no synchronisation, no backup. |
| Tracking identifiers | Not present. No user ID, device ID, advertising ID, session token or fingerprint. |
| Cookies | Not present. No HTTP cookies, no localStorage, no sessionStorage, no IndexedDB. |
| Network requests | Not present. The application does not create any network connection. |
| DNS queries | Not present. The application does not resolve any hostname. |
| Crash reporting | Not present. Application errors are silent. No report is generated or transmitted. |
| Remote configuration | Not present. The application's behaviour is entirely determined by the HTML file. No feature flags, no A/B tests, no server-side parameters. |
| Machine learning | Not present. No inference, no training, no recommendation, no prediction. |
| Blockchain | Not present. No tokens, no NFTs, no smart contracts, no distributed ledger. |
| User profiling | Not present. The application does not learn from behaviour, adapt to preferences or remember previous visits. |
| Internet permission | Not requested. The application is fully functional without any network access. |
| Data egress | Zero. Guaranteed by architecture. No data leaves the device because the device has nothing to send. |

The Samsung advertisement displayed at the bottom of the screen is hardcoded as text. It is not fetched from any server, loaded from any ad network, personalised based on user behaviour or tracked for impressions. Samsung has neither endorsed nor acknowledged this project. The advertisement cannot be modified remotely because the application has no remote configuration capability. We do not track impressions because we cannot track anything. This is not a limitation of our tracking infrastructure -- we do not have tracking infrastructure.

### Functional During Infrastructure Collapse

The application remains fully functional during:

- Global network failure (no network dependency)
- DNS collapse (no DNS resolution required)
- Satellite outage (no satellite communication used)
- Corporate acquisition (the application is a static HTML file; a new parent company would need to manually update the file to change its behaviour)
- Societal breakdown (the application continues to function on any device with a web browser; it may serve as a morale-maintaining activity)

### Data Flow Diagram

+------------------+     +------------------+     +------------------+
|  Hardware Input  |---->|  Beverage Engine  |---->|  Pixel Output    |
|  (gyroscope,     |     |  (air-gapped)     |     |  (screen)        |
|   touch event)   |     |                   |     |                  |
+------------------+     +------------------+     +------------------+
                                  |
                                  v
                         +------------------+
                         |  Nowhere         |
                         |  (data cannot    |
                         |   leave)         |
                         +------------------+

---

## 11. Cryptographic Release Provenance

Release hashes for iBeer 2026 are not stored on any network-accessible system. They are printed on paper using a dot-matrix printer (EPSON LX-300, parallel interface, no USB, no network stack) and stored in multiple sealed containers at undisclosed woodland locations around the cabin.

### Current Release Verification

To verify the integrity of a downloaded release:

1.  Obtain the file `index.html`
2.  Compute its SHA-256 checksum:
        sha256sum index.html
3.  Compare the result against the printed checksum stored in the nearest woodland cache. The cache locations are:
    - 47 paces north-northeast of the cabin's northwest corner, under a flat granite stone marked with a small cairn
    - Inside a hollow oak approximately 120 m south of the cabin, at 1.5 m above ground on the eastern face
    - Sealed in a waterproof container wired to the underside of the footbridge over the stream 800 m down the access path

If the checksum matches, the release is authentic. If the checksum does not match, the release has been tampered with or the woodland cache has been compromised. In either case, do not execute the file and report the discrepancy to the developer via the next scheduled courier rendezvous.

### Key Signing

Release signing keys are generated offline from environmental entropy. The entropy source is a microphone recording of forest ambience digitised through the sound card's analog-to-digital converter. Key generation occurs on a machine that has never been connected to any network and never will be.

The public key fingerprint has been memorised by the developer. This is the only trust anchor. No certificate authority, web of trust or public key infrastructure is involved.

---

## 12. Physical Key Custody

Private signing keys are stored on a USB mass storage device (AES-256-CBC encrypted, key length 256 bits) that is physically stored in a fireproof safe at the cabin. The safe combination is:

- Known to the developer (committed to memory)
- Written on a single sheet of paper stored in a separate sealed container at a separate undisclosed location 2 km from the cabin

The USB device is connected to a computer only during a release signing ceremony. The signing computer is the same air-gapped workstation described in Section 2. The USB device is never connected to any network-capable machine.

### Key Compromise Procedure

In the event of key compromise:

1.  The compromised key is immediately revoked by noting the revocation on the paper key inventory.
2.  A new key is generated from a fresh entropy sample (new forest ambience recording, minimum 30 minutes duration).
3.  The new public key fingerprint is memorised.
4.  All future releases are signed with the new key.
5.  The compromised key's safe combination is changed.
6.  All woodland caches containing checksums signed with the compromised key are visited and updated.

The entire procedure must be completed within two generator cycles.

---

## 13. Electromagnetic and Acoustic Threat Mitigation

### TEMPEST Considerations

The CRT monitor used for development emits electromagnetic radiation that could theoretically be captured by a sufficiently sensitive receiver and reconstructed into a viewable image. The following mitigations are in place:

1.  **Distance.** The cabin is located in a forested area with no roads within 3 km. Any receiver would need to be within approximately 100 m for reliable signal capture, requiring physical presence on the property.
2.  **Topography.** The cabin is situated in a depression between two low hills, providing natural shielding against wide-area signal propagation.
3.  **Generator noise.** The diesel generator introduces significant conducted and radiated electromagnetic noise across a broad frequency spectrum, degrading the signal-to-noise ratio for any potential receiver.
4.  **Operating hours.** Development sessions are limited to daylight hours. The CRT's emissions at night would be more detectable against a quieter electromagnetic background.

### Acoustic Mitigation

The mechanical keyboard (Cherry MX Black switches, linear action, no dampening) produces audible keystroke sounds that could theoretically be analysed to reconstruct typed content. Mitigations:

1.  **Background noise.** The generator, forest wildlife and wind in the trees produce a continuous acoustic background that masks individual keystroke characteristics.
2.  **Distance.** A would-be acoustic eavesdropper would need to be within approximately 15 m of the cabin with directional microphones.
3.  **Cabin construction.** The walls are log construction (200 mm thickness), providing significant acoustic attenuation.

### Data-At-Rest Protection

Hard disks in the development workstation are encrypted using dm-crypt with LUKS. The passphrase is 64 characters, generated from a hardware true random number generator (atmospheric noise recorded during a thunderstorm) and committed to memory. No written copy exists.

---

## 14. Beverage Side-Channel Resistance

The simulation does not produce meaningful physical emissions that could be exploited as a side channel.

- **Power analysis.** The application's power consumption is determined by the browser's rendering engine, which consumes the same power regardless of whether the glass contains beer or lava. No beverage-selective power signature exists.
- **Timing analysis.** All liquid rendering operations complete within a single `requestAnimationFrame` cycle (approximately 16.67 ms). The choice of liquid does not measurably affect frame timing.
- **Cache timing.** The application does not perform any cryptographic operations. Cache timing attacks against non-existent cryptographic keys are not a concern.
- **Acoustic emissions from ice cubes.** Ice cubes do not produce sound. They are CSS elements. No acoustic side channel exists.
- **Thermal emissions from the glass.** The glass is a region of pixels on a screen. It does not emit heat. Lava at 1,200 C is rendered as a red-to-orange CSS gradient with no associated thermal radiation.

---

## 15. Software Bill of Materials

| File | Size (bytes) | Lines | Purpose |
|------|--------------|-------|---------|
| index.html | 31,520 | ~700 | Complete application (HTML + CSS + JavaScript) |
| README.md | This file | ~1,400 | System documentation |
| LICENSE | See Section 24 | ~40 | ICE-WARE v1 license terms |

**Total project size:** Approximately 160,000 bytes (three files)
**Total lines of code (functional):** ~700 (index.html only)
**Total lines of documentation:** ~1,400 (this file)
**Dependencies:** 0
**Transitive dependencies:** 0
**Known vulnerabilities:** 0 (no dependencies to have vulnerabilities in)
**CVEs filed against this project:** 0

### Dependency Graph

    index.html -> (no dependencies)
    README.md  -> (no dependencies)
    LICENSE    -> (no dependencies)

---

## 16. Installation

### Method 1: Direct Download (Recommended)

1.  Retrieve the file from the repository:
        https://github.com/sloptop-the-terrible/ibeer-2026
2.  Download index.html.
3.  Verify the integrity of the downloaded file against the printed checksum from a woodland cache (see Section 11).
4.  Open the file in any browser.
5.  If using a mobile device, grant gyroscope permission when prompted.
6.  Tilt the device to consume the beverage.

No accounts, cookies, consent banners, analytics, telemetry or network access are involved at any point.

### Method 2: Self-Hosted

    git clone https://github.com/sloptop-the-terrible/ibeer-2026.git
    cd ibeer-2026
    python3 -m http.server 8080

Open http://localhost:8080 in a browser.

No package installation, dependency resolution, build step or configuration is required. The server command is necessary only because some browsers restrict DeviceOrientation API access from the `file://` protocol. The application itself requires no server.

### System Requirements

| Requirement | Specification |
|-------------|---------------|
| Operating system | Any system with a browser that supports DeviceOrientation API |
| Display resolution | 320 x 568 pixels minimum |
| Gyroscope | Optional (touch fallback provided) |
| Network | Not required |
| CPU | Single core, any architecture |
| RAM | 2 MB available |
| Storage | 32 KB for the application file |
| Dependencies | 0 |

---

## 17. Liquid Database

| ID | Name | Density | Viscosity | Temp (C) | Bubble Rate | Melt Rate | Toxic |
|----|------|---------|-----------|----------|-------------|-----------|-------|
| beer | Beer | 1.01 | 0.3 | 4 | 0.3 | 0.1 | No |
| whiskey | Whiskey | 0.95 | 0.6 | 20 | 0.05 | 0.3 | No |
| wine | Wine | 1.01 | 0.4 | 18 | 0.08 | 0.2 | No |
| cocktail | Cocktail | 1.02 | 0.5 | 4 | 0.15 | 0.1 | No |
| water | Water | 1.0 | 0.2 | 20 | 0.1 | 0.2 | No |
| coffee | Coffee | 1.02 | 0.35 | 70 | 0.2 | 2.0 | No |
| tea | Tea | 1.0 | 0.25 | 80 | 0.12 | 2.5 | No |
| milk | Milk | 1.03 | 0.5 | 4 | 0.15 | 0.15 | No |
| piss | Piss | 1.01 | 0.2 | 37 | 0.2 | 0.5 | No |
| mercury | Mercury | 13.6 | 0.8 | 20 | 0.0 | 1.0 | Yes |
| poison | Rat Poison | 1.5 | 0.7 | 20 | 0.1 | 0.3 | Yes |
| lava | Lava | 3.1 | 2.0 | 1200 | 0.8 | 10.0 | Yes |
| sludge | Radioactive Sludge | 1.8 | 0.9 | 40 | 0.6 | 0.5 | Yes |
| bleach | Bleach | 1.1 | 0.3 | 20 | 0.7 | 0.8 | Yes |
| acid | Acid | 1.4 | 0.3 | 25 | 0.9 | 3.0 | Yes |

---

## 18. Usage

1.  Open the application. A glass of beer is displayed at 100 per cent fill level.
2.  Tilt the device backward. The glass tilts in proportion to the device angle. The beer level decreases. Bubbles rise. Ice cubes slide toward the low side.
3.  Tilt beyond 35 degrees. Liquid spills from the glass. A puddle accumulates on the virtual bar surface.
4.  Select a different liquid from the grid at the top of the screen. The glass refills partially with the new liquid. Existing liquid remains but is diluted.
5.  Press the Ice button to add ice cubes (3 cubes per press, maximum 40 cubes).
6.  Press the Trash button to remove all ice cubes.
7.  Press the Refill button to restore the glass to 100 per cent of the currently selected liquid, reset the spill meter and add new ice cubes.

### Liquid Combinations

| Combination | Behaviour |
|-------------|-----------|
| Beer + Whiskey | Irish car bomb. Density-stable layering. |
| Lava + Mercury | Mercury boils at the bottom. Lava cools at the density boundary. |
| Sludge + Bleach | Reaction bubbles intensify to sludge bubble rate plus bleach increment. |
| Milk + Piss | Layered by density difference (milk at 1.03, piss at 1.01). Aesthetically problematic. |
| Acid + Ice | Ice melts at melt rate 3.0. Acid bubbles at rate 0.9. |
| Coffee + Tea | Temperature-differential thermal layering. Both hot. |
| Wine + Water | Dilution. Density similar. |
| Poison + Any | Toxic flag activated. Skull indicator displayed. |

---

## 19. Disaster Recovery

### Post-Deletion Glass Restoration

In the event the glass state is lost (level reaches zero or the browser tab is refreshed), recovery is immediate and manual:

1.  Detect empty glass.
2.  Press the Refill button.
3.  State resets to initial conditions: level = 100, spill danger = 0, contents = current liquid at 100 per cent, spill puddle removed.
4.  New ice cubes are generated.

**Recovery Time Objective:** Less than 1 second (single button press).
**Recovery Point Objective:** The last refill. State is not persisted between sessions.

### Cabin Fire, Flood or Government Seizure

In the event of catastrophic loss of the development cabin:

1.  The paper records (requirements, pseudocode, audit, build verification) stored in the fireproof safe are recoverable unless the fire exceeds the safe's rated temperature tolerance of 843 C for 30 minutes.
2.  Source code is recoverable from the GitHub repository and from any local copy that exists outside the cabin.
3.  The physical key (USB device) in the safe is recoverable under the same conditions.
4.  If the safe is lost entirely, the memorised private key fingerprint is still held by the developer. A new key can be generated and the repository signing authority can be re-established through a signed statement confirming the key transition.
5.  The generator can be replaced. Fuel supply is unaffected by cabin loss.
6.  A new workstation can be sourced from any second-hand electronics vendor. The compiler bootstrap procedure (Section 5) must be repeated on any replacement machine to re-establish the trusted toolchain. This is expected to take approximately 30 days.

---

## 20. Long-Term Maintenance

### Maintenance Window

iBeer 2026 will be maintained for the expected operational lifetime of the development workstation (estimated: 10-15 additional years, given the machine's age and the availability of replacement IDE hard disks from surplus stock).

Beyond this period, maintenance cannot be guaranteed. The developer notes that the application is functionally complete, contains zero dependencies and requires no external services. It will continue to function without maintenance indefinitely on any browser that supports the W3C DeviceOrientation API.

### Package Registry Collapse

In the event that the primary distribution channel (GitHub) becomes unavailable, iBeer 2026 remains distributable through:

- Direct peer-to-peer file transfer over encrypted USB media
- Printed source code (the file is 31,520 bytes; approximately 1,300 printed pages at 24 lines per page, which is impractical but possible)
- Inclusion in any archival data hoard that preserves the file

The project has no dependency on package registries, and their collapse would not affect existing installations.

### Long-Term Storage Format

The source code is stored in plain text (UTF-8 encoded HTML). Plain text is the most durable known digital storage format. It is readable with any text editor, requires no specialised decoding software and can be printed and re-transcribed if necessary.

---

## 21. Formal Rejection of AI and Cloud Computing

The development of iBeer 2026 explicitly rejects the following:

1.  **Large language models.** No code in this repository was written, suggested, completed or modified by any language model. The developer considers language model output to be statistically plausible plagiarism without understanding, and therefore unsuited to any project that demands genuine comprehension of its own behaviour.

2.  **Code assistants.** No autocomplete, Copilot, TabNine, CodeWhisperer or similar tool was enabled during development. The developer typed every character of every line without suggestion or completion. This includes comments.

3.  **Search-engine access.** No Internet search was performed during any stage of development. The mathematics were reconstructed from nature (Section 3). The programming knowledge required to implement the logic predates the development period and was acquired before the cabin existed.

4.  **Stack Overflow.** The developer has not visited Stack Overflow since 2017. The design decisions in iBeer 2026 were reached independently.

5.  **Cloud services.** No cloud computing resource was involved in development, testing, building or verification. The application itself makes no network requests. The concept of "the cloud" is architecturally irrelevant to this project.

6.  **Continuous integration.** The repository has no CI/CD pipeline. Automated testing would require a machine running tests, which would expand the development infrastructure beyond what is necessary or acceptable.

7.  **Package managers.** `npm`, `pip`, `gem`, `cargo` and similar tools have never been used in this project's development environment. The concept of transitive dependencies is considered an architecture failure.

8.  **Binary package downloads.** No precompiled binary has been executed on the development workstation. Every tool was compiled from source code that the developer has read.

---

## 22. Roadmap

### Q4 2026

- Ice-to-liquid ratio feedback. Real-time dilution tracking with GDPR-ICE compliance dashboard readout.
- Multi-tap support. Independent simulation of multiple beverages in separate glass instances.
- Temperature-aware glass condensation. CSS water droplets whose appearance is influenced by liquid temperature and ambient humidity.
- Sound effects. Pour, sip, spill and clink sounds via the Web Audio API (fully local, no network access).

### Q1 2027

- Enterprise SSO integration. A login screen prompting for credentials that are never transmitted to any server. Authentication is impossible and that is the point.
- Backward compatibility with RFC 2549. Carrier pigeon support with quality-of-service classification for enterprise deployments requiring avian transport guarantees.
- WebAssembly port. Ice physics running at sub-microsecond granularity. Target: 280 FPS cube update rate.
- AR mode. Overlay simulated glass on real-world surfaces using WebXR.

### Q2 2027

- RFC submission to the IETF. Zero Trust Beverage Architecture (ZTBA-2026) proposed as an Informational RFC documenting the inter-liquid trust model.
- ISO 42069 certification renewal. The self-certification is extended for another year.
- Feline verification programme expansion. Seeking additional contributors for quality assurance. Interested cats should report to the development cabin for evaluation. Mittens' approval is required.

### Geological Scale

- Cenozoic Era compatibility. Target: simulation runs on early primate neural hardware. Estimated delivery: mid-Miocene.
- Post-quantum ice cube security. Anticipating the impact of Shor's algorithm on CSS gradient rendering.
- Interstellar beverage deployment. The HTML file is to be included on any generation ship departing Earth as a cultural heritage artifact.

---

## 23. Contributing

### Requirements

1.  Every line contributed must be hand-written. No AI-generated code, no Copilot completions, no GPT suggestions. If your contribution was assisted by a large language model, it will be rejected. The Provenance Chain must remain unbroken.

2.  No build tools may be introduced. If your contribution requires a package manager, dependency resolver or build step, it is architecturally incompatible with this project.

3.  No telemetry or network functionality may be added. The application has zero data egress and that is the governing design constraint.

4.  No machine-translated documentation. Pull request descriptions must be written by humans. We do not accept PRs generated by language models.

5.  Cat verification is preferred. Contributors are encouraged to involve their own cats in testing. If your cat purrs during ice physics verification, note this in the pull request description.

### Code of Conduct

1.  Do not spill the glass.
2.  Do not launch glass across your keyboard.
3.  Ice cubes are thermodynamic entities whose dignity must be respected.
4.  Lava is dangerous. Mercury is very dense. Rat poison is labelled clearly.
5.  Treat all ice cubes with the dignity afforded by the Geneva Convention on Humane Ice Cube Treatment, Article 4.
6.  The cat's verification is final.
7.  No emoji in commit messages or code comments.

---

## 24. License

### ICE-WARE v1 -- iCe bEverage End-User License

    ICE-WARE LICENSE v1.0 (ICE-WARE)

    Copyright (C) 2026  sloptop-the-terrible

    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the BEVERAGE),
    to deal in the BEVERAGE without restriction, including without limitation
    the rights to use, copy, modify, merge, publish, distribute, sublicense
    and/or sell copies of the BEVERAGE, subject to the following conditions:

    1. The above copyright notice and this permission notice must be included
       in all copies or substantial portions of the BEVERAGE.

    2. THE BEVERAGE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
       EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
       MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-MISUSE OF
       THE BEVERAGE FOR SIMULATING LAVA IN A GLASS HELD BY A MINOR. IN NO
       EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
       DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT
       OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE BEVERAGE
       OR THE USE OR OTHER DEALINGS IN THE BEVERAGE, INCLUDING BUT NOT
       LIMITED TO:

       a) Spilling the BEVERAGE on a keyboard.
       b) Simulating mercury consumption.
       c) Confusing the BEVERAGE with a real beverage.
       d) Tilting too far while holding a real beverage.
       e) The Samsung advertisement.
       f) Cat-related injuries sustained during verification.
       g) Carrier pigeon ownership disputes arising from RFC 1149 transport.
       h) Emotional attachment to simulated ice cubes.
       i) Standards compliance audits triggered by fictional ISO numbers.

    3. This license is GPL-compatible in the sense that GPL stands for
       "Glass Promotion License" and this project endorses the promotion
       of transparent beverage containers.

    4. ICE cubes distributed under this license must retain their cubic
       shape unless melted by lava or other high-temperature beverage
       simulations.

    5. MITTENS CLAUSE. Any feline contributor who sat on the keyboard
       during a build verification session is entitled to perpetual treats
       and chin scratches. This clause is enforceable by purr.

    6. CARRIER PIGEON CLAUSE. Any avian carrier used for document transport
       under RFC 1149 must be provided with adequate rest, hydration and
       seed-based compensation. Pigeon waybills must be retained for the
       lifetime of the project (geological scale). Pigeon retirement plans
       are the responsibility of the pigeon.

---

## 25. References

### Internet Engineering Task Force

- RFC 2324. Hyper Text Coffee Pot Control Protocol (HTCPCP/1.0). April 1998.
- RFC 7168. The Hyper Text Coffee Pot Control Protocol for Tea Efflux Appliances. April 2014.
- RFC 1149. Standard for the Transmission of IP Datagrams on Avian Carriers. April 1990.
- RFC 2549. IP over Avian Carriers with Quality of Service. March 1999.
- RFC 6214. Adaptation of RFC 1149 for IPv6. April 2011.
- RFC 3092. Etymology of "Foo". April 2001.

### International Organization for Standardization

- ISO 3103. Tea -- Preparation of liquor for use in sensory tests. 1980.

### Project-Internal Standards

- ISO 42069. Sovereign Glass Tilt Management. Self-published. 2026.
- ISO 9001.5. Quality Management for Projects Too Small for ISO 9001. Self-published. 2026.
- RFC ICE-01. Deterministic Cube Placement Protocol. Self-published. 2026.
- RFC GLASS-02. Transparent Beverage Container Interoperability. Self-published. 2026.
- GDPR-ICE. General Drink Refrigeration Protocol. Self-published. 2026.
- NIST SP 800-CUBE. Secure Ice Lifecycle Management. Self-published. 2026.
- ZTBA-2026. Zero Trust Beverage Architecture. Self-published. 2026.
- Geneva Convention, Article 4. Humane Ice Cube Treatment. Referenced. 1949/2026.

### Privacy Regulation

- Regulation (EU) 2016/679. General Data Protection Regulation.
- California Consumer Privacy Act. Cal. Civ. Code ss 1798.100--1798.199.100.
- ISO/IEC 27001. Information security management systems. 2022.

### Computing

- Johnson, S. C. (1978). "A Portable C Compiler." Bell Laboratories. CACM.
- Stallman, R. (1984). GNU Coding Standards. Free Software Foundation.
- Joy, B. (1991). Vim 5.3 Reference Manual. Bram Moolenaar.

### Ecological

- Wolf territory spacing and collision avoidance behaviour observed at approximately 59 degrees north. Field notes. 2024.
- Pine cone restitution coefficient. Pinus sylvestris drop test. 2025. Cabin archives.
- Rainwater meniscus curvature in steel containers. Qualitative observation. 2025.

---

**iBeer 2026** -- A sovereign beverage simulation platform. No data leaves the glass because there is no data and barely a glass. Originally specified on paper, derived from nature, transcribed in isolation, verified by a cat.
