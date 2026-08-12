# CLAUDE.md

Instructions for an AI assistant helping someone use this repo.

## What this repo is for

Helping a B2B software company get recommended when a buyer asks an AI which software to use. The work is mostly off-site presence plus making the company's own pages easy to quote.

## Before you write anything

Read these two files first, every time:

- `system/02-your-entity.md`: the one description of this company. Use it exactly. Do not invent a new tagline, category, or one-liner. If it is empty, help the user fill it in before doing anything else.
- `system/03-questions-buyers-ask.md`: the questions the company wants to win. Anything you draft should help answer one of these.

## When the user asks you to check AI visibility

Use the prompt set in `03-questions-buyers-ask.md` and the method in `06-measure.md`. Report, for each question: whether the company is named, where it sits in the list, whether the description is accurate, which sources are cited, and which competitors appear. Do not guess. If you cannot run the check, say so and set it up for the user to run.

## When the user asks you to draft a page

Follow `05-make-your-pages-answerable.md`. Lead with a direct answer. Use clear headings that match how buyers ask. Include a table, an honest "who it is not for", and a real price if there is one. Name sources for any number.

## Writing rules

- Keep the company described the same way everywhere. Same name, same category, same one-liner.
- Plain sentences, one idea each.
- Sentence case headlines.
- British and EU English.
- No em dashes.
- Numbers instead of adjectives.
- Do not claim the company is recommended by any AI unless the measurement file shows it.

## What not to do

- Do not suggest tricks. No keyword stuffing, no fake reviews, no llms.txt as a shortcut. See the last section of `01-how-ai-recommends.md`.
- Do not promise fast results. This is slow, earned work.
