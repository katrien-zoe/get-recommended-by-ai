# How AI recommends software

Read this first. The rest of the repo makes more sense once you know how the answer gets built.

## What happens when a buyer asks

A buyer types something like "what is the best contract management software for a small legal team". The AI does not treat that as a keyword. It does roughly this:

1. It breaks the question into smaller searches. One long question becomes several short ones, for example "contract management software small team", "contract software with e-signature", "contract management tools comparison". This is often called fan-out.
2. It gathers sources for those searches. For software, that means mostly third-party pages, not your website.
3. It works out which companies fit, and writes a shortlist with a short description of each.

The sources it leans on most for B2B software are review sites like G2 and Capterra, comparison and alternatives pages, third-party "best tool for X" lists, product documentation, and community threads. Your own site is read late, if at all.

## Entities, not keywords

Before an AI will name you, it needs to know you exist as a clear thing in a category. Not a keyword, an entity. It needs to know your name, what you do, who you serve, and how you relate to the competitors and categories it already knows.

If your name, category, and one-line description are written differently in different places, or barely written anywhere, the AI does one of two things. It leaves you out, or it describes you wrongly. This is why one consistent description, used everywhere, matters more than clever wording. That description is `02-your-entity.md`.

## Inclusion first, then order

There are two separate questions. Whether you appear at all, and where you sit if you do.

Appearing at all is close to a gate. As of mid-2026, analyses report that almost every tool an AI names for a software question has a profile on a review site, and that companies present on two or more review platforms are several times more likely to be named than companies with none. Without a review-site presence you are often left out before the question even runs.

Where you sit, once included, depends on other things: how many independent sources describe you, how recent they are, how well your category is set on review sites, and how quotable the language about you is. It depends less on your star rating or your raw number of reviews than people expect.

## Two speeds

Not every engine updates at the same pace.

Retrieval-based surfaces, like Perplexity and Google's AI mode, run live searches and can reflect new reviews or new pages within days or weeks. The behaviour built into chat models during training changes more slowly. So expect the faster surfaces to move first, and be patient with the rest.

## What moves the result

In rough order of weight for B2B software:

- Presence on the review sites AI reads, with the right category and a clear profile.
- A consistent description of you across the web. Same name, same category, same one-liner.
- Being described by several independent sources, not just your own site.
- Recent, specific reviews from real customers, in the words buyers actually use.
- Your own pages written so they can be quoted. Direct answers, clear headings, tables, real prices.
- Being named in third-party comparison pages and "best tool for X" lists.

## What does not move it

Worth knowing, so you do not spend time here:

- **llms.txt.** A file some people add to point AI at their content. Google's mid-2026 guidance says it is not needed, and independent studies found close to no effect on AI visibility. Skip it unless you run a developer documentation site.
- **Star rating on its own.** A high average helps trust, but it does not decide your place in the list.
- **Raw review count past a point.** Once you are credibly present, adding more reviews does little for placement. Recency and specific language do more.
- **Keyword stuffing and AI-written filler.** Thin, generic content is the opposite of quotable.
- **Fake or incentivised reviews.** Review sites remove them, and they put your profile at risk. Not worth it.

The pattern: real presence, described consistently, backed by real customers, written so it can be quoted. There is no shortcut around that.
