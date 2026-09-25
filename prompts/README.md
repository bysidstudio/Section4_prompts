# Section 4 Prompts

XML versions of the Brand Strategy Presentation prompts.

## Naming correction

Any reference to **"1.2 Business Goals"** should read **"1.2 Brand Goals"**.
This applies to this prompt and all prompts added to this folder going
forward.

## Format

These prompts run inside one ongoing chat, not as isolated per-call
templates. You paste the Brand Discovery Brief and Evidence once near the
top of the conversation, then run each page's prompt (4.1, 4.2, 4.3...) as
a new turn in that same chat. Every later prompt reads the brief, evidence,
and earlier approved pages straight out of chat history, so nothing gets
re-pasted per page. Instructions stay compact prose grouped by topic (role,
routes, voice, output format, etc.) rather than one XML tag per sentence,
since fragmenting instructions further doesn't change how reliably Claude
follows them, it just adds tokens.

## Files

- `4.1-brand-purpose.xml` - Page 4.1 Brand Purpose
- `4.2-brand-vision.xml` - Page 4.2 Brand Vision
- `4.3-core-values.xml` - Page 4.3 Core Values
- `4.4-brand-positioning.xml` - Page 4.4 Brand Positioning
- `4.5-value-proposition.xml` - Page 4.5 Value Proposition
- `4.6-brand-personality.xml` - Page 4.6 Brand Personality
- `4.7-brand-voice.xml` - Page 4.7 Brand Voice
- `4.8-key-messages.xml` - Page 4.8 Key Messages
- `4.9-brand-strategy-summary.xml` - Page 4.9 Brand Strategy Summary
- `strategy-check.xml` - Strategy Check: audits a PDF export of Sections
  01-04 for high-impact problems before Creative Direction. Different
  shape from the page prompts: it doesn't write brand copy, it reads an
  uploaded PDF and reports up to 3 fixable issues (first check) or
  fixed/still-open status against a prior report (recheck). No routes,
  no word-count fields.

Section 05 (Creative Direction) prompts, including Core Creative Idea,
now live in the separate `section5_prompts` repo.
