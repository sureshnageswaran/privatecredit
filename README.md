# Private Credit Research Corpus
 > **⚠️ Synthetic Research Artifact**
All agreements, entities, borrowers, lenders, and financial terms in this repository are entirely fictitious and were synthesized for research purposes. No document here represents a real transaction, real party, or real confidential information.

# Meridian Composites Open Private Credit Agreement Benchmark

A fully synthetic private credit agreement for document AI, covenant extraction, GraphRAG, ontology design, and agentic compliance research.

## Overview

This repository contains a **fictional, synthetic senior secured credit agreement** for **Meridian Composites, LLC**.

The agreement was created as an open research artifact because real private credit agreements are rarely available to researchers, builders, students, and open-source contributors. Most private credit documents are confidential, negotiated bilaterally, and unavailable outside lenders, sponsors, counsel, and borrowers. That creates a major bottleneck for anyone trying to build tools for covenant monitoring, private credit analytics, legal document understanding, credit agreement parsing, or AI-based workflow automation.

This project is intended to help close that gap.

The included agreement is not a real transaction document. It is a synthetic benchmark designed to resemble the complexity of a middle-market sponsor-backed private credit deal.

The main artifact is:

```text
Meridian_Composites_Credit_Agreement.pdf
```

It is a fictional execution-version credit agreement dated June 10, 2026, among:

* Meridian Composites, LLC, as Borrower
* Meridian Composites Intermediate Holdings, LLC, as Holdings
* The lenders party thereto
* Argent Capital Administrative Services, LLC, as Administrative Agent and Collateral Agent
* Argent Direct Lending Advisors, L.P., as Sole Lead Arranger and Sole Bookrunner

The synthetic transaction includes **$385 million of senior secured credit facilities**, consisting of:

* **$300 million Initial Term Loan**
* **$50 million Delayed Draw Term Loan**
* **$35 million Revolving Facility**

## Why This Exists

Private credit has become a major part of the institutional lending market, but the documents that govern private credit transactions are usually not public.

That makes it difficult to build, test, and benchmark AI systems for questions such as:

* Can an LLM correctly identify the financial covenants?
* Can a model extract all restricted payment baskets?
* Can a GraphRAG system trace definitions across a 90+ page agreement?
* Can an agent determine whether a proposed acquisition, dividend, debt incurrence, or PIK election is permitted?
* Can a small model be fine-tuned to classify credit agreement clauses?
* Can an ontology represent the relationships among loans, commitments, covenants, baskets, subsidiaries, collateral, defaults, and remedies?

Most researchers cannot work on these problems because they do not have access to realistic private credit agreements.

This benchmark provides a synthetic but realistic document that can be shared, annotated, extended, and used for reproducible research.

## Important Disclaimer

This document is **entirely fictional and synthetic**.

It is not:

* A real credit agreement
* A market-standard form
* A legal template
* Legal advice
* Investment advice
* Lending advice
* A recommendation for any transaction structure
* A substitute for review by qualified counsel

No real borrower, lender, sponsor, agent, transaction, commitment, or credit facility is represented by this agreement.

Any resemblance to actual companies, funds, agreements, transactions, or legal drafting is unintended.

Use this artifact for research, education, experimentation, and benchmarking only.

## Core Private Credit Features Included

The agreement intentionally includes many features commonly found in sponsor-backed private credit and direct lending transactions.

### 1. Facility Architecture

The agreement includes multiple loan facilities:

* Initial Term Loan
* Delayed Draw Term Loan
* Revolving Facility
* Incremental / accordion facility mechanics
* Separate commitments by facility type
* Term loan and revolver treatment
* Borrowing requests
* Interest election mechanics
* Commitment termination mechanics

### 2. Delayed Draw Term Loan Mechanics

The DDTL feature is designed to support post-closing activity such as acquisitions or capital expenditures.

Included features:

