# Systematic Literature Review Protocol

The complete results of all articles is available in this repository. 
1. [screening_results_all_records.csv](/screening_results_all_records.csv) : contains all 5K titles from literature searching including the individual votes and verdicts for each article at all screening stages.
2. [data_extraction.csv](/data_extraction.csv) : contains the data extracted from selected articles.
3. [quality_assessment_result.csv](/quality_assessment_result.csv) : contains the results of quality assessment based on the protocol and verbatim checklist from the following paper. See [the list of quality assessment checklist](#quality-assessment-checklist).
> Kitchenham, B., & Brereton, P. (2013). A systematic review of systematic review process research in software engineering. Information and Software Technology, 55(12), 2049–2075. https://doi.org/10.1016/j.infsof.2013.07.010

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

### Independent Screening Process
- Two junior authors screened **5,8K article titles** independently.
- Votes were consolidated and **Cohen’s kappa coefficient** was calculated at checkpoints to assess inter-rater agreement.

### Discrepancy Resolution
- When low agreement was detected:
  - Authors shared screening experiences.
  - Misunderstandings were clarified.
  - Conflicting articles were revisited separately.
- This process led to a **Cohen’s kappa of 0.853**, indicating **almost-perfect agreement**.

### Screening Outcome
- **293 articles** were mutually agreed upon for abstract screening.
- **5 articles** lacked abstracts (labeled E9), leaving **288 articles** for the next phase.

## Abstract Screening Summary

### Second Screening Round
- Two junior authors screened **288 articles** using titles and abstracts.
- Abstracts provided additional context to verify assumptions from the first round.

### Inclusion for Further Review
- Articles with unclear abstracts were retained for full-text screening.
- Discrepancies resolved through discussion with a senior author, following Kitchenham and Brereton’s guidance.

### Screening Outcome
- **162 articles excluded**, **126 articles** advanced to full-text screening.
- Low exclusion rate indicates high quality of initial title-based selection.

## Full-Text Screening Summary

### Third Screening Round
- Two junior authors screened **126 full-text articles** for eligibility.
- Each excluded article was labeled with its **main exclusion reason**, based on exclusion criteria from the previous section.

### Discrepancy Resolution
- All disagreements were resolved through discussion.
- Senior author consulted when necessary, following Kitchenham and Brereton’s guidance.

### Screening Outcome
- **71 studies excluded**, **55 studies included** in the final review.
- **PRISMA flow diagram** summarizes the search and screening process.

### Exclusion Reasons

| ***Exclusion Reason*** | ***Count of Studies*** |
| :--- | ---: |
| E6. Technique not feasible for consumers | 45 |
| E8. Literature review, editorial, comment, etc. |  13 |
| E7. Not focused on risk aspects | 4 |
| E4.2 Cloud only as an enabler | 3 |
| E5. Only cloud implementation or use case | 3 |
| E4.1 Focus on other technology/concept | 2 |
| E3. Decentralized cloud | 1 |
| **Total** | **71** |

## PRISMA Diagram

![PRISMA diagram](/prisma.png)

_PRISMA diagram summarizing the screening process._

## Quality Assessment Checklist

QA1.	Is there a clear statement of the aims of the study?\
QA2.	Is there an adequate description of the context in which the research or observation was carried out?\
QA3.	Was the research method appropriate to address the aims of the research?\
QA4.	Was the recruitment strategy (for human-based experiments and quasi-experiments) or experimental material or context (for lessons learnt) appropriate to the aims of the research?\
QA5.	For empirical studies (apart from Lessons Learnt), was there a control group or baseline with which to evaluate risk management techniques?\
QA6.	For empirical studies (apart from Lessons Learnt), was the data collected in a way that addressed the research issue?\
QA7.	For empirical studies (apart from Lessons Learnt), was the data analysis sufficiently rigorous?\
QA8.	Has the relationship between researcher and participants been considered to an adequate degree?\
QA9.	Is there a clear statement of findings?\
QA10.	Is the study of value for research or practice?


## Records

The complete screening results of all articles is available in this repository. 
> [screening_results_all_records.csv](/screening_results_all_records.csv).
