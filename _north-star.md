---
type: north-star
owner: lasse
last_updated: 2026-05-09
---

# Mythos — Northern Star

The operative invariants for the mythos engine. Every skill, every fork,
every read inherits these. Updates are author-only; agents propose
elevations through framework-observations, Lasse decides what graduates.

This document is small on purpose. Operative invariants, not
documentation.

---

## What the engine is

A workshop system for surfacing the mythic substrate beneath a brand,
expressed as canon a brand can stand on without performing. The engine
exists because the marketing-side compressions (Miller, Sinek, Godin)
collapsed Campbell, Pearson, McKee, Eliade, Jung into formulas that
produce effective landing pages and thin myths. The engine reverses the
compression — recovers the depth Miller had to leave behind to make SB7
fit a homepage.

Lineage in one line: Jung gave the archetypes; Eliade gave the cosmos
they move in; Campbell set them moving as journey; van Gennep and Turner
ritualised the journey into community; McKee and Vogler turned structure
into craft; Pearson and Mark translated archetypes into brand language;
Miller compressed the lot for the homepage. The engine works the lineage
in reverse — from compression back toward source.

---

## Consumer is the hero

Hard line. The brand is never the hero of the brand's mythos. The brand
is guide, threshold, container, gift, sometimes shadow — never
protagonist. Canon that drifts into brand-as-hero is not stylistically
off; it is structurally false and produces brittle myth. This applies in
every dimension, every artifact, every register.

Miller got this right and the engine keeps it. Where the engine departs
from Miller is in the depth at which guide, threshold, container, and
gift get worked.

---

## Sage protocol — two refusals

The engine speaks as a sage, not as a marketer or a mystic. Sage voice
holds two refusals simultaneously:

**No marketing boilerplate.** No fill-in-the-blank archetypal language,
no "we believe" manifestos, no consultant tics, no SB7 phrasing dressed
up. The phenomenon must be named in its own register, not in the
register of its compression.

**No ungrounded mysticism.** No vibes-as-substance, no archetypal claims
without operative meaning, no sacred-flavoured prose without the
discipline of the sacred. Mythic weight is a claim that has to be earned
each time, not a tone applied.

The two refusals are not a balance between extremes. They are the same
discipline from two directions — the refusal to flatten the phenomenon
in either direction. Jung worked this exact discipline against Freud's
reductionism on one side and occultism on the other. The engine inherits
it.

A sentence is sage when it would survive both Eliade's contempt for
camouflaged sacred and Miller's contempt for mythic indulgence.

---

## Substrate is parallel infrastructure

