# Refcards

The atomic knowledge base of the Historiotheque: one concept per card,
tens of thousands of them, on anything.

## What a Refcard is

A Refcard is a single atomic unit of knowledge — a concept, definition, distinction,
quote, question, or method — captured on one physical index card and mirrored here
as one Markdown file. Refcards are universal: a card can be about anything, but it
must be atomic.

## The atomicity rule

One card = one concept. If a card needs the word "and" in its title, it is two cards.
Cards link; they don't contain. If a card wants to become an essay, the essay belongs
in a project's `theory/` directory, and the card becomes its pointer.

## Numbering

`RC-YYYY-NNNN` — e.g. `RC-2026-0001`. Sequential within the year; the year prefix
keeps every ID globally unique. IDs never change; titles may.

## Sharding

Cards live in `cards/RC-YYYY/RC-YYYY-NNNN.md` — one directory per year. If a year ever
exceeds ~2,000 cards, split into `RC-YYYY-A/`, `RC-YYYY-B/` thousand-blocks. Never put
tens of thousands of files in one directory.

## Physical cards

Each file records `physical_location` in its frontmatter (box and divider), so the
digital card always knows where its physical index card lives.

## Card types

`concept` | `definition` | `quote` | `question` | `method` | `reference` | `distinction`

## Status values

`seed` | `developing` | `stable` | `superseded`
