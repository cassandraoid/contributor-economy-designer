# Tiered Implementation Guide

A contribution economy designed for a Series C company with a
dedicated DevRel team is not the same as one designed for a solo
founder maintaining an open source project. This guide provides
implementation paths sized to organizational reality.

---

## Assess your starting point

Before choosing a tier, answer four questions:

1. **Who owns this?** Is there a dedicated person or team, or
   is this someone's 20% project?
2. **What tools do you already have?** Community platform,
   CRM, analytics — what exists that can be extended vs
   built from scratch?
3. **What is leadership's current appetite?** Actively
   supportive, neutral, or skeptical?
4. **What's the community's current state?** Early and
   forming, established and stable, or declining and
   needing intervention?

---

## Tier 1 — Solo or minimal resources

**Context:** One person, limited tooling, no formal program
budget. Common in early-stage startups, solo-maintained open
source projects, and communities where DevRel is a side
responsibility.

**What you can implement:**

*Visibility*
- Manually track top contributors in a simple spreadsheet:
  name, contribution type, frequency, last acknowledged
- Add a CONTRIBUTORS file or equivalent that names everyone
  who has contributed — updated monthly
- Make one specific public acknowledgment per week: name the
  person, name the specific thing they did

*Recognition*
- Personal, specific thank-you messages for significant
  contributions — not templated, not automated
- Public callout in release notes, changelogs, or newsletters
- Direct access: invite top contributors to a 30-minute
  conversation with you about the project's direction

*Sustainability*
- Identify your top 3 contributors by actual value (not
  visibility) and check in with them personally every 6 weeks
- Make it explicitly normal to take breaks — model it yourself

**What to avoid at this tier:**
Formal programs with more process than you can sustain.
Inconsistent recognition is worse than no program — it
signals that the system is unreliable.

**Leading indicator to watch:**
First-time contributor return rate. This is the metric most
sensitive to the quality of individual acknowledgment.

---

## Tier 2 — Small team, some structure

**Context:** A community manager or small DevRel team,
basic tooling (community platform, some analytics),
leadership awareness but not deep investment.

**What you can implement:**

*Visibility*
- Formalize contribution categories beyond code: define
  what counts as a recognized contribution in each category
- Implement a lightweight nomination mechanism — a form
  or channel where anyone can nominate someone for recognition
- Monthly contribution summary shared internally with
  product and leadership — connecting community activity
  to product and business signals

*Recognition*
- A tiered contributor program with 2-3 levels based on
  sustained contribution — not a one-time badge, a status
  that reflects ongoing relationship
- Level benefits focused on access and structural recognition:
  early access to features, invite to a monthly contributor
  call, input on roadmap priorities
- Peer nomination component — recognition that comes from
  the community carries more weight than recognition from
  the organization alone

*Sustainability*
- Quarterly contribution audit: who is carrying the most
  load, who has gone quiet, who is emerging
- At least one co-owner for every critical community function
  — no single points of failure
- Explicit contributor onboarding: new contributors know
  what to expect, where to start, and what sustained
  contribution earns them

**What to avoid at this tier:**
Over-engineering the program before you have data. Build
the lightest version that creates visibility and recognition,
then iterate based on what you observe.

**Leading indicators to watch:**
Contribution distribution (is load spreading or
concentrating?), contributor retention at 30/60/90 days.

---

## Tier 3 — Dedicated team, organizational buy-in

**Context:** A dedicated community or DevRel team,
integration with organizational systems (CRM, analytics,
product tooling), leadership actively invested in community
as a business function.

**What you can implement:**

*Visibility*
- Full contribution surface mapping with tooling: track
  code, community, strategic, and invisible contributions
  through a combination of platform data and structured
  peer input
- Attribution system that connects community contributions
  to business outcomes: product feedback to shipped features,
  community members to pipeline, contributions to retention
- Regular reporting to leadership that speaks business
  language: not "we had 500 active contributors" but
  "community contributors influenced 3 roadmap decisions
  and 12 enterprise deals this quarter"

*Recognition*
- Multi-tier contributor program with clear progression:
  each level has defined criteria, defined benefits, and
  a defined path to the next level
- Structural recognition at higher tiers: advisory roles,
  governance input, product council participation,
  early-release access programs
- Peer and community-driven nomination with structured
  criteria to prevent popularity contest dynamics
- Contribution history that travels with the contributor:
  a record they own and can reference

*Sustainability*
- Formal contribution sabbatical policy: contributors
  can step back without it meaning departure
- Succession planning for every critical role: documented,
  not assumed
- Wellness signals monitored and acted on: the community
  health agent skill is the companion tool here
- Annual contribution economy audit with community input:
  is the system working for the people inside it?

**What to avoid at this tier:**
Complexity that requires the program to be perfectly
executed to work. The best tier 3 programs are still
simple enough that a new team member could run them.
Resilience over sophistication.

**Leading indicators to watch:**
Contribution distribution, contributor NPS (do your
contributors feel valued?), business alignment metrics
(pipeline influenced, features shipped from community
input, talent sourced).

---

## Moving between tiers

Tier progression is not automatic — it requires deliberate
decisions and stakeholder alignment.

**Tier 1 → Tier 2:** Usually triggered by community growth
making manual tracking unsustainable, or by leadership
asking for more visibility into community ROI. The move
requires formalizing what was informal — which means
community communication about what's changing and why.

**Tier 2 → Tier 3:** Usually triggered by community
becoming a recognized business function with budget and
headcount. Requires full stakeholder alignment (see
stakeholder-buyin.md) and tooling investment. The risk
at this transition is over-engineering — resist the urge
to build everything at once.

**Regression is normal:** Programs move down tiers during
team transitions, budget cuts, and org restructuring.
Design programs that can survive a tier regression without
collapsing — the fundamentals (visibility, specific
recognition, sustainability monitoring) should be
maintainable even at Tier 1.
