# Software and system transparency - Contributing JSON (TC54-TG4)

<!-- Scope, POW copied from https://ecma-international.org/task-groups/tc54-tg3/ -->

## Scope:

Ecma TC54-TG4 is chartered with the standardization of Contributing JSON, an open contributions specification to enable the structured and machine-readable communication of an open source community’s or project's state, needs, and support intentions. This includes codifying maintainers’ support levels, signalling calls for assistance, identifying abandonment or handoff status, and improving visibility into whether a project is viable for commercial or long-term use. The Contributing JSON specification aims to support software supply chain risk assessment, organisational investment decisions, and community sustainability efforts.


**Objectives**

* **Standardise Project State Signalling:** Define a consistent taxonomy and data model for expressing open source project states and support levels.
* **Enable Contributor Discovery and Matching:** Provide a machine-readable structure for signalling specific contributor needs, enabling ecosystem tools to match volunteers and organisations with maintainers’ requests.
* **Improve Risk and Investment Transparency:** Empower downstream users and ecosystem hosts to make informed decisions regarding project viability, maintenance, and sustainability through clear and accessible metadata.
* **Support Ecosystem Intervention:** Define statuses and mechanisms to support trusted ecosystem actors in situations where maintainers are unreachable or projects are abandoned.
* **Align with Existing Specifications:** Ensure compatibility with CycloneDX, PURL, VERS, TEA, and other emerging standards relevant to the software supply chain and SBOM use cases.


## Programme of work:

* Define and publish the **Contributing JSON Specification** including a taxonomy of project states, maintainer signals, and support levels.
* Define and publish a **standard file format and location** to convey this information, with versioning and support for monorepos and website URLs.
* Define mechanisms for **external references** (e.g., SBOM linkages, URL references to FUNDING.md, issue tracker tags, etc.).
* Specify a **framework for trusted assertions** of project state by third parties (e.g., ecosystem hosts).
* Publish **best practices** for maintainers, ecosystem platforms, and tool developers for adoption and integration of OSS sustainability metadata.
* Explore and define **governance considerations** for privacy-sensitive contexts and signals (e.g., unresponsive maintainers, mental health concerns, or project succession plans).
* Develop a reference **prototype implementation** for generating, validating, and consuming sustainability metadata.
