+++
title = "About"
description = "Who builds ThreatLVL, and the principles it is built on."
weight = 4
+++

# About

ThreatLVL is an independent project, built in Rust, currently in development.

## Principles

**The GM is always in the seat.** Every design decision resolves in favour of the person running
the game. Automation exists to spare them bookkeeping, never to take a ruling out of their hands.

**Optional means optional.** Dice, maps, voice recording, virtual-tabletop bridges and the GM
assistant are all subsystems that can be compiled out. A build without any of them has to work
properly, and that is checked rather than assumed.

**Small on purpose.** The reference hardware is a Raspberry Pi 400. Every layer is measured under
load as it is built, and the capacity of the platform is whatever the weakest layer can sustain.
Working within that constraint keeps the system honest.

**One place for the rules.** All game logic lives in a single engine library. Interfaces render it;
they never reimplement it. Two frontends can never disagree about how a rule works.

**Systems and editions are different things.** A game system is one axis, an edition is another.
Two systems do not mix at a table; two editions frequently do, so editions are modelled as
differences from a base rather than as separate copies of the rules.

## Content and licensing

Game content is used under the licences its publishers granted. D&D 5e material comes from the
System Reference Document under Creative Commons Attribution 4.0. Pathfinder material uses the
ORC licence. Anything outside those licences is gated behind explicit per-book handling.

Authors who publish through ThreatLVL keep their intellectual property. The platform licenses
their work for distribution and play, and nothing more.

## Status

Not yet generally available, and there is no sign-up. The [features list](../features) tracks what
exists today; the [roadmap](../roadmap) covers what comes next.

Technical documentation lives separately, at
[docs.threatlvl.com](https://docs.threatlvl.com).
