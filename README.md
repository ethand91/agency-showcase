# Agency Showcase — The UwU Ecosystem

This repository showcases a growing set of projects exploring **persistent AI characters that can exist across multiple digital environments**.

The common direction is bigger than a single VTuber app: shared identity, memory, relationships, voice, embodiment, autonomous action and environment-specific capabilities.

## Core projects

| Project | Role in the ecosystem |
|---|---|
| [vtube-agency-hq](https://github.com/ethand91/vtube-agency-hq) | AI VTuber production, streaming and agency control plane |
| [vr-uwu](https://github.com/ethand91/vr-uwu) | VRChat embodiment and social-world experiments |
| [UwU-Chan-Discord](https://github.com/ethand91/UwU-Chan-Discord) | Community personality, voice, memory, games and moderation |
| [UwU-Employee](https://github.com/ethand91/UwU-Employee) | Embodied AI coworker, meetings, grounded memory and presentations |
| [UwU-Minecraft](https://github.com/ethand91/UwU-Minecraft) | Autonomous world agents, planning, learning and multi-agent coordination |
| [UwU-Desktop-Pet](https://github.com/ethand91/UwU-Desktop-Pet) | Ambient desktop presence and character interaction |
| [uwu-chan](https://github.com/ethand91/uwu-chan) | Local-first developer/tool-use agent |
| [UwUSNS](https://github.com/ethand91/UwUSNS) | Synthetic social-network and multi-agent society experiments |
| [UwU-Filter](https://github.com/ethand91/UwU-Filter) | Realtime webcam / visual transformation experiments |

## The idea

> **One identity. Many bodies.**

Rather than building unrelated chatbots for every platform, the long-term architecture is a reusable talent/agent core with adapters for each environment.

```text
                    SHARED TALENT / AGENT CORE
 identity • persona • memory • relationships • mood • events
                 planning • permissions • intent
                              │
      ┌───────────┬───────────┼───────────┬───────────┐
      ▼           ▼           ▼           ▼           ▼
 Agency HQ     Discord     Employee     VRChat     Minecraft
 production   community     work      embodiment    action
      │
      ├──────── Desktop Pet  → ambient presence
      ├──────── uwu-chan     → developer/tool use
      ├──────── UwUSNS       → social simulation
      └──────── UwU-Filter   → realtime media
```

Open `ecosystem.html` for the dedicated ecosystem showcase page.
