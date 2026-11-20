# Aurum Accord

**Tech4Bharat 2026 · Problem Statement 2.2 · Jeweltech**

A repo starter for the Aurum Accord idea submission. It includes the copy-ready submission fields, the presentation PDF, product scope, and supporting research references.

## Submission form content

### Project Title

Aurum Accord: Bilateral Gold Job-Work Ledger

### Brief about your idea

Aurum Accord is a proposed shared gold job-work record for jewellers and karigars. It captures agreed job terms, gold handovers and returns, and shows unresolved weight or material differences as open items for both parties to review. An AI agent asks focused questions about missing details and prepares a monthly statement for their approval. Each karigar can access their own account and review, confirm, or dispute entries. AI suggestions remain provisional until confirmed; calculations are transparent, and the system does not assign fault, apply deductions, or execute payments.

### Detailed explanation of the idea

Aurum Accord is designed around one jeweller–karigar relationship and a shared record for each gold job. Before work begins, the jeweller records the agreed terms, due date, relevant purity and weight details, and the quantity of gold handed over. The karigar can access their own account, review and confirm the handover, then record returned pieces, weights, scrap or other remaining material, and job progress. Both parties can see which entries are confirmed and which still need review.

Gold reconciliation is the core workflow. A rules-based ledger compares the recorded issue, return, and remaining-material quantities, showing the inputs and arithmetic behind each balance. When an entry leaves an unresolved balance, Aurum Accord opens an item for review immediately rather than waiting until month-end. If the parties record different return weights, it preserves both values and asks them to clarify or correct the record. If remaining gold has not been classified, the agent asks a focused question about it. It does not decide which person or measurement is right.

In the illustrative Job 12, 250.000 g is issued. The karigar first records 244.620 g returned, while the jeweller records 244.640 g, so the 0.020 g difference becomes an open item. After review, the karigar corrects the return to 244.640 g. The karigar then classifies 4.700 g as recoverable scrap, leaving 0.660 g. In this example only, that balance is 0.340 g below the 1.000 g allowance agreed for the job. These figures demonstrate the workflow; they are not industry benchmarks.

The agent tracks missing information and pending confirmations, drafts a neutral clarification or reminder, and prepares a monthly statement showing job entries, open items, and settlement status. AI-drafted text stays marked **Suggested** until a person confirms it. Corrections are added as new entries so earlier records remain visible. At month-end, both parties review and approve the same statement version. Aurum Accord does not assign fault, impose a universal wastage rule, make deductions, or execute payment.

The proposed MVP includes a shared job card, confirmation-first ledger, issue and return entries, discrepancy thread, rules-based plan panel, typed AI drafting, and monthly statement with dual approval. An offline draft queue, voice input, and English plus one Indian language are planned; approvals require a connection. Reminders are simulated in the presentation.

Desk research suggests jewellery ERP products cover parts of job-work operations and reconciliation. Aurum Accord’s proposed focus is narrower: a karigar-friendly, bilateral confirmation and settlement workflow for one jeweller–karigar relationship. This positioning, along with local workflows, adoption, and willingness to pay, still needs validation.

### Presentation Deck

The PDF presentation is in [`presentation/`](presentation/):

- [`Aurum_Accord_Tech4Bharat.pdf`](presentation/Aurum_Accord_Tech4Bharat.pdf)

### Additional supporting links (research reference)

- **Research references:** see [`docs/REFERENCES.md`](docs/REFERENCES.md).

## Repository status

This repository contains submission materials and product-scope notes; it does not contain a working software implementation. No field interviews, local adoption validation, or willingness-to-pay research are claimed. See [`docs/PROJECT_SCOPE.md`](docs/PROJECT_SCOPE.md) before adding implementation claims.
