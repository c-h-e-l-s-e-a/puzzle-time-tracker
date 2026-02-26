# Puzzle Time Tracker

> _(for my own reference and remembering)_
>
> README -> “What is this and why should I care?” (primary statement; stable)
>
> Wiki -> “How am I thinking about this?” (expanded context; evolves with justification)
>
> Issues -> “What needs to be decided or done next?”


## Core purpose

This application is being made to track speed puzzling data and see trends over time using visualizations. I want to be able to see filtered data on, for example, specific puzzle time changes, trends for all puzzles of the same size, filter by number of sittings, and more to be considered in the visualizations.


## Motivation

TODO


## What it does (February 2026)

TODO


## Status

Early development (February 2026).


## How to run

TODO


## Tech stack

TODO


## Project Notes

See the Wiki for design decisions, background, and open questions.


## Information being tracked:

### Puzzle data:

- id
- title
- company identifier
- brand
- artist
- number of pieces
- year
- image (later)
- link to listing (later)

### Attempt data:

- id
- puzzle id
- build style (fast vs casual)
- single sitting?
- finished?
- sort time (can be empty)
- total time
- pieces per minute (PPM, calculated)
- remaining pieces (only relevant if not completed; could be used for remaining pieces at 2 h?)
- attempt number (not relevant if date present? calculated?)
- date
- notes

### Exercise:

- name
- description

### Exercise attempt:

- exercise id
- time
- date
- notes

### Data things to consider:

- how to handle individual vs pairs vs team attempts?
- how hard is it to update the schema later?