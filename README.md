# write-like-yourself

**Teach your AI editor what you would keep, change and delete — using your own writing and corrections.**

I started noticing the same problem when editing event messages: every paragraph was trying to sound clever. After months of correcting drafts, I realized those corrections were more useful than a prompt saying "write naturally." They contained actual editorial judgments — including when a sentence should be left alone.

This repository turns that practice into a simple, reusable workflow. No training, API keys or code required.

## Start in five minutes

**[START HERE →](START-HERE.md)**

Copy the starter prompt into your AI assistant, paste some writing and a few corrections, then review the proposed guide. You can start provisionally with just **two texts and one correction**. If you've already done that, use the ready-made prompts to [write](prompts/write.md), [edit](prompts/edit.md) or [review](prompts/review.md).

## Optional agent skill

Agents that support the [Agent Skills format](https://agentskills.io/specification) can read [`skills/write-like-yourself/SKILL.md`](skills/write-like-yourself/SKILL.md). It provides **BUILD / WRITE / EDIT / REVIEW / EVALUATE** modes and loads references as needed. It is optional: the plain Markdown prompts still work with any assistant. The skill is not automatically installed by cloning the repository; follow your agent's skill-directory instructions.

## See the method with real examples

The [Spanish-language Borja case study](examples/borja/README.md) contains original excerpts, verbatim feedback, coedited document comparisons and a working voice guide. Start with the [step-by-step walkthrough](examples/borja/before-after.md), then explore the [source excerpts](examples/borja/corpus.md).

Want to see the difference in practice? [Guess which version used the guide](DEMO.md). **Those pairs are teaching demonstrations, not an independent model benchmark.**

## What's inside

| File | Use |
| --- | --- |
| [START-HERE.md](START-HERE.md) | A single copyable prompt to start | 
| [skills/write-like-yourself/SKILL.md](skills/write-like-yourself/SKILL.md) | Optional agent skill |
| [templates/VOICE.template.md](templates/VOICE.template.md) | Editable template for your own voice |
| [prompts/build-your-voice.md](prompts/build-your-voice.md) | A structured analysis workflow |
| [prompts/write.md](prompts/write.md) | Draft a new piece |
| [prompts/edit.md](prompts/edit.md) | Edit an existing draft with restraint |
| [prompts/review.md](prompts/review.md) | Review without rewriting |
| [EXAMPLES.md](EXAMPLES.md) | Evidence labels and documentation |
| [EVALUATION.md](EVALUATION.md) | How to run a fairer comparison |
| [DEMO.md](DEMO.md) | A/B illustration, answers hidden below |

## Why the evidence labels matter

An author's original writing, direct feedback, a coedited document and an AI proposal are not interchangeable. This project asks you to label them so your assistant doesn't take a proposed rewrite as a preference you endorsed.

A voice guide should capture **decisions**, not repeated catchphrases. It should learn why you delete a metaphor, preserve an imperfect sentence, or prefer concrete stakes. It must not invent details, impersonate other people's writing or treat a single sample as an immutable rule.

## Privacy, language and limits

Review samples for private messages, company secrets and identifying information before posting them. Use material you have the right to share. Your private `VOICE.md` is ignored by Git by default; don't commit private samples to public paths.

The framework is written in English for reuse, but the case study stays in Spanish. Create and maintain your own guide in the language you write in.

This repository is not a trained model or an automatic memory system. It won't guarantee an indistinguishable voice; you still need to review each draft. [Evaluation protocol](EVALUATION.md).

## Accompanying article

The article **«Cómo conseguí que una IA escribiera como yo»** is available as a separate draft. Add its public URL here once published; no URL is fabricated.

## License and attribution

Templates, prompts and project documentation are available under [MIT](LICENSE). Excerpts in the `examples/borja/` case study are attributed to their author and provided for commentary and analysis. Don't assume that those excerpts are granted for unrestricted reuse merely because the tooling is MIT-licensed; ask the author before republishing substantial portions elsewhere.
