# Dennis_kiplagat_EPL
Class assignment week 5 analysis of English Premier league(EPL)

**Clutch Threat Index (CTI): A Decision‑Support Tool for EPL Match Strategy**
**Project Overview**
This project proposes the creation of a Clutch Threat Index (CTI) — an analytics tool designed for an English Premier League club to quantify how attacking players perform in high‑leverage match situations. Instead of relying on traditional stats like goals and assists, CTI measures a player’s impact when the match state is most critical (e.g., tied or trailing by one goal after the 70th minute).

The tool would help managers and analysts identify which players consistently create value under pressure and should be prioritized for late‑match substitutions, tactical adjustments, or contract decisions.

**Decision‑Making Problem**
Premier League managers frequently face late‑match decisions:

Who should be subbed on when chasing a goal

Which attackers maintain performance under pressure

Which players shrink or thrive in high‑stress match states

How to allocate minutes among forwards and attacking midfielders

Currently, these decisions rely heavily on intuition, narratives, or basic stats that ignore context. The CTI tool addresses the strategic question:

“Which players consistently create high‑value actions when the match is on the line?”

**Proposed Analytics Approach**
The analysis would use:

Event‑level data (Opta-style): shots, key passes, carries, pressures, xG, xA

Match state variables: score differential, time remaining, possession zone

Win Probability Added (WPA) adapted for football

High‑leverage filters:

70th minute or later

Match tied or trailing by ≤1

Possession in attacking third

CTI would combine these into a single index that ranks players by their ability to influence match outcomes in pressure moments.

**Use by Decision Makers**
Managers, analysts, and sporting directors would use CTI to:

Guide late‑match substitutions

Identify “impact subs” who consistently change matches

Support recruitment decisions for players with proven clutch profiles

Communicate insights to coaching staff in a simple, intuitive format

The dashboard would present:

Player CTI scores

High‑leverage xG/xA contributions

Pressure‑moment heatmaps

Recommended substitution patterns

**Connection to Chapter 7**
This idea is in the Creative Phase of the innovation framework.
At this stage, the goal is to:

Define the idea

Clarify the decision problem

Outline the analytics approach

Explain how decision makers would use it

**Prototype Enhancement**
The enhancement focuses on adding a Match‑Specific CTI Module that automatically generates a pre‑match “Clutch Threat Report” tailored to the upcoming opponent.

What is being changed
Incorporating opponent‑specific defensive tendencies

Adding matchup‑based CTI projections

Including a “Substitution Recommendation Engine” that suggests which attackers should be prioritized for late‑match minutes

Adding a simple red/yellow/green confidence indicator based on sample size and opponent style

Why this improves decision‑making
Managers often prepare differently depending on the opponent’s defensive structure.
This enhancement:

Makes CTI actionable for today’s match

Helps coaches plan substitution patterns before kickoff

Reduces friction by presenting analytics in a simple, intuitive format

Bridges the gap between raw analytics and real tactical decisions
