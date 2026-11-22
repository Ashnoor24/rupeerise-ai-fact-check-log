# RupeeRise: Fact-Checking an AI-Written Investor Brief

**A FinTech case study on catching AI hallucinations before they reach investors.**

Author: Ashnoor Kaur (2620992549) · BBA (FinTech), Chitkara Business School · Tools: Gemini AI, ChatGPT, Perplexity AI · November 2026

## The case
**RupeeRise** (fictional) is a digital lending app in Bengaluru lending to young salaried workers. Its founder asked an AI tool to write a one-page investor brief on India's digital lending and UPI market. As a Business Analyst, I checked every single claim against official NPCI, RBI, and PIB sources before the brief could reach investors.

## The data
Two 250-word AI drafts generated from the exact same prompt (Gemini AI vs. ChatGPT), 11 extracted factual claims audited against `npci.org.in`, `rbi.org.in`, and `pib.gov.in`, plus a live citation audit of 4 Perplexity AI links.

## Approach
| Step | Tool | Task |
|---|---|---|
| 1 | None | Read RupeeRise case & define official proof sources |
| 2 | Gemini AI + ChatGPT | Generate identical 250-word investor briefs |
| 3 | Manual rubric | Score both drafts out of 10 |
| 4 | ChatGPT | Extract 11 claims and ask AI to self-rate confidence |
| 5 | Official sites | Verify every claim against NPCI, RBI, and PIB |
| 6 | Perplexity AI | Audit every cited URL for actual claim support |
| 7 | Manual rewrite | Produce verified brief + 8-rule "What not to do" guide |

## Results
| Metric | Result |
|---|---|
| Draft scores (Gemini AI vs. ChatGPT) | 8/10 vs. 7/10 |
| Claims audited in ChatGPT draft | 11 |
| Verdict breakdown | 2 Correct · 3 Distorted · 3 Unsupported · 3 Fabricated |
| "High" confidence claims that failed audit | 7 out of 9 (78% overconfidence error rate) |
| Perplexity citations verified | 2 Supports · 1 Partly supports · 1 Does not support |

## Key learnings
1. **Fluency hides fabrication:** ChatGPT invented a realistic-sounding RBI circular number (`DOR.FIN.REC.42/2023-24`) and an executive quote that never happened.
2. **AI confidence ratings are unreliable:** 7 of the 9 claims rated `"High"` confidence turned out to be false or distorted.
3. **A real link is not proof:** Perplexity cited a real 2022 RBI vision document to support a 2024 monthly UPI figure that was not in the file.
4. **Human verification is mandatory:** Removing 9 unverified claims and replacing them with primary NPCI/RBI figures saved RupeeRise from misleading investors.

## My recommendation to RupeeRise
Never send an AI-generated investor brief without a line-by-line source audit. Use Gemini AI and Perplexity AI to draft and locate primary `npci.org.in` and `rbi.org.in` pages quickly, open every cited PDF/table manually, and mark any unverified market projection as `[not verified]`.

## Skills shown
Fact-checking & source verification · AI hallucination detection · Regulatory research (RBI / NPCI / PIB) · Multi-tool AI benchmarking · Responsible AI governance · Investor communications

## What I learned
- AI writes fluent, confident prose even when numbers, dates, and circular numbers are fabricated.
- Only primary official websites (`rbi.org.in`, `npci.org.in`, `pib.gov.in`) count as proof in FinTech research.
- Self-reported AI confidence ("High") does not correlate with factual accuracy.
- Clicking every cited URL in Perplexity is essential because links can be irrelevant or outdated.
- A structured hallucination log turns vague skepticism into auditable evidence.

*RupeeRise and all case details in this project are fictional and created for learning.*
