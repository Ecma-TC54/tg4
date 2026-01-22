# Software and system transparency - OSS Sustainability (TC54-TG4)

This repository contains information for the [Software and system transparency - OSS Sustainability Task Group (TC54-TG4)](https://www.tc54.org/contributing-yaml/).

See [Scope](#scope) for our mandate.

<!-- Scope, POW copied from https://ecma-international.org/task-groups/tc54-tg3/ -->

## Contributing

All community members are welcome to participate. Because we are working on a specification that we seek to standardize, individuals making technical contributions must agree to Ecma's IPR agreements. The usual way of doing that is by becoming a delegate of an Ecma member or, in certain cases, being invited as an Invited Expert. If you are interested, please join us at a meeting, in the slack channel, or by creating an issue here.

### Meetings

Meetings occur every other Thursday and appear on the [OWASP calendar](https://calendar.google.com/calendar/u/0/embed?src=c_884decde5a152902bb51a62f89550d0f3748484534f08c63792f2e654f2a7ebc@group.calendar.google.com).

- [Join meeting](https://teams.microsoft.com/meet/22488847526639?p=vhuF4GKC0B8yPthzjf)
- [Agenda](https://hackmd.io/hx-pkNLCT-mUBmHF-kLKFA)

<!-- DST below -->

<!-- ### Every other Thursday

|              |       |
| -----------: | ----- |
| US / Central | 12:00 |
|          UTC | 17:00 | -->

<!-- not DST below -->

#### Every other Thursday

|              |       |
| -----------: | ----- |
| US / Central | 12:00 |
|          UTC | 18:00 |

### Chat

We use Slack room [#workstream-oss-sustainability](https://cyclonedx.slack.com/archives/C072WMNML75) in the [OWASP CycloneDX workspace](https://cyclonedx.org/slack/invite).

### Folks

- Convenors
  - [Chris de Almeida](https://github.com/ctcpip)
  - [Piotr P. Karwasz](https://github.com/ppkarwasz)
- Members
  - [Lauriane Mollier](https://github.com/LaurianeOSE)
  - [Salve J. Nilsen](https://github.com/sjn)
  - [Steve Springett](https://github.com/stevespringett)

## Scope:

Ecma TC54-TG4 is chartered with the standardization of Contributing JSON, an open contributions specification to enable the structured and machine-readable communication of an open source community’s or project's state, needs, and support intentions. This includes codifying maintainers’ support levels, signalling calls for assistance, identifying abandonment or handoff status, and improving visibility into whether a project is viable for commercial or long-term use. The Contributing JSON specification aims to support software supply chain risk assessment, organisational investment decisions, and community sustainability efforts.

### Objectives

- **Standardise Project State Signalling:** Define a consistent taxonomy and data model for expressing open source project states and support levels.
- **Enable Contributor Discovery and Matching:** Provide a machine-readable structure for signalling specific contributor needs, enabling ecosystem tools to match volunteers and organisations with maintainers’ requests.
- **Improve Risk and Investment Transparency:** Empower downstream users and ecosystem hosts to make informed decisions regarding project viability, maintenance, and sustainability through clear and accessible metadata.
- **Support Ecosystem Intervention:** Define statuses and mechanisms to support trusted ecosystem actors in situations where maintainers are unreachable or projects are abandoned.
- **Align with Existing Specifications:** Ensure compatibility with CycloneDX, PURL, VERS, TEA, and other emerging standards relevant to the software supply chain and SBOM use cases.

## Programme of work:

1. Define and publish the **Contributing JSON Specification** including a taxonomy of project states, maintainer signals, and support levels.
1. Define and publish a **standard file format and location** to convey this information, with versioning and support for monorepos and website URLs.
1. Define mechanisms for **external references** (e.g., SBOM linkages, URL references to FUNDING.md, issue tracker tags, etc.).
1. Specify a **framework for trusted assertions** of project state by third parties (e.g., ecosystem hosts).
1. Publish **best practices** for maintainers, ecosystem platforms, and tool developers for adoption and integration of OSS sustainability metadata.
1. Explore and define **governance considerations** for privacy-sensitive contexts and signals (e.g., unresponsive maintainers, mental health concerns, or project succession plans).
1. Develop a reference **prototype implementation** for generating, validating, and consuming sustainability metadata.
