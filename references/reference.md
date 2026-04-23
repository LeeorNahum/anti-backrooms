# Anti-Backrooms Design Reference

This file expands the core skill with a deeper model of what "Backrooms wrongness" means in AI-generated artifacts.

## Why The Backrooms Metaphor Works

The Backrooms are not frightening because every pixel is impossible. They are frightening because the environment is almost normal while violating deeper expectations:

- the space is familiar but not placeable
- objects repeat without purpose
- rooms are segmented but not meaningfully organized
- scale feels off even when nothing is obviously broken
- navigation exists but does not produce confidence
- the world seems assembled from averages of real places rather than from one real place

That is exactly how many AI outputs fail.

AI often produces:

- correct local syntax with wrong global intent
- valid components with invalid composition
- reasonable words with unreasonable placement
- polished visuals with no believable human path
- internal context accidentally sucked into the public artifact

The result is not pure hallucination. It is coherent-but-wrong. That is the Backrooms failure class.

## Mapping Backrooms Phenomena To AI Failures

### Randomly segmented rooms

Backrooms: the space is cut into partitions that do not feel planned around real activity.

AI parallel:

- cards, sections, dividers, and content blocks appear because "that is what artifacts have," not because the structure serves the user
- a document gets sectioned into generic chunks with no information architecture
- a slide deck gets split into too many micro-sections that feel procedurally generated

What to do:

- ask what each segment accomplishes
- merge sections that do not create a new decision, proof, or transition
- prefer fewer, more intentional zones

### Mono-yellow sameness

Backrooms: the environment is unvaried in a way that feels oppressive rather than coherent.

AI parallel:

- repeated card styles with no hierarchy
- repeated wording rhythms
- repeated UI blocks with no emphasis
- design that is consistent but dead

What to do:

- keep consistency, but introduce deliberate hierarchy
- vary density, scale, emphasis, and rhythm intentionally
- use repetition only when it clarifies pattern recognition

### Endless hum-buzz

Backrooms: constant ambient noise creates low-grade stress.

AI parallel:

- too much low-value text
- every area saying something, but nothing truly leading
- many small labels, pills, helper lines, and footnotes competing at once

What to do:

- reduce ambient explanatory noise
- reserve words for what changes the viewer's understanding
- make the artifact quieter so the signal can dominate

### Non-Euclidean geometry

Backrooms: the space connects in ways that are locally navigable but globally impossible.

AI parallel:

- the artifact has an order, but that order does not resolve
- main story and appendix bleed into each other
- a page seems to conclude, then restarts a new conceptual branch
- a flowchart reads in loops or multiple contradictory directions

What to do:

- verify the global path, not just local transitions
- identify where the artifact should end emotionally and structurally
- separate mainline from optional branches

### Wrong scale

Backrooms: proportions often feel too wide, too long, too tall, too empty, or too compressed.

AI parallel:

- text sized for the canvas rather than the audience
- whitespace that feels luxurious on a monitor but wasteful in print
- diagrams with nodes that look balanced on-screen but collapse when projected
- table plans that ignore actual human sightlines and reach distance

What to do:

- evaluate the artifact in the intended medium
- ask viewing-distance questions explicitly
- size for use, not for aesthetic abstraction

### Duplication / replacement

Backrooms: areas look similar-but-not-the-same, as if one room was regenerated imperfectly.

AI parallel:

- sections restate each other with slightly different wording
- multiple slides express the same beat
- cloned UI modules drift from one another without reason
- a deck has duplicate proof, duplicate market framing, or duplicate CTA moments

What to do:

- collapse duplicates aggressively
- ensure each repeated structure earns its place
- if two parts are both necessary, differentiate their jobs clearly

### Observer effect / shifting geometry

Backrooms: things seem stable while being observed, but coherence breaks under movement or time.

AI parallel:

- an artifact survives a static skim but breaks when you imagine actually using it
- a slide looks good until you think about projection distance
- a website looks good until you consider click order
- a booth plan looks good until you imagine people physically gathering around it

What to do:

- simulate use, not just appearance
- walk through the artifact mentally
- inspect transitions, handoffs, and real interaction sequences

## The Biggest AI Mistakes This Skill Should Catch

### 1. Surface-first design

The artifact looks designed before it is reasoned.

Symptoms:

- pretty gradients covering weak hierarchy
- polished cards covering weak content strategy
- decorative patterns added before resolving user flow

### 2. Placeholder logic shipped as real logic

The model uses scaffolding as if it were final structure.

Symptoms:

- generic headings that survived into final output
- project-internal labels exposed publicly
- builder notes turned into product copy

### 3. Good-enough-for-now maze-making

The agent knowingly creates a poor structure hoping to repair it later, then keeps building on top of it.

Symptoms:

- temporary sections becoming permanent
- a shaky deck path accumulating more slides
- a weak page hierarchy gaining more components rather than being reset

If the maze is wrong, do not decorate it. Rebuild the maze.

### 4. Context contamination

The artifact pulls in nearby material simply because it was present in the local context window.

Symptoms:

- unrelated terminology leaks into user-facing copy
- a visual artifact inherits structure from a nearby but different artifact
- the model confuses process context with product context

## High-Value Questions To Ask Mid-Generation

- If I remove this section, does the artifact get clearer?
- Is this element here for the user, or because models tend to put one here?
- Would a stranger understand why this is included?
- Is this text readable at the actual presentation, print, or use scale?
- Did the artifact already resolve before this section appeared?
- Did I accidentally bring internal context into a public-facing surface?
- If this were a real room, would the placement still make sense?

## Strong Correction Patterns

### Reset the path

When the artifact feels like an impossible corridor:

- define the true start
- define the true end
- map the minimum number of beats in between
- cut anything that is not on the main path or clearly marked as appendix or reference

### Re-ground the artifact in physics

When scale or placement feels abstract:

- specify viewer distance
- specify device size or print size
- specify whether the artifact is scanned, projected, held, skimmed, or navigated
- resize and reprioritize based on those constraints

### Re-ground the artifact in audience

When content feels contaminated or generic:

- identify the real audience
- remove anything they would never need to see
- replace process labels with audience-relevant meaning

### Re-ground the artifact in purpose

When repetition or decorative noise takes over:

- state the job of the artifact in one sentence
- justify every section against that job
- delete anything whose role cannot be defended quickly

## What Good Feels Like

An artifact passes this skill when:

- it feels intentionally composed rather than statistically assembled
- the viewer knows where to look and why
- the structure resolves cleanly
- scale matches real usage
- nothing internal or accidental leaks out
- the artifact is believable as something a careful human would have chosen to make
