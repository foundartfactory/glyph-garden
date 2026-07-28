# Design Record

**Project:** Glyph Garden  
**Language:** Grammar of the Seasons  
**Document Version:** 0.1.0  
**Status:** Draft

---

## Purpose

The Design Record documents significant decisions that shape the evolution of the Grammar of the Seasons.

Unlike the Geometry Specification, which describes the language as it currently exists, the Design Record explains why the language came to exist in that form.

Each record captures the context, reasoning, and consequences of a design choice.

Together, these records form the historical memory of the project.

---

# Philosophy

Design decisions are part of the language.

Recording why a decision was made is often more valuable than recording the decision itself.

Future contributors should be able to understand the reasoning behind the Grammar without reconstructing its history from commit messages or discussions.

---

# Record Format

Every Design Record follows the same structure.

```text
Identifier

Title

Status

Context

Decision

Rationale

Consequences

Related Documents
```

Records should remain concise.

Whenever possible, each record should address a single question.

---

# Status Values

Design Records may have one of the following states.

### Proposed

An idea under active discussion.

No change to the Grammar has yet occurred.

---

### Accepted

The decision has become part of the project.

Relevant documentation should reflect the change.

---

### Superseded

A newer Design Record replaces this decision.

Historical context should be preserved.

---

### Withdrawn

The proposal was intentionally abandoned.

Withdrawn records remain valuable as documentation of explored alternatives.

---

# Initial Records

---

## DR-0001

### One New Concept Per Plate

**Status:** Accepted

#### Context

Construction Plates are intended to teach the Grammar incrementally.

Introducing multiple major concepts simultaneously makes it difficult to understand which ideas contribute to later discoveries.

#### Decision

Each Construction Plate introduces exactly one significant geometric concept.

#### Rationale

Small, isolated steps make the language easier to learn, critique, and extend.

#### Consequences

Construction Plates remain focused and composable.

Future Plates should assume previously established concepts without redefining them.

#### Related Documents

- Constitution
- Geometry Specification
- Construction Plates

---

## DR-0002

### Grammar Before Vocabulary

**Status:** Accepted

#### Context

The project began with the goal of creating seasonal glyphs.

Early discussions revealed that a coherent construction language was more valuable than a collection of finished illustrations.

#### Decision

The Grammar shall be developed before expanding the Vocabulary.

#### Rationale

A stable Grammar enables consistent growth.

Without it, each new glyph risks becoming an isolated design exercise.

#### Consequences

Documentation precedes implementation.

Patterns are adopted gradually through repeated success.

#### Related Documents

- Design Brief
- Geometry Specification
- Pattern Library

---

## DR-0003

### Discover Forms. Don't Invent Them.

**Status:** Accepted

#### Context

A central question emerged during early exploration:

Should Glyph Garden create arbitrary decorative forms, or uncover forms implied by the Grammar itself?

#### Decision

Design work should prioritize discovering forms that emerge naturally from the Grammar.

#### Rationale

The strongest solutions appear inevitable rather than arbitrary.

This philosophy encourages coherence while allowing the language to evolve organically.

#### Consequences

Experiments focus on revealing latent possibilities within existing structures before introducing new concepts.

#### Related Documents

- Constitution
- Pattern Library
- Geometry Specification

---

# Writing Design Records

A Design Record should be created whenever a decision:

- changes the Grammar,
- introduces a new foundational concept,
- modifies an existing Pattern,
- alters construction methodology,
- changes project philosophy,
- affects future contributors.

Minor editorial improvements should not require a Design Record.

---

# Relationship to Other Documents

The Design Record complements every technical document in the repository.

Specifications describe the language.

Construction Plates explore it.

Patterns preserve successful discoveries.

Design Records explain why those discoveries became part of the project.

---

> *Discover forms. Don't invent them.*

---

**Status:** Draft

**Version:** 0.1.0
