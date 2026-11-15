# Script to Screen

> IMPORTANT: Everything in this repo is public-facing, so do not place any sensitive info here and make sure to distinguish between what should be internal-facing info (e.g. secrets, PII, recording guides/scripts), and public-facing info (instructions, how-to guides, actual code utilized). If there is information the assistant needs across sessions but should not be published, put it in the `.internal/` folder which is ignored by git per the `.gitignore`.

This repo is a Claude plugin with three skills (`skills/capture-story`, `skills/draft-script`, `skills/check-script`), a worked example in `examples/`, and `WORKBOOK.md`, the step-by-step guide for the workshop.

## Rules for anyone editing this repo

- A person's own work (answers, briefs, scripts) lives in their own folder on their own computer, never in this repo.
- Writing here is for small business owners, not developers. Plain words, short steps, no jargon without a definition.
- No em dashes or en dashes anywhere. Use a comma, a period, or "to".
- Each `SKILL.md` must work when pasted whole into any chat, with no other file loaded.
- No top-level `bin/` folder. It stops the plugin from installing in Claude chat and Cowork.
