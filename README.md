# Practical AI workflow kits

<img src="assets/profile.jpg" alt="Thomas Musser" width="220" align="right">

I'm Thomas Musser, a Staff Data Scientist building small, opinionated tools for making AI-assisted work more reliable.

I got tired of cognitive debt: moving fast with AI, but ending up with work I could not fully explain, verify, or hand off.

These repos are my attempt to fix that.

**Core wedge**

Better specs, not bigger specs.
Plan Mode prevents premature edits. These workflows prevent premature agreement.
Context engineering is not about preserving more context. It is about preserving the right uncertainty.

**Start here**

**[ai-engineering-skills](https://github.com/tmusser/ai-engineering-skills)**

Portable skills for Claude Code, Codex, and coding agents. Use it when AI coding sessions drift, overbuild, lose context, or skip verification.

**[context-to-action-skills](https://github.com/tmusser/context-to-action-skills)**

Claude skills for turning messy workplace context into clear facts, asks, decisions, owners, risks, updates, and safe replies. Start with `/reduce-to-facts` when the source is too dense or ambiguous to act on safely.

**[chart-contract](https://github.com/tmusser/chart-contract)**

A Python library for claim-first analytical charts with audit trails, caveats, and provenance. Use it when AI-generated charts look polished but may be analytically weak.

<br clear="right">

## The pattern

Reduce messy context. Clarify the claim. Bound the work. Verify the result. Leave a handoff.

## Current focus

Improving adoption paths and proof examples for the AI workflow repos.
Sharpening `context-to-action-skills` around epistemic distillation: facts, uncertainty, claims, and next actions.
Building `chart-contract` as a concrete proof artifact for analytical integrity.

## Repo map

| Repo | Problem | First thing to try |
| --- | --- | --- |
| [ai-engineering-skills](https://github.com/tmusser/ai-engineering-skills) | AI coding work drifts, overbuilds, or skips checks | Compare [broken-vs-gated](https://github.com/tmusser/ai-engineering-skills/tree/main/examples/broken-vs-gated), then try mini-spec → scope-freeze → verify-contract |
| [context-to-action-skills](https://github.com/tmusser/context-to-action-skills) | Messy context does not become a clear decision path | Start with `/reduce-to-facts`, then move to clear-ask, decision-brief, status-update, or follow-up-draft |
| [chart-contract](https://github.com/tmusser/chart-contract) | Charts can look good while hiding weak claims or missing provenance | Build one chart with an explicit claim, caveat, and source trail |

These projects are intentionally small. The goal is not to automate judgment away; it is to make judgment easier to apply.
