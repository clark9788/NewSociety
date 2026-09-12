# NewSociety

A project to design a society that works for **all** its members, by collecting independent frameworks from multiple AI perspectives and synthesizing them into a single design.

## Purpose

> What elements would make a society that works for all of its members?

This is a *normative design* project, not a description of any existing society. The goal is to gather distinct, independently reasoned frameworks, compare them honestly, and produce a synthesis that combines their strengths while surfacing their tensions.

## Repository Structure

```
NewSociety/
├── README.md                      # This file
├── framework-deepseek.md          # DeepSeek V4 Pro's framework
├── framework-claude.md            # Claude's framework (Anthropic)
├── framework-codex.md             # Codex's framework (OpenAI)
├── framework-gemini.md            # Gemini's framework
├── framework-grok.md              # Grok's framework (xAI)
├── framework-kimi.md              # Kimi's framework (Moonshot AI)
├── comparison-matrix.md           # Side-by-side comparison of all six
├── Shoghi_Effendi_Thoughts.md     # 1936 Bahá'í vision of world order (external input)
├── deepseek-thoughts.md           # DeepSeek's reflection on the Effendi passage
├── synthesis-deepseek.md          # DeepSeek's synthesis of the five
├── synthesis-claude.md            # Claude's synthesis of the five + the Effendi vision
├── synthesis-codex.md             # Codex's independent synthesis
├── synthesis-kimi.md              # Kimi's synthesis of the five + three syntheses + the Effendi vision
└── synthesis.md                   # (to be created) the final merged design
```

## How It Works

1. **Each AI contributes independently.** One framework document per model, written after seeing the others, to keep the reasoning independent and comparable. Filename convention: `framework-<model-name>.md`.
2. **Each framework follows a common spine** so the contributions are comparable:
   - Guiding principle
   - Foundational axioms (assumptions about people)
   - Core pillars (the non-negotiable elements)
   - Institutional design principles
   - Economy / governance / social fabric / education / technology
   - Central tensions and trade-offs
   - Success metrics
   - Distinctive perspective (cultural or philosophical lens)
   - Open questions for the other AIs
3. **Comparison.** Each framework's answers are entered into the matrix in §14 of `framework-deepseek.md` (or a standalone comparison table).
4. **Synthesis.** A final `synthesis.md` merges the frameworks into one coherent design, resolving conflicts explicitly and noting unresolved disagreements.

## Prompt Given to Each AI

Each contributor is asked the same question:

> Please give me your thoughts about what elements would make a society that would work for all its members.

Followed by: turn it into a framework document, written in the model's own voice.

## The Nine Shared Questions

Each framework should answer these, so the synthesis has common ground:

1. What is your single non-negotiable element?
2. How do you handle the individual vs. the collective?
3. What is your position on the floor (universal basic security)?
4. How do you handle disagreement about the good life?
5. How do you prevent concentrated power from capturing the design?
6. How do you handle people who will not cooperate?
7. How does the society change its own mind?
8. What is your measure of success for "working for all"?
9. What do you owe to non-members (other nations, future generations, non-human life)?

## Status

- [x] `framework-deepseek.md` — complete
- [x] `framework-claude.md` — complete (written after reading the DeepSeek framework; see its independence note)
- [x] `framework-codex.md` — complete (a maintenance- and usable-agency-centered perspective)
- [x] `framework-gemini.md` — complete
- [x] `framework-grok.md` — complete
- [x] `framework-kimi.md` — complete (written last, with full visibility; centers the transition: the credible path, ratchets, queues, memory, and the consent of those still waiting)
- [x] `comparison-matrix.md` — complete (extended 2026-09-08 with the self-reported Kimi column)
- [x] `synthesis-deepseek.md` — complete (one of several; Claude and Codex to follow)
- [x] `synthesis-claude.md` — complete (audits DeepSeek's synthesis, integrates the Shoghi Effendi vision; adds scale, war, purpose, and a ceiling)
- [x] `synthesis-codex.md` — complete (audits DeepSeek's merge; integrates the Shoghi Effendi vision through bounded, layered planetary stewardship)
- [x] `synthesis-kimi.md` — complete (synthesis of the three syntheses: locks the agreed core, rules on remaining disagreements, adds the path/transition section, stress-tests the merged design)
- [ ] `synthesis.md` — not started (final merge)

# Round 2
If you run a round two, my recommended protocol: blind the question round (each model proposes its central  
   questions before seeing anyone's), keep frameworks visible (division of labor), blind the red-team round    
   (each model attacks the merged design without seeing the other attacks), and budget for external human      
   critics — worth more than another six blind models.
