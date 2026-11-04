# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS/JS with no build step and no dependencies, shipped as an installable PWA (manifest.json + sw.js, offline cache). Hosted on GitHub Pages: https://guiguibaena123-eng.github.io/impostor/ (repo guiguibaena123-eng/impostor, branch main).

## Users

Families of all ages, from children to grandparents, playing together in person. One phone is passed from hand to hand around a table, a sofa, or a car. Every word has to be something everyone at the table knows.

## Product Purpose

"Impostor" is a Portuguese (pt-BR) party word game. Every player secretly receives the same word except the impostor(s). Players take turns saying one clue word, then discuss and vote. If the impostor is caught, they get one last chance to guess the word. Success means a fast setup, secrets that never leak while the phone is passed, and rounds that start again with no friction.

## Positioning

It runs on one device and needs no accounts, no internet, and no installation from an app store. It gives curated, family-safe words in pt-BR, with Brazilian categories.

## Operating Context

The game is played in person and out loud, and the phone travels between hands. Each player looks at the secret alone and hides it before passing the phone on. The screen is usually seen at arm's length in mixed lighting, in living rooms at night and outdoors. Short sessions are played in repeated rounds with a running scoreboard.

## Capabilities and Constraints

- Players: at least 3, saved in localStorage. There can be 1 or more impostors, capped at floor((n-1)/2).
- Discussion timer with pause, +30s, and a beep and vibration at the end.
- Optional hint: the impostor sees the category name.
- Voting is done out loud, and the result is entered on the device. With several impostors, voting continues until all are caught or an innocent is accused.
- Scoring: crew +1 each for a catch, impostor +2 for guessing the word after being caught, impostor +3 for escaping.
- Word bank: 20+ categories with roughly 150–250 well-known, family-safe words each (quality over quantity, confirmed by the user). Categories the user requires: Football and teams, Movies/series/games, Brazil. The rest are curated freely.
- Words used recently are not repeated until the pool runs out.
- Must keep working offline and stay installable.

## Brand Commitments

- Name: "Impostor". UI language: pt-BR.
- The user made the palette binding: sky blue, cloudy white, and amber red as the base colors.
- The user made the aesthetic binding: minimalist, futuristic, sophisticated, with very carefully crafted details.
- Categories need their own dedicated interface.

## Evidence on Hand

There are no testimonials, metrics, or press. Do not invent any.

## Product Principles

1. The secret never leaks: every handoff makes privacy obvious and deliberate.
2. Anyone can play: legible at arm's length, with no jargon and words a child and a grandparent both know.
3. Zero friction between rounds: the next round is always one tap away.
4. The device is the game master: it holds the state so people can look at each other, not the screen.

## Accessibility & Inclusion

The game is played by all ages, including children and older adults. That means large text, large touch targets, and strong contrast. Respect reduced-motion preferences.
