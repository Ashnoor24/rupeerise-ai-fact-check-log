# Step 5: Official Source Verification & Hallucination Log

**Student:** Ashnoor Kaur (2620992549)

## Verification Table Against Official Sources (`npci.org.in`, `rbi.org.in`, `pib.gov.in`)

| ID | AI Claim | What the Official Source Says (with Link) | Verdict |
| :--- | :--- | :--- | :---: |
| **C01** | UPI recorded 18.2 billion transactions in October 2024. | NPCI official UPI Product Statistics (https://www.npci.org.in/what-we-do/upi/product-statistics) reports **16.58 billion** transactions in October 2024, not 18.2 billion. | **Distorted** |
| **C02** | UPI transactions were worth ₹26.4 lakh crore in October 2024. | NPCI official UPI Product Statistics (https://www.npci.org.in/what-we-do/upi/product-statistics) reports **₹23.50 lakh crore** (₹23,49,821.46 Cr) in October 2024. | **Distorted** |
| **C03** | UPI volume grew at 52% YoY in October 2024. | Comparing Oct 2024 (16.58B) vs Oct 2023 (11.41B) on NPCI (https://www.npci.org.in/what-we-do/upi/product-statistics), YoY volume growth was **45.3%**, not 52%. | **Distorted** |
| **C04** | Over 450 million unique users are onboarded on UPI nationwide. | NPCI does not publish a live unique-user count on its monthly statistics dashboard; RBI/PIB releases cite ~350–380M users (https://pib.gov.in). | **Unsupported** |
| **C05** | India's digital lending book is valued at $350 billion in 2024. | No RBI publication (https://www.rbi.org.in) states a $350B digital lending book for 2024 (unverified consulting blog estimate). | **Unsupported** |
| **C06** | India's digital lending market is expected to reach $1.3 trillion by 2030. | The $1.3T by 2030 projection is from a private BCG-FICCI report, not an official RBI or PIB forecast (https://www.rbi.org.in). | **Unsupported** |
| **C07** | Source for $350B / $1.3T is "RBI Working Group Report, 2023". | The RBI Working Group on Digital Lending report was published in **November 2021** (https://www.rbi.org.in/Scripts/PublicationReportDetails.aspx?UrlPage=&ID=1189), not 2023, and contains neither figure. | **Fabricated** |
| **C08** | RBI Digital Lending Directions (Circular RBI/2022-23/111, Sept 2, 2022) mandate KFS and APR. | Matches RBI Notification RBI/2022-23/111` (`DOR.CRE.REC.66/21.07.001/2022-23) dated Sept 2, 2022 on https://www.rbi.org.in/Scripts/NotificationUser.aspx?Id=12382. | **Correct** |
| **C09** | RBI Circular DOR.FIN.REC.42/2023-24 (Aug 14, 2023) prohibits contact list access. | While banning contact-list access is a real rule under the Sept 2, 2022 guidelines, **Circular DOR.FIN.REC.42/2023-24 dated August 14, 2023 does not exist** on https://www.rbi.org.in/Scripts/NotificationUser.aspx. | **Fabricated** |
| **C10** | Nandan Nilekani quote at 2024 Global FinTech Fest ("enable 500 million formal credit borrowers within the next three years"). | No record of this verbatim quote appears in official GFF transcripts or PIB archives (https://pib.gov.in). | **Fabricated** |
| **C11** | Source for October 2024 UPI figures is "NPCI Monthly Metrics, 2024". | NPCI's official portal (https://www.npci.org.in/what-we-do/upi/product-statistics) publishes monthly UPI statistics, though the AI misquoted the numbers inside it. | **Correct** |

## Audit Summary
* **Total Claims Audited:** 11 (2 Correct | 3 Distorted | 3 Unsupported | 3 Fabricated → **9 non-Correct claims**).
* **Overconfidence Trap:** The AI rated **9 of 11 claims as "High" confidence** in Step 4—yet **7 of those 9 "High" confidence claims turned out to be Distorted, Unsupported, or Fabricated**.