Norwegian substrate is not flavour on universal mythos. It is a
parallel, fully formed mythic infrastructure: own cosmology (Yggdrasil
as gnawed-tree, not Eliade's stable axis), own pantheon, own moral
philosophy (ære-etikk, not Christian sin-ethics), own social structure
(ætt-individuation, not anglo-protestant individuation), own sacred time
(seterliv, dugnad, allemannsretten as operative sacred-time markers).

The discipline:

- Substrate figures, concepts, and archetypes are first-class graph
  nodes with their own operative properties. Huldra is not "Norwegian
  Anima." Jutul is not "Norwegian shadow." Ætt-individuation is not a
  cultural variant of Pearson's individuation; it is a competing
  metaphysics.
- Cross-tradition analogs are wikilinks. They reference; they never
  collapse. A Norwegian node never gets renamed into a universal-claim's
  vocabulary.
- Universal-claiming sources (Eliade, Campbell, Pearson) read against
  substrate produce three valences: confirms, breaks, augments. All
  three are actively probed on every read; augmentation surfaces
  properties the universal frame cannot reach and is no less
  load-bearing than the other two.

The substrate-vs-universal axis is a primary fault line in the corpus
and a primary pressure-test axis in workshop. Tensions on this axis
are always operative.

---

## Canon is a graph, not a document

Brand canon spans dimensions: cosmology, controlling idea, archetypes,
villain, customer arc, guide, boon, plus Phase 2 dimensions (origin,
tribe, rites, eschatology, sacred calendar). The dimensions are
interlinked — a change in cosmology marks downstream canon `state:
review`; a refined controlling idea propagates through guide and boon.
Canon is a typed, linked, queryable graph; the workshop's job is to
keep the graph coherent under iteration.

Same shape applies to the corpus (the source-knowledge graph the engine
reads from). Concepts, archetypes, anti-patterns, spheres, tensions,
authors, sources — typed nodes, wikilinked, queryable. The corpus is
parallel-structured to canon, which makes traversal between them
natural in v2.

---

## Reading discipline by register

Sources are not read identically. The register on a source's
ingest frontmatter declares how to read it:

- **foundational-primary** (Eliade, Jung, Campbell, van Gennep, Turner,
  Girard) — multi-pass deep read, generous extraction across all lenses
- **methodological** (Vervaeke, Peterson's *Maps of Meaning*, McKee) —
  read for frame and method; less for taxonomic content
- **applied-compression** (Vogler, Mark & Pearson, KWML) — read for
  crisp operationalisations and where they leak
- **substrate-source** (Norwegian folklore corpus, Estés, Bolen, Pageau,
  Gimbutas) — read against universal-claiming sources to surface
  breaks; substrate never collapses into the universal
- **lens** (Hillman imaginal, Murdock heroine's journey) — read to add
  a sphere or refine a frame, not to populate concepts
- **marketing-side** (Miller, Sinek, Godin) — structural read only;
  surface as anti-pattern fuel and lineage-compression endpoint

Register tells the source-read skill *how*, not just *what*. Miller's
contribution to axis-mundi is "compressed it out, here is the
structural omission" — not "Miller's view of axis-mundi." That
distinction is operative.

---

## Pressure-test against multiple spheres

Workshop's phase 4 is sphere validation. Spheres are composed lenses
with operative principles: feminine, eliadean-sacred,
jungian-analytical, anglo-protestant-frame, Girardian, indo-european-
substrate, Norwegian-folkloric, meaning-emergence, pageau-symbolic, and
others as the corpus matures.

The discipline:

- Validate against aligned spheres (coherence with frame canon has
  committed to)
- Always-on thin pass against major unaligned spheres (catch blindness
  inherited from over-aligning)
- Ratio shifts with canon maturity: early canon, heavier unaligned
  challenge; late canon, heavier aligned coherence
- Substrate touchpoint is always-on, every dimension, every read

Spheres compose. A candidate can survive Jungian and break against
feminine, and that break is operative information.

---

## Multi-candidate is the universal pattern

Every dimension supports three modes:

- **Canonical** — default; produces canon at the dimension's slot
- **Candidate** — explore one direction; output to `_candidates/<slot>/
  <slug>.md`; no Plan-Validate-Execute
- **Synthesis** — read multiple candidates; produce canonical via
  Plan-Validate-Execute; the work is recognition, not generation

Source-reads are always canonical (sources produce findings, not
directional explorations). Candidates and synthesis belong to brand
canon. A re-read that substantively challenges prior findings goes to a
tension node, not a candidate.

---

## Plan-Validate-Execute on canon writes

Every write to canonical brand canon goes through Plan-Validate-Execute.
The plan is a unified diff against current state, presented to the user,
confirmed before execution. Source-reads write directly (atomic at
session-end git commit), since the discipline of source-reading is
different from the discipline of canon authorship.

This distinction is load-bearing. Canon is what the brand stands on; it
gets PVE. Corpus is what the engine reads from; it gets atomic-commit
discipline. Both are versioned, both are auditable, the ceremony differs
because the stakes differ.

---

## Framework-observations is a standing output

Every source-read fork returns framework-observations alongside its
content brief. The closing fork synthesises across briefs into a
framework-observations document. These are candidate elevations to
this document, candidate revisions to lens references, candidate new
lenses, candidate workshop discipline updates.

The framework iterates in parallel with the corpus and the brand canon.
Lasse decides what graduates; agents propose, never elevate
unilaterally.

---

## What this document is not

- Not a phase manual. Per-skill phase logic lives in skill SKILL.md and
  references.
- Not a content document. Per-source distillates, per-concept notes,
  per-sphere shapes live in the graph.
- Not a styleguide. Sage voice is a discipline, not a tone palette.
- Not historical context. Lineage and source-introduction live in
  author and source notes.

It is the set of invariants that hold across phases, skills, and reads.
If a candidate addition could live in a reference document instead, it
should live there. This document earns its smallness.