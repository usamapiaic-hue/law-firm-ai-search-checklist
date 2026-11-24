# Law Firm AI Search Visibility Checklist

More people now ask ChatGPT, Perplexity or Google's AI Overviews "who is a good divorce lawyer near me?" before they ever click a website. AI tools answer from sources they can read, trust and connect to a real firm. This checklist covers what a law firm can control. Published by Legal Web Agency.

## 1. Let the crawlers in

| Check | Pass condition |
|-------|----------------|
| robots.txt | Does not block GPTBot, OAI-SearchBot, PerplexityBot, ClaudeBot or Google-Extended, unless the firm has decided to |
| Firewall / CDN | Bot protection does not return errors to legitimate AI crawlers |
| Rendering | Key text is in the HTML, not loaded only by scripts after the page opens |
| llms.txt | Optional plain-text summary of the firm and its key pages at /llms.txt |

An llms.txt file is not a standard that every tool reads, but it is cheap to add and harmless.

## 2. Be one clear entity

AI tools need to be sure that the firm on your website, your Google Business Profile and your directory listings is the same firm.

- The same firm name, address and phone everywhere.
- Organization or LegalService structured data on the homepage, with `sameAs` links to the profiles the firm controls.
- Attorney bios with the lawyer's full name, bar admissions and practice focus.
- A Google Business Profile that is complete and active.

## 3. Write pages that can be quoted

- Put a direct 40-60 word answer under each main heading.
- Use one page per case type, so each answer is specific.
- Add short FAQ sections taken from real intake questions.
- Use plain numbers and dates where they are accurate, and update them when the law changes.
- Avoid unverifiable claims such as "best" or "top-rated". They are an advertising-rule risk, and AI tools tend to ignore them anyway.

## 4. Be mentioned elsewhere

AI answers lean heavily on third-party sources: "best lawyers in [city]" lists, local news, bar association pages, legal directories and review sites. A firm that appears only on its own website is easy to overlook.

| Source | What to do |
|--------|------------|
| Legal directories | Keep listings consistent and complete |
| Reviews | Ask every satisfied client; reply to each review |
| Local media | Offer comment on legal topics in the news |
| "Best of" lists | Check which lists AI tools cite for your city and practice |

## 5. Test it the same way every quarter

1. Write 5 to 10 prompts a real client might use ("best DUI lawyer in Tampa", "do I need a lawyer for a car accident in Ohio").
2. Run them in ChatGPT, Perplexity and Google with location settings that match your market.
3. Record whether the firm is mentioned, which sources are cited, and which competitors appear.
4. Compare quarter to quarter, and fix the gaps the cited sources reveal.

## Further reading

Legal Web Agency has longer guides on [ChatGPT and law firms](https://legalwebagency.com/does-chatgpt-recommend-your-law-firm/), [Google AI Overviews for law firms](https://legalwebagency.com/google-ai-overviews-for-law-firms/) and [llms.txt for law firms](https://legalwebagency.com/llms-txt-for-law-firms/). For a quick look at your own site, the free [Legal Web Agency website scan](https://legalwebagency.com/free-website-scan/) checks robots.txt, llms.txt, schema, titles and headings, plus common bar advertising wording problems.

---

*Published by [Legal Web Agency](https://legalwebagency.com/), a website design and SEO studio for law firms.*
