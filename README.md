# Get recommended by AI

A system for getting a B2B software company named when a buyer asks an AI tool which software to use.

When someone asks ChatGPT, Claude, Perplexity, Gemini, or Google's AI mode which software to pick, this is about making sure your company is in the answer, and described for the right reasons. 

Some people call this AEO, answer engine optimisation. Others call it GEO, generative engine optimisation. 

## Why this matters now

Buyers have changed where they start. As of mid-2026, G2's 2026 buyer research says about half of B2B software buyers now begin research with an AI chatbot more often than with Google, and that share is still rising. Nearly nine in ten say AI search has changed how they research.

The part that should get your attention: G2 reports that most buyers ended up shortlisting a vendor they did not start with, and a third bought from a company they had never heard of before an AI recommended it. The shortlist is being written before anyone reaches your website.

## The one idea

When a buyer asks an AI which software to use, the AI rarely reads your website first. It reads what other people say about you.

For B2B software that means review sites like G2 and Capterra, comparison and alternatives pages, third-party "best tool for X" lists, product documentation, and community threads. The AI gathers those, works out which companies fit the question, and writes a shortlist.

So getting recommended is mostly work that happens away from your own site. Your job is to be present, consistently described, and easy to quote across the places the AI reads. Then to make your own pages easy to extract when the AI does reach them.

Two things follow from that:

- It is earned, not bought. There is no file or setting that makes an AI recommend you.
- It is slow. Retrieval-based surfaces like Perplexity and Google's AI mode update in days or weeks. The behaviour built into chat models changes more slowly than that.

## What's in here

The `system/` folder holds the working files.

- `01-how-ai-recommends.md`: how answer engines choose which software to name, and what moves the result. Read this first.
- `02-your-entity.md`: one clear description of your company, used the same way everywhere. A template to fill in.
- `03-questions-buyers-ask.md`: the real questions your buyers type into AI, and the ones you want to win. A template to fill in.
- `04-where-to-appear.md`: the sources AI reads, in rough order of weight for B2B software, with the action for each.
- `05-make-your-pages-answerable.md`: how to write your own pages so an AI can quote them.
- `06-measure.md`: a monthly check across the main AI engines, so you can see whether any of this is working.

The `example/` folder shows the whole system filled in for Ficti, a made-up B2B company that sells AI-native CSRD and ESG reporting software. Start at `example/output/current-vs-target.md`.

The `teardown/` folder does the opposite. It reads a real company that AI already recommends, Tally, to show what good looks like on something you can check yourself.

## How to use it

1. Read `system/01-how-ai-recommends.md` so the rest makes sense.
2. Fill in `02-your-entity.md`. This is the description you will reuse everywhere.
3. Fill in `03-questions-buyers-ask.md`. These are the answers you are trying to win.
4. Work through `04` and `05`, off-site first, then your own pages.
5. Set up `06-measure.md` and run it once now, to get a starting point.

## What this is not

This does not make an AI recommend you next week. Nobody can promise that, and anyone who does is selling something.

It also will not fix a product that buyers do not rate. AI leans on what real customers say. If the reviews are thin or unhappy, the honest fix is upstream of anything in this repo.

Results differ by engine and by category, so treat the measurement file as the source of truth for your own case, not the general claims above.