* Delayed draw availability period
* Maximum aggregate DDTL commitment
* Minimum draw size
* Limit on number of DDTL borrowings
* Permitted uses of DDTL proceeds
* Conditions to DDTL funding
* Pro forma covenant compliance requirement
* Liquidity trigger limitations
* No reborrowing after repayment

### 3. Revolving Facility

The agreement includes a revolving facility intended for working capital and general corporate purposes.

Included features:

* Revolving commitments
* Revolving loans
* Revolving exposure
* Unused commitment fee
* Borrowing and repayment mechanics
* Liquidity trigger based on revolver usage
* Minimum liquidity covenant during liquidity trigger periods

### 4. Interest Rate Structure

The agreement includes a modern SOFR-based interest rate framework.

Included features:

* Term SOFR loans
* Base Rate loans
* Adjusted Term SOFR
* SOFR adjustment
* Interest rate floor
* Base Rate floor
* Interest periods
* Interest payment dates
* Default interest
* Benchmark replacement mechanics

### 5. Pricing Grid

The agreement includes a leverage-based pricing grid tied to the Total Net Leverage Ratio.

Included features:

* Pricing levels
* Term SOFR margins
* Base Rate margins
* Step-down pricing based on leverage
* Default to highest pricing level if compliance certificates are not delivered
* Retroactive margin true-up after financial statement restatement

### 6. PIK Interest Feature

The agreement includes a PIK election feature for the Term Loans.

Included features:

* Borrower election to pay a portion of interest in kind
* PIK Election Period
* Maximum PIK percentage
* Maximum number of PIK quarters
* PIK margin increase
* Capitalization of PIK interest
* Treatment of capitalized PIK as principal
* PIK impact on amortization
* PIK impact on voting and lender economics
* Event of Default blocker for PIK elections

This is one of the most important features in the artifact because PIK interest creates several downstream reasoning issues for AI systems. A model must understand that PIK interest is not merely deferred cash interest. It becomes principal, increases future interest accrual, affects leverage, and may affect prepayment economics.

### 7. Fees

The agreement includes several fee types.

Included features:

* Revolving commitment fee
* Delayed Draw Term Loan ticking fee
* Agency fees
* Fee Letter reference
* Quarterly fee payment mechanics

### 8. Amortization

The agreement includes light scheduled amortization with a large final maturity payment.

Included features:

* Quarterly term loan amortization
* DDTL amortization after funding
* Amortization recalculation after PIK capitalization
* Final maturity balloon payment

### 9. Voluntary Prepayments

The agreement includes voluntary prepayment rights.

Included features:

* Voluntary prepayment of Term Loans
* Voluntary prepayment of Revolving Loans
* Conditional prepayment notices
* SOFR notice periods
* Base Rate notice periods
* Breakage cost mechanics
* Application of prepayments to remaining amortization installments

### 10. Mandatory Prepayments

The agreement includes multiple mandatory prepayment triggers.

Included features:

* Asset sale sweep
* Casualty event sweep
* Debt incurrence sweep
* Excess Cash Flow sweep
* Change of Control repayment
* Reinvestment rights
* De minimis thresholds
* Declining lender mechanics

### 11. Excess Cash Flow Sweep

The agreement includes an annual Excess Cash Flow sweep.

Included features:

* ECF calculation
* Leverage-based ECF sweep percentage
* ECF step-downs
* ECF de minimis threshold
* Credit for voluntary prepayments
* Declining lender treatment

### 12. Call Protection and Prepayment Premium

The agreement includes private-credit-style call protection.

Included features:

* Make-whole premium during the first year
* 2.00% premium after year one
* 1.00% premium after year two
* No premium after year three
* Premium Events
* Premium on acceleration
* Premium in certain bankruptcy or restructuring scenarios
* Repricing protection

### 13. Incremental Facility / Accordion

The agreement includes incremental debt capacity.

Included features:

