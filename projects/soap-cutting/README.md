# SoapCutting

**A personal Roblox pet project by Arseni Atrokhov, built with AI coding tools.**

The published game is **[NEW] +1 Knife Size Every Cut**.

**[Play on Roblox](https://www.roblox.com/games/102709455340707)** · [Developer profile](https://github.com/CondrusArsen)

## What you can play

The current public version combines a short expedition with incremental progression:

**train → throw a knife → cut soap → escape the foam → process the haul on a raft → upgrade equipment**

The public description lists knife and equipment progression, four districts, soap mutations, geodes, server events, daily goals and raft processing. The public place was checked on 10 November 2026. It is an early pet project under active development, rather than evidence of a commercially successful game.

## My contribution

I initiated the project and assembled it using Claude Code and Codex. I define the gameplay and progression, set implementation tasks, work through client and server scripts, direct UI and visual iterations, playtest builds and request fixes.

Most implementation code was generated and iterated with AI assistance. My earlier hand-written Luau is available separately in [Roblox Feature Pack](https://github.com/CondrusArsen/roblox-feature-pack/tree/original-2025).

## How the game is organised

| Area | Implemented scope |
|---|---|
| Gameplay | Knife flight and boosts, per-player cutting state on a shared course, a moving foam threat and return with the haul |
| Progression | Equipment, districts, workshop recipes, collection and mastery systems |
| Client | Input, camera, gameplay feedback, HUD and shop presentation |
| Server | Authoritative progression and reward checks, movement validation, player state and persistence |
| Workflow | Luau modules, versioned design contracts, automated rule checks and Roblox Studio playtests |

These are descriptions of the project and documented development checks. They do not certify every current live path, purchase flow or device.

## Published version and redesign

**Published build:** the expedition and raft loop described above.

**Current development:** a redesign of the cutting interaction and first session. The new direction focuses on a more direct cutting gesture, clearer short-term goals and a simpler introduction. This work is not presented as already published or as a measured retention improvement.

The separate ASMR experiment in development and the collaborative [Fish & Survive: Zombie Lake](https://www.roblox.com/games/134519178428493) are different projects.

## A development decision

**Problem:** the existing first session introduces throwing, mining, escape and processing before the central cutting interaction has become clear.

**Decision:** prototype a more direct cutting interaction and reduce the number of ideas introduced at once.

**Verification plan:** check whether a new player can identify the first action, complete one useful cycle and explain the next upgrade. Compare behaviour in playtests before making claims about retention.

This is a development hypothesis, not a claimed commercial uplift.

## Evidence and limits

- The public Roblox page confirms the playable project and its listed features.
- The local October B23 delivery records document a two-client check of independent cutting/inventory state and escape outcomes, plus mobile-emulator UI checks. These are historical development checks, not a fresh certification of the current live build.
- The November redesign is in progress; its results and live player impact are not yet established.
- Commercial growth, reliable mobile-device performance and revenue outcomes are not claimed.
- This repository section is a portfolio case study. The full editable place, internal production notes and account configuration are not distributed here.

## Review another kind of work

[Roblox Feature Pack source](https://github.com/CondrusArsen/roblox-feature-pack) · [Deep Contract playable and design notes](https://github.com/CondrusArsen/deep-contract) · [CV](../../cv/Arseni_Atrokhov_Game_Prototyper_EN.pdf)

[Contact on LinkedIn](https://www.linkedin.com/in/arseni-atrokhov/)
