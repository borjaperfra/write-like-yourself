# How to document an editorial decision

Each example records **what happened**, not a generalized preference invented after the fact.

```yaml
id: EX-001
date: YYYY-MM-DD
channel: article  # article | short-post | email | chat | video
evidence: EXPLICIT_FEEDBACK
author_of_original: person
original: "..."
revision: "..." # omit if no approved revision
revision_status: approved # approved | proposed | unknown
feedback: "..." # quote exact feedback if available
editorial_principle: "..."
source_note: "article draft / conversation; private link if applicable"
```

## Evidence strength

1. Published text or edits explicitly approved by the author.
2. Direct, verbatim feedback on a draft.
3. Unpublished original writing.
4. Coedited documents, where approval is unclear.
5. Suggested edits awaiting approval.

An `AUTHOR_ORIGINAL` example can show a characteristic voice even without a revision. A `COEDITED_COMPARISON` can show a useful editing technique, but should **not** be represented as the author's approved change.

## Good analytical note

“‘Decidir realmente’ became ‘decidir qué poner en producción’: the latter points to the reader's actual deployment decision.”

## Weak analytical note

“The author likes short, punchy lines.” This is too vague without evidence and may fail in long articles.