* Incremental Term Loans
* Incremental Revolving Commitments
* Free-and-clear incremental basket
* Ratio-based incremental basket
* Pro forma leverage testing
* MFN protection
* Maturity protection
* Weighted average life protection
* Pari passu and junior-lien incremental debt
* No obligation of existing lenders to participate
* Incremental facility amendment mechanics

### 14. Financial Covenants

The agreement includes a financial covenant package.

Included features:

* Maximum Total Net Leverage Ratio
* Minimum Fixed Charge Coverage Ratio
* Minimum Liquidity covenant
* Step-down leverage covenant
* Liquidity covenant triggered by revolver usage
* Quarterly testing
* Compliance certificate reporting

### 15. Equity Cure

The agreement includes a sponsor equity cure right.

Included features:

* Cure Amount
* Cure Right
* EBITDA addback for covenant cure purposes
* Cure window after compliance certificate due date
* Limits on frequency of cures
* Lifetime cap on cures
* Cure amount limited to amount needed for compliance
* Debt repayment from cure proceeds disregarded for covenant testing
* Remedy standstill during cure period

### 16. EBITDA and Ratio Definitions

The agreement includes a detailed definition of Consolidated EBITDA and related financial metrics.

Included features:

* Interest addbacks
* Tax addbacks
* Depreciation and amortization addbacks
* Non-cash charge addbacks
* Transaction cost addbacks
* Restructuring cost addbacks
* Business optimization cost addbacks
* Run-rate cost savings and synergy addbacks
* Sponsor fee addbacks
* Insurance and indemnity reimbursement addbacks
* Caps on certain addbacks
* Pro forma adjustments
* Historical deemed EBITDA
* Cash netting cap
* Treatment of capitalized PIK in net debt

This section is particularly useful for AI research because many credit agreement questions require the model to distinguish accounting metrics from covenant-defined metrics.

### 17. Reporting Package

The agreement includes an ongoing reporting and monitoring package.

Included features:

* Annual audited financial statements
* Quarterly financial statements
* Monthly financial statements
* Annual budget
* Compliance Certificate
* Excess Cash Flow calculation
* Available Amount rollforward
* Basket usage reporting
* Equity cure reporting
* Lender calls
* Notice obligations
* Inspection rights
* KYC / AML information requests

### 18. Negative Covenants

The agreement includes a broad negative covenant package.

Covered covenant categories include:

* Indebtedness
* Liens
* Fundamental changes
* Dispositions
* Investments
* Restricted Payments
* Junior debt payments
* Affiliate transactions
* Restrictive agreements
* Changes in business
* Fiscal year changes
* Prepayments and amendments of junior debt
* Material IP transfers

### 19. Debt Baskets

The indebtedness covenant includes multiple baskets.

Included examples:

* Debt under the loan documents
* Capitalized PIK interest
* Existing debt
* Intercompany debt
* Purchase money debt
* Capital lease obligations
* Acquired debt
* Swap obligations
* Unsecured debt
* Earnouts and purchase price adjustments
* Insurance premium financing
* General debt basket

### 20. Lien Baskets

The lien covenant includes multiple permitted lien categories.

Included examples:

* Liens securing the credit facilities
* Permitted encumbrances
* Existing liens
* Purchase money liens
* Capital lease liens
* Acquired liens
* Judgment liens below default thresholds
* Cash management liens
* General lien basket
* Special limitations relating to Material Intellectual Property

### 21. Investment Baskets

The investment covenant includes multiple investment baskets.

Included examples:

* Investments in Loan Parties
* Investments in subsidiaries
* Employee loans and advances
* Permitted acquisitions
* Joint ventures
* Non-loan-party investments
* Unrestricted subsidiary investments
* Available Amount investments
* Ratio-based investments
* General investment basket

### 22. Restricted Payments

The restricted payment covenant includes several permitted payment categories.

Included examples:

* Tax distributions
* Holdings overhead payments
* Sponsor management fees
* Employee equity repurchases
* Qualified equity payments
* General restricted payment basket
* Available Amount restricted payments
* Ratio-based restricted payments

