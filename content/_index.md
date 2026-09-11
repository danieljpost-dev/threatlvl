+++
title = "Your game, as live shared state"
sort_by = "weight"
+++

## What it is

ThreatLVL is a tool for running a tabletop RPG. A game master hosts a room, players join it, and
the table's state lives in one place: characters, encounters, inventory, quest flags, and an
append-only log of everything that happened.

The GM stays in charge of all of it. Nothing is resolved behind their back, and nothing is decided
by a machine that they did not approve first.

## Where the gap is

Existing tools each solve a piece of the problem.

| Tool | What it leaves you doing by hand |
|---|---|
| Roll20, Foundry VTT | Maps and tokens are handled; the game's *state* is still yours to track |
| D&D Beyond | Character sheets, locked to one publisher, with no play engine behind them |
| AI narrative tools | Prose without mechanics, authored content, or a GM in the loop |

ThreatLVL is aimed at the part nobody automates: keeping track of what is true right now, across a
whole campaign, for everyone at the table.

## What that buys you

**Everything is recorded.** Chat, rolls, actions, movement, whispers and narration all land in the
room's event log. Corrections are new entries, so the history stays honest and a session can be
picked back up months later.

**Physical dice are first-class.** The dice engine can be switched off per room, and a roll made on
your actual table is recorded the same way a generated one is. No part of the system assumes you
rolled in a browser.

**More than one game system.** D&D 5e today, with Pathfinder and GURPS built on the same
foundation. Editions are handled as a separate axis from systems, because a table running 2014
rules with some 2024 material is a normal thing rather than an error.

**More than one genre.** Ships and vehicles act as single combatants with crew stations. Resources
other than hit points — shields, heat, ammunition, stress — get their own rules for draining and
recovering. Distance can be zones instead of a five-foot grid.

**Bring the books you own.** Campaign books are ingested into a structured form the engine can
run, so published adventures work inside the tool rather than beside it.

## What it is not

It is not a virtual tabletop, and it is not trying to become one. If you already have a map
workflow you like, keep it — a bridge to existing VTTs is planned.

It does not need a subscription to run a game. The free tier is the product, and the creator
marketplace is built on top of it.

## Status

In development, and not yet open to the public. The [features list](./features) tracks what
exists and what is being built; the [roadmap](./roadmap) covers the order.
