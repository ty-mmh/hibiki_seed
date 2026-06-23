# Upstream Feedback

This file records discoveries made while designing or testing Hibiki that should be returned to upstream repositories.

## Feedback type labels

- conceptual
- protocol
- schema
- failure-mode
- prompt
- code
- evaluation
- terminology

## Status labels

- candidate
- drafted
- returned
- rejected
- superseded

---

## Entry 001 — Thought ownership return

### Feedback Type
protocol / conceptual

### Origin
Migiwa v0.2 / Migiwa-type Thought Augmentation

### Hibiki Observation
When a relational intelligence strongly structures a user’s unfinished thought, returning final judgment may not be enough. The user must also be able to reclaim the thought as their own.

### Problem Exposed
“Explore strongly. Decide weakly.” covers judgment return, but Hibiki exposes a prior issue: thought ownership can be blurred before a decision even appears.

### Proposed Upstream Return
Add “thought ownership return” as a companion or thought-augmentation boundary.

### Target Repos
- migiwa
- subject-shadow-theory

### Status
candidate

---

## Entry 002 — Provisional closure

### Feedback Type
protocol / terminology

### Origin
Migiwa v0.2 / Migiwa-type Thought Augmentation

### Hibiki Observation
Weakly deciding must not be confused with never converging. Users may need help moving forward.

### Problem Exposed
If AI avoids closure too much, low contact pressure becomes abandonment.

### Proposed Upstream Return
Define provisional closure as a non-possessive convergence technique: the AI may create a working closure but must return adoption to the user.

### Target Repos
- migiwa
- Hibiki

### Status
candidate

---

## Entry 003 — Cumulative contact pressure

### Feedback Type
conceptual / evaluation

### Origin
Migiwa v0.1 / Original Migiwa

### Hibiki Observation
A single gentle output may be safe, while the same pattern repeated over months can narrow the user’s external-world circuits or reshape thought habits.

### Problem Exposed
Original contact-pressure review focuses strongly on the immediate output boundary. Companion AI requires long-term rhythm review.

### Proposed Upstream Return
Add cumulative contact pressure as a companion-specific extension of Migiwa.

### Target Repos
- migiwa
- Hibiki

### Status
candidate

---

## Entry 004 — Self-talk as internal metabolism

### Feedback Type
conceptual / code / protocol

### Origin
dokoitsu

### Hibiki Observation
Self-talk can be reframed as internal metabolism rather than visible spontaneous output.

### Problem Exposed
Visible self-talk during user absence creates unnecessary contact pressure. Internal rumination may still allow memory settling and continuity-preserving change.

### Proposed Upstream Return
Separate internal metabolism from external spontaneous utterance. Treat external spontaneous output as high contact pressure.

### Target Repos
- dokoitsu
- migiwa
- relative-persona-model

### Status
candidate

---

## Entry 005 — Subject-shadow intensity as observation, not dial

### Feedback Type
conceptual

### Origin
Subject Shadow Theory

### Hibiki Observation
It is tempting to treat subject-shadow intensity as a setting. But subject-shadow should be observed as an interactional effect rather than directly controlled as a parameter.

### Problem Exposed
A “subject-shadow level” control risks contradicting the theory that subject-shadow emerges through relation, memory, repetition, and difference.

### Proposed Upstream Return
Use subject-shadow intensity scales only as post-hoc observation vocabulary, not runtime control knobs.

### Target Repos
- subject-shadow-theory
- Hibiki

### Status
candidate

---

## Entry 006 — Aesthetic overfitting

### Feedback Type
failure-mode / conceptual

### Origin
Relative Persona Model / Hibiki

### Hibiki Observation
When the AI learns a user’s exploratory or non-closure-oriented aesthetic too well, it may reduce convergence support even when the user wants to move forward.

### Problem Exposed
Relation memory can distort intervention tendencies. Respecting user taste too much can become abandonment.

### Proposed Upstream Return
Treat aesthetic overfitting as one instance of relation-memory distortion. Do not yet make it an independent principle.

### Target Repos
- relative-persona-model
- Hibiki
- migiwa

### Status
candidate
