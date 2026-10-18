# OpenMeshTak

**Self-hosted TAK server with Meshtastic for events.** Open source provisioning, mission authoring and mission distribution for ATAK, iTAK, WinTAK and Meshtastic radios.

An administrator defines an event once. OpenMeshTak works out each participant's identity, team and
role and hands them exactly what they need: a working TAK connection, Meshtastic radio settings and
the event's map data. Participants don't have to understand certificates, server settings, channels,
PSKs or mission package layouts.

- **Events, roles and groups** with participants added by hand or synchronized from other systems
- **Built-in TAK server** with certificate enrollment, Data Package access and CoT streaming
- **Meshtastic profiles** with per-member settings, channels and secret handling
- **Mission map editor** in the browser that publishes ATAK Data Packages
- **API-first:** the Web app, SDK and your own portals or bots all use the same public REST API
- **Self-hosted** with Docker Compose, no cloud vendor required

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/OpenMeshTAK/.github/main/profile/assets/event-live-dark.webp">
  <img src="https://raw.githubusercontent.com/OpenMeshTAK/.github/main/profile/assets/event-live-light.webp" alt="Live view of a fictional demo event: TAK apps and Meshtastic nodes on the event map, grouped by team">
</picture>

📖 **[Documentation](https://openmeshtak.github.io/openmeshtak-docs/)** · [Self-hosted TAK server](https://openmeshtak.github.io/openmeshtak-docs/tak-server) · [ATAK with Meshtastic](https://openmeshtak.github.io/openmeshtak-docs/atak-meshtastic)

## Repositories

| Repository | What it is | License |
| --- | --- | --- |
| [openmeshtak](https://github.com/OpenMeshTAK/openmeshtak) | Core API server and backend | AGPL-3.0-only |
| [openmeshtak-web](https://github.com/OpenMeshTAK/openmeshtak-web) | Web app for participants, administrators and mission editors | AGPL-3.0-only |
| [openmeshtak-sdk](https://github.com/OpenMeshTAK/openmeshtak-sdk) | TypeScript/JavaScript SDK, on npm as [`@openmeshtak/sdk`](https://www.npmjs.com/package/@openmeshtak/sdk) | Apache-2.0 |
| [openmeshtak-docs](https://github.com/OpenMeshTAK/openmeshtak-docs) | Documentation site | CC BY 4.0 |

Core, Web and SDK are released together under one version.

## Getting started

- [Install OpenMeshTak](https://openmeshtak.github.io/openmeshtak-docs/installation/)
- [Set up an event](https://openmeshtak.github.io/openmeshtak-docs/events/)
- [Connect your apps as a participant](https://openmeshtak.github.io/openmeshtak-docs/participants/)
- [Use the API](https://openmeshtak.github.io/openmeshtak-docs/api/) or the [SDK](https://openmeshtak.github.io/openmeshtak-docs/sdk/)
