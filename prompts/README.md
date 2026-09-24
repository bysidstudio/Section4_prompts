# Section 4 Prompts

XML versions of the Brand Strategy Presentation prompts.

## Naming correction

Any reference to **"1.2 Business Goals"** should read **"1.2 Brand Goals"**.
This applies to this prompt and all prompts added to this folder going
forward.

## Format

Each prompt keeps a real `<inputs>` block (`brand_discovery_brief`,
`evidence`, `approved_pages`) that you paste content into per run. That's
the part XML tagging actually earns its keep on, separating data Claude
reasons from from the instructions it obeys. Everything below `<inputs>`
is compact instruction text, not further broken into one-line-per-tag XML,
since that doesn't change how reliably Claude follows it.

## Files

- `4.1-brand-purpose.xml` - Page 4.1 Brand Purpose
