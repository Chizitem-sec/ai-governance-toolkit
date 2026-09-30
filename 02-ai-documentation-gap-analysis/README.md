# AI Documentation Gap Analysis: A Case Study

I reviewed a 46 document AI governance framework as a security lead, to find what was missing and make the software that holds it easier to measure. This is the walkthrough of how I did it and what I found.

The full write up and the numbers are in the workbook: **AI_Documentation_Gap_Analysis_Case_Study.xlsx**.

## Summary

- I sorted all 46 documents by security area, type, driver and adoption tier, then checked the whole set against three public lists of AI risks.
- **Biggest finding:** the framework is built for AI that informs decisions, not AI that acts. Of the 10 OWASP agentic risks, only 1 is covered, 4 are thin, and 5 have nothing.
- **Second finding:** it has a policy layer but no control layer. 26 of 46 documents are governance, only 8 are technical, and 5 of the 8 lifecycle stages have no technical document at all.
- I recommended 5 new documents, 4 changes to existing ones, and a set of fixes to the software.

## How I did it

1. **Sort every document.** Four labels each: domain, control type, driver, adoption tier. One rule: one value per label, or you cannot count.
2. **Count.** A coverage matrix by stage. Empty cells and lopsided rows show the gaps.
3. **Check against public references.** OWASP Top 10 for Agentic Applications, CSA AI Controls Matrix, MITRE ATLAS. One verdict per risk: Covered, Thin or Absent. The rule: judge what a document says, not what it links to.
4. **Turn gaps into proposals**, ranked by exposure.
5. **Fix the tool** so the set can be measured, not just browsed.

## What's in the workbook

- **Walkthrough:** the full story, step by step, with the findings.
- **Findings:** the real numbers behind every claim.
- **Document Inventory (sample):** 14 of the 46 documents, shown as a worked example of the classification. The rest are held back.
- **Reference Sweep:** the verdict for all 42 risks across the three references.

## What I found

- Built for AI that informs, not AI that acts. Nothing in the set covers agents that call tools or take actions.
- A policy layer with no control layer. Plenty of governance, almost no technical controls.
- Nothing protects the model itself, and nothing covers who may access an AI system.
- Most documents exist for compliance (17) rather than security (7).

## What I recommended

- **Five new documents:** Agentic AI Security Standard, AI Identity and Access Management Policy, AI Model Security Standard, AI Cryptography and Key Management Standard, AI Change and Configuration Management Procedure.
- **Four changes to existing documents:** make the threat assessment recurring and cover runtime poisoning, extend supply chain risk to parts an agent fetches while running, add security logging to monitoring, and add rules for AI generated code.
- **Software fixes:** count from structured labels, add search across all documents, and replace simple status with maturity levels that need evidence.

## References used

- OWASP Top 10 for Agentic Applications: genai.owasp.org
- CSA AI Controls Matrix: cloudsecurityalliance.org
- MITRE ATLAS: atlas.mitre.org

## Note

This shows the method and the findings. It shows 14 of the 46 document titles as examples; the full set is held back. It names no client and no internal product.

## Author

Johnbosco Ibeneme, AI Governance and GRC
LinkedIn: linkedin.com/in/chizitem-ibeneme
