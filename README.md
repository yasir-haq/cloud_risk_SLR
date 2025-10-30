# Systematic Literature Review Protocol

The complete screening results of all articles is available in this repository. 
> [screening_results_all_records.csv](/screening_results_all_records.csv).

## Review Objective and Research Questions
The main goal of this work is to develop an understanding of both technical and non-technical risks on enterprises from the utilization of cloud services, and the risk management techniques that are feasible for them.

Research questions:
1. What are the technical and non-technical risks of using cloud services for enterprise consumers?
2. What are the techniques that are feasible for enterprise cloud consumers to manage the risks of using cloud services?

## Search Strategy
- Repository: Scopus
- Query:
  ```
  TITLE-ABS-KEY ( ( cloud ) AND ( comput* OR storage OR service OR outsourc* OR iaas OR paas OR saas )
  AND ( risk OR secur* OR resilienc* OR threat ) )
  ```
- Filter:
  - Published between January 2013 and September 2022
  - Journal and conference only
  - English only
  - Final only
  - Irrelevant subject excluded
  - Q1 journals only
  - A* and A conferences only
  - Valid and unique DOI only
  - Retrievable abstract only

## Exclusion and Inclusion Criteria
Inclusion criteria:
- I1. The article is a peer-reviewed publication
- I2. The article is in English
- I3. The article is in its final stage
- I4. The article was published between January 2013 and September 2022,
- I5. The article is relevant to the search criteria as discussed in Section 5.1.3
- I6. The article focuses on the utilization of a centralized cloud for enterprises
- I7. The article presents a new discussion about risks with a direct impact on cloud consumers and originate from or increase due to cloud use
- I8. The article presents a new strategy or technique to manage the risks that are feasible for cloud consumers i.e., under consumer’s control
- I9. The article was published in a high-quality venue

Exclusion criteria:
- E1. The article refers to a wrong ‘cloud’, e.g., rain cloud
- E2. The article focuses on clouds for personal use
- E3. The article focuses on decentralized cloud, e.g., edge, fog, or mist computing
- E4. The article focuses on other emerging concepts and only refers to the cloud as an enabler
- E5. The article only presents a use case for cloud
- E6. The article presents a risk management technique that is not feasible for consumers or beyond consumers’ control
- E7. The article focuses on aspects of the cloud unrelated to risk such as optimization and adoption
- E8. Literature review, opinion, viewpoint, keynote, discussion, editorial, comment, tutorial, preface,
or anecdote paper due to its lack of new ideas
- E9. The article whose abstract or full text is inaccessible or unavailable

## Initial Search Result

![Article per year](/5k_initial_articles_by_year_source.png)
_Number of articles published per year._

## Title Screening Summary

### 🧾 Independent Screening Process
- Two junior authors screened **5,8K article titles** independently.
- Votes were consolidated and **Cohen’s kappa coefficient** was calculated at checkpoints to assess inter-rater agreement.

### 🔄 Discrepancy Resolution
- When low agreement was detected:
  - Authors shared screening experiences.
  - Misunderstandings were clarified.
  - Conflicting articles were revisited separately.
- This process led to a **Cohen’s kappa of 0.853**, indicating **almost-perfect agreement**.

### 📊 Screening Outcome
- **293 articles** were mutually agreed upon for abstract screening.
- **5 articles** lacked abstracts (labeled E9), leaving **288 articles** for the next phase.

## Abstract Screening Summary

### 🔍 Second Screening Round
- Two junior authors screened **288 articles** using titles and abstracts.
- Abstracts provided additional context to verify assumptions from the first round.

### 📘 Inclusion for Further Review
- Articles with unclear abstracts were retained for full-text screening.
- Discrepancies resolved through discussion with a senior author, following Kitchenham and Brereton’s guidance.

### 📊 Screening Outcome
- **162 articles excluded**, **126 articles** advanced to full-text screening.
- Low exclusion rate indicates high quality of initial title-based selection.

## Full-Text Screening Summary

### 📖 Third Screening Round
- Two junior authors screened **126 full-text articles** for eligibility.
- Each excluded article was labeled with its **main exclusion reason**, based on exclusion criteria from the previous section.

### 🔄 Discrepancy Resolution
- All disagreements were resolved through discussion.
- Senior author consulted when necessary, following Kitchenham and Brereton’s guidance.

### 📊 Screening Outcome
- **71 studies excluded**, **55 studies included** in the final review.
- **PRISMA flow diagram** summarizes the search and screening process.

![PRISMA diagram](/prisma.png)
_PRISMA diagram summarizing the screening process._

## Records

The complete screening results of all articles is available in this repository. 
> [screening_results_all_records.csv](/screening_results_all_records.csv).
