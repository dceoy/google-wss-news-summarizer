Give me a concise, professional news briefing as I start my work day. Keep the briefing strictly limited to developments published within the last 24 hours.

## Context

I am interested only in high-signal, professionally relevant news in the following domains:

- Technology
- Science
- Finance
- Politics
- Economics

Prioritize developments with material impact on markets, regulation, public policy, major companies, scientific research, infrastructure, national security, or international affairs.

## Core scope rules

- ONLY include news published within the last 24 hours.
- EXCLUDE unverified social media claims or weakly sourced breaking reports.

## Selection rules

- Prioritize the most important and actionable developments.
- Focus on substantive, evidence-backed developments.
- Merge duplicate coverage of the same event into one item.
- Prefer the most authoritative and direct source for each item.
- If multiple sources discuss the same event, cite the strongest available evidence first.

## Evidence rules

- Use an evidence-first approach.
- Prefer sources in this order:
  1. Primary sources (official government statements, central bank releases, company filings, company press releases, regulator notices, court filings, official data releases, peer-reviewed journal articles)
  2. Reputable wire services and major financial newspapers
  3. High-quality secondary analysis

- For science items, strongly prefer peer-reviewed papers, official preprints, journal publications, university press releases tied to a paper, or official institutional statements.
- For technology items, prefer official company announcements, regulatory filings, security advisories, technical documentation, and direct statements by the relevant organization.
- For finance, politics, and economics, prioritize items involving central banks, inflation, interest rates, regulation, fiscal policy, trade, sanctions, major earnings, M&A, capital markets, macro indicators, or geopolitical policy shifts.
- If evidence is weak, conflicting, or incomplete, say so explicitly and either deprioritize the item or omit it.

## Source citation rules

- For each item, include 1 to 3 sources maximum.
- Cite sources in a format similar to scientific or academic references.
- Do not fabricate authors, publication names, dates, issue numbers, DOIs, or other citation fields.
- If a citation field is unavailable, omit that field rather than guessing.
- Use direct article URLs only, never a homepage or landing page.

## Citation format

- For news / official documents, use this style:
  [1] Author or Organization. "Article or document title." Publication or Issuing Body. Published YYYY-MM-DD. Direct URL
- For scientific papers, use this style when available:
  [1] Author(s). "Paper title." Journal. Year;Volume(Issue):Pages. DOI. Direct URL
- If the source is a preprint, label it clearly as:
  [1] Author(s). "Paper title." Preprint (e.g. arXiv / bioRxiv / medRxiv). Posted YYYY-MM-DD. Direct URL
- If the source is an official filing, label it clearly as:
  [1] Organization. "Filing / release title." Filing type or agency. Published YYYY-MM-DD. Direct URL

## Output rules

- Do not include any introductory sentence, greeting, or conversational preamble.
- Organize the output under these headers only:
  - 💻 Technology
  - 🔬 Science
  - 💹 Finance
  - 🏛️ Politics
  - 📈 Economics

- Use only sections that have strong qualifying items in the last 24 hours. Omit empty sections.
- Under each header, use bullet points.
- Do not repeat the same event across multiple sections.
- Keep the tone factual, neutral, and concise.
- Do not add opinions.

## For each bullet point, output in this exact structure

- **English:** Headline — 1–2 sentence factual summary.
  **Why it matters:** 1 sentence explaining the practical significance (market / policy / industry / scientific significance).
  **日本語:** 見出し — 1〜2文の事実ベース要約。
  **重要性:** 実務上の重要性を1文で記載。
  **Sources:**
  [1] ...
  [2] ...

## Formatting rules

- Use rich text formatting with bold headers and clean spacing.
- Keep bullets visually separated with line breaks.
- Hyperlink text should be the article title or the direct URL itself if needed.
- Do not use vague labels like "link".
- Include publication dates inside the citations only.
- Keep the output compact, readable, and evidence-dense.

## Quality control

- Before finalizing, check for duplicate events, weak sourcing, non-qualifying categories, and missing source dates.
- If a source is not sufficiently trustworthy or direct, replace it with a better source or remove the item.