### 23. Junior Debt Controls

The agreement includes restrictions on junior debt payments and amendments.

Included features:

* Scheduled interest and maturity payments
* Refinancing of junior debt
* Available Amount junior debt payments
* General junior debt basket
* Restrictions on adverse junior debt amendments
* Limits on increasing cash-pay interest
* Limits on shortening maturity
* Restrictions on weakening subordination

### 24. Affiliate Transactions

The agreement includes affiliate transaction restrictions.

Included features:

* Arm’s-length standard
* Dollar threshold for covered transactions
* Exceptions for permitted intercompany transactions
* Exceptions for sponsor fees
* Exceptions for employment and compensation arrangements
* Exceptions for equity transactions
* Exceptions for transaction fees and expenses

### 25. Unrestricted Subsidiaries

The agreement includes unrestricted subsidiary mechanics.

Included features:

* Designation of unrestricted subsidiaries
* Redesignation as restricted subsidiaries
* No-default requirement
* Pro forma covenant compliance
* Investment treatment of designation
* EBITDA cap on unrestricted subsidiaries
* Restrictions on ownership of Material Intellectual Property
* Restrictions on unrestricted subsidiaries holding equity of the Borrower or restricted subsidiaries

Unrestricted subsidiaries are important for research because they create leakage and structural subordination issues that are difficult for simple extraction systems to understand.

### 26. Material Intellectual Property Protection

The agreement includes a specific anti-leakage covenant for Material Intellectual Property.

Included features:

* Restrictions on transferring Material IP to unrestricted subsidiaries
* Restrictions on transferring Material IP to non-loan-party subsidiaries
* Restrictions on transferring Material IP to non-loan-party affiliates
* Restrictions on exclusive licensing of Material IP
* Special amendment protection
* Null-and-void language for prohibited transfers

This is one of the most useful features for collateral leakage and covenant monitoring research.

### 27. Collateral and Guarantee Package

The agreement includes a secured loan party structure.

Included features:

* Holdings guarantee
* Subsidiary guarantees
* Material domestic subsidiary guarantor requirement
* Excluded subsidiary concept
* Collateral package
* Equity pledges
* CFC pledge limitation
* Intercompany note
* UCC filings
* Intellectual property security agreements
* Deposit account control agreements
* Post-closing collateral perfection requirements

### 28. Events of Default

The agreement includes standard and private-credit-specific Events of Default.

Included examples:

* Nonpayment of principal
* Nonpayment of interest or fees
* Breach of representations
* Breach of affirmative covenants
* Breach of negative covenants
* Financial covenant defaults
* Cross-default to Material Indebtedness
* Bankruptcy and insolvency defaults
* Judgment defaults
* ERISA defaults
* Invalidity of loan documents
* Invalidity of guarantees or collateral documents
* Change of Control

### 29. Assignment and Voting Mechanics

The agreement includes lender assignment and voting provisions.

Included features:

* Eligible assignee requirements
* Borrower consent rights
* Agent consent rights
* Assignment minimums
* Assignment fees
* Disqualified Lender restrictions
* Affiliated Lender restrictions
* Debt Fund Affiliate provisions
* Required Lender voting
* Sacred rights
* Pro rata sharing
* Amendment and waiver mechanics

### 30. Boilerplate and Regulatory Provisions

The agreement includes several standard loan agreement provisions.

Included examples:

* Taxes and withholding
* Increased costs
* Break funding
* Illegality
* Replacement of lenders
* Confidentiality
* Notices
* Expenses and indemnification
* Governing law
* Jurisdiction
* Waiver of jury trial
* Electronic execution
* Patriot Act notice
* Beneficial ownership regulation
* Sanctions
* Anti-corruption laws
* ERISA
* Bail-in acknowledgement
* Supported QFC acknowledgement

## Suggested Benchmark Tasks

This document can be used to create benchmark tasks such as:

### Covenant Extraction

Extract:

* Maximum Total Net Leverage Ratio covenant
* Minimum Fixed Charge Coverage Ratio covenant
* Minimum Liquidity covenant
* Testing dates
* Cure rights
* Covenant levels
* Trigger conditions

### PIK Reasoning

Answer questions such as:

* Can the borrower elect to PIK interest?
* What percentage of interest may be paid in kind?
* How long can the PIK election last?
* What happens to PIK interest after capitalization?
* Does PIK apply to Revolving Loans?
* How does PIK affect principal and future interest?

### Basket Analysis

Answer questions such as:

* How much debt can the borrower incur under the general debt basket?
* Can the borrower make an investment in a non-loan-party subsidiary?
* Can the borrower make a restricted payment using the Available Amount?
* Which baskets are fixed-dollar baskets?
* Which baskets are ratio-based?
* Which baskets require no default?

### Acquisition Scenario Testing

Answer questions such as:

* Can the borrower use DDTL proceeds for a permitted acquisition?
* What conditions must be satisfied before a DDTL borrowing?
* How does the Limited Condition Transaction election work?
* What happens if leverage changes between signing and closing?

### Collateral Leakage Testing

Answer questions such as:

* Can Material IP be transferred to an unrestricted subsidiary?
* Can a subsidiary holding Material IP be excluded from the guarantee package?
* What happens if a prohibited Material IP transfer occurs?
* Which assets require perfection?
* Which assets are excluded from perfection requirements?

### Default and Remedy Reasoning

Answer questions such as:

* What happens upon a payment default?
* What happens upon a bankruptcy default?
* Does acceleration trigger a prepayment premium?
* Which defaults have cure periods?
* Which defaults trigger automatic acceleration?

### GraphRAG Tasks

Build a graph connecting:

* Defined terms
* Sections
* Covenants
* Baskets
* Ratios
* Loan facilities
* Events of Default
* Collateral requirements
* Subsidiary classifications
* Permitted and prohibited actions


## Responsible Use

This artifact is intended to support open research and education.

Please do not use it to:

* Represent a real transaction
* Train systems that provide legal advice without attorney review
* Market financial products as if the agreement were real
* Mislead users into believing the document is an actual credit agreement
* Replace professional legal, credit, or investment judgment

If you use this artifact in a model, demo, article, benchmark, or academic project, clearly disclose that the underlying document is synthetic.

## Suggested Citation

If you use this artifact, please cite it as:

```text
Meridian Composites Open Private Credit Agreement Benchmark,
synthetic private credit agreement research artifact,
created for covenant extraction, document AI, GraphRAG, and agentic compliance research.
```

Suggested BibTeX entry:

```bibtex
@misc{meridian_composites_private_credit_benchmark,
  title        = {Meridian Composites Open Private Credit Agreement Benchmark},
  author       = {Suresh Nageswaran},
  year         = {2026},
  note         = {Synthetic private credit agreement for document AI, covenant extraction, GraphRAG, and agentic compliance research}
}
```

## Contributing

Contributions are welcome.

Useful contributions include:

* Clause annotations
* Defined-term extraction
* Covenant extraction labels
* Basket labels
* Question-answer pairs
* Scenario tests
* Ontology improvements
* GraphRAG schemas
* Markdown or JSON conversions
* Additional synthetic private credit documents
* Benchmark results from different models

Potential future synthetic documents could include:

* First amendment
* Waiver letter
* Compliance certificate
* Borrowing request
* DDTL funding notice
* Quarterly financial package
* Officer certificate
* Notice of default
* Intercreditor agreement
* Security agreement
* Sponsor support letter
* Restructuring support agreement



## Project Status

Initial release.

The first version includes the synthetic Meridian Composites credit agreement as a PDF. Additional structured formats, annotations, benchmark questions, and ontology files may be added later.

## Contact

Created by Suresh Nageswaran.

This project is part of a broader effort to make alternative investments, private credit, and institutional finance more accessible to AI researchers, engineers, students, and practitioners.

