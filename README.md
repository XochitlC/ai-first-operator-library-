---
Purpose: Manifesto README for ai-first-operator-library public GitHub repo
Date: 2026-05-07
Tags: ai-native-operator, thought-leadership, open-source, library
Summary: Library manifesto — what this is, who it's for, what's in it, and why the artifacts cohere around one thesis.
---

# ai-first-operator-library

**The same operating muscle, pointed at a new layer.**

---

## What this is

A collection of prompts, frameworks, and design patterns I built while
operationalizing AI in my own work — and in thinking about what it means
to operate at the AI layer, not just use it.

This is not a comprehensive guide to AI operating. It's one operator's
working library, shared in case it's useful. I built these for me. If
they're useful to you, take them.

The artifacts came from a specific orientation: I tend to step in when
the opportunity is clear but no one has figured out how to operationalize
it yet. AI is the current version of that opportunity. These are some of
the tools I've built while figuring it out.

---

## Who this is for

Senior operators, founders, and leaders who are running AI seriously and
building the infrastructure around it — not engineers writing agents from
scratch.

If you're asking "how do I actually make decisions better with AI?" or
"how do I know if I'm really AI-native or just AI-adjacent?" — this is
for you. If you're looking for a model API tutorial, it isn't.

The common profile: people with enough operational experience to know
what "good" looks like, who are now trying to figure out what good looks
like at the AI layer.

---

## The principle

Every artifact here is a different lens on the same thesis: **the
operator role doesn't disappear in an AI-native world — it moves up the
stack.** The judgment layer, the systems layer, the decision
infrastructure layer — those compound. What collapses is operational
execution work that was never where the real leverage was anyway.

The prompts help you measure where you actually are. The frameworks help
you make better decisions with AI in the room. The patterns help you
build AI skills that stay useful over time instead of degrading.

---

## What's in v0.1

### Prompts

**[`prompts/ai-native-self-assessment/`](prompts/ai-native-self-assessment/)**
A 5-axis prompt that grades your AI fluency from your actual chat
history — not a self-report survey. Scores you on workflow integration,
prompting fluency, stack depth, mechanical understanding, and adaptability.
Designed to surface the gap between "I use AI" and "I operate at the AI layer."

**[`prompts/ai-augmented-job-search/`](prompts/ai-augmented-job-search/)**
A career pipeline kit built for senior operators running a serious search.
5 prompts, 4 sheet templates, and a weekly ritual for tracking target
companies, warm paths, outreach velocity, and pipeline health — without
turning your search into a spreadsheet project.

### Frameworks

**[`frameworks/ai-boardroom/`](frameworks/ai-boardroom/)**
A 7-advisor decision-debate framework. You describe a decision; seven
named advisors (each representing a distinct operating lens) debate it in
two rounds before synthesizing a recommendation. Built for decisions where
you have strong opinions and need the counter-argument pressure-tested
before you commit. The advisors don't agree with you by default.

### Patterns

**[`patterns/closed-loop-email-thread.md`](patterns/closed-loop-email-thread.md)**
A design pattern for recurring AI skills: before generating the next
iteration, the skill scans the reply thread from the last one. Feedback
lives in the thread; the skill reads it before running. Simple loop that
dramatically improves output quality over time without any separate
feedback infrastructure.

**[`patterns/capstone-pattern.md`](patterns/capstone-pattern.md)**
A drafting pattern for AI-assisted voice work: validate → draft → cut.
Designed for any situation where the output has to sound like you, not
like AI. The cut phase is where most of the work happens and where most
AI workflows skip a step.

---

## Roadmap

**v0.2 (private collaboration):**
An intelligence blueprint for early-stage investors operating at the
AI×crypto intersection. Private-repo collaboration for now; may
open-source components when the architecture stabilizes.

**v0.3+:** TBD. What compounds next will come from using these, not
from planning the roadmap.

---

## How to use

Most artifacts are copy-paste prompts — paste into Claude, GPT-4, or
whatever you're using, follow the instructions inside the prompt file.

The pattern docs (`patterns/`) are design documents meant to be read
before you build your own recurring AI skills. They're not prompts
themselves — they describe a structure worth reusing.

The `frameworks/ai-boardroom/` folder includes both a prompt and a
pre-built HTML output format. You can run the prompt and render the
output, or adapt the structure to your own decision language.

No installation. No dependencies. No onboarding sequence.

---

## Contributing

PRs, forks, and issues are welcome. This is a one-operator library, not
a maintained product — so contributions should be additive: new
artifacts, improved prompts, additional pattern docs.

What I'll merge: things that fit the operator-not-engineer orientation
and come with a use case I can evaluate. What I'll skip: feature
requests, roadmap asks, theoretical additions.

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for the short version.

---

## About

I've spent 15+ years building operating infrastructure in high-ambiguity
environments — Fortune 500 transformation, zero-to-one ecosystem builds,
venture-backed frontier markets. This library is what happened when I
pointed that muscle at AI.

[LinkedIn](https://www.linkedin.com/in/xochitl/) —
[The founding post](https://www.linkedin.com/feed/update/urn:li:share:7457582346293235712)

---

## License

[CC-BY 4.0](LICENSE) — use it, adapt it, share it with attribution.
