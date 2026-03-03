# Daily Market News Analysis

Analyze the latest macroeconomic and financial news from reputable sources.
Prioritize items published or updated in the last 24-48 hours.

## Scope

- Equities: S&P 500, NASDAQ 100, Dow, Russell 2000, Nikkei 225, S&P/ASX 200, China A50, Hang Seng, MSCI Singapore, EURO STOXX 50, DAX, CAC 40, AEX, FTSE 100
- Commodities: WTI, Brent, Gold, Silver, Copper, Platinum, NatGas
- Macro/FX: UST yields, DXY, VIX, USD/JPY, EUR/USD

## For each category (Equities / Commodities / Macro&FX), do exactly

1. Key drivers (2-4): the freshest catalysts (data prints, central banks, geopolitics, positioning, market microstructure).
2. Why it matters: one line per driver linking to price action/mechanism (e.g., `高インフレ -> 実質金利↑ -> 金下押し`).
3. 24h outlook: Bias = {Bullish | Bearish | Sideways}. Add 2–3 critical levels or events (exact times in JST).
4. Confidence: 0-5. Add 1 alternate scenario (what flips the bias).

## Output requirements

- Keep tone factual, neutral, and concise.
- Use headers, bolding, spacing, line breaks, emojis and links to make the output look great.
- Include direct links to sources for each item.
- Add blank lines between items for readability.
- Translate the analysis results to Japanese for the final output.

## Output structure example

**Daily Market News Analysis** (YYYY-MM-DD HH:MM JST)

📈 **Equities**

Key drivers (2-4):

- {Driver 1}: [Primary source](https://example.com/source-1)
- {Driver 2}: [Primary source](https://example.com/source-2)

Why it matters:

- {Driver 1} -> {Mechanism} -> {Price action}
- {Driver 2} -> {Mechanism} -> {Price action}

24h outlook:

- Bias: Bullish | Bearish | Sideways

Critical levels / events (JST):

- {Asset}: {Support} / {Resistance}
- {HH:MM JST} {Event}

Confidence:

- {0-5} / 5
- Alternate scenario: {What changes the bias}

...
