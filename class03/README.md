# 500 Class 03: 2026-01-29

[Main Site](https://thomaselove.github.io/500-2026/) | [Calendar](https://thomaselove.github.io/500-2026/calendar.html) | [Syllabus](https://thomaselove.github.io/500-syllabus-2026/) | [Contact Us](https://thomaselove.github.io/500-2026/contact.html) | [Canvas](https://canvas.case.edu) | [Get Data](https://github.com/THOMASELOVE/500-data) | [Sources](https://github.com/THOMASELOVE/500-sources)
:-----------: | :--------------: | :----------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | HTML | Quarto | Recording
:---: | :--------: | :------: | :------: | :-------------:
03 | 2026-01-29 | **[Slides 03](https://thomaselove.github.io/500-slides-2026/500-slides03.html)** | **[Quarto 03](https://thomaselove.github.io/500-slides-2026/500-slides03.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- The HTML link provides the slides that I will use during class. To print the slides to PDF, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf).
- The Quarto link downloads the Quarto code (.qmd file) I used to build the slides.

---

## Announcements

1. An answer sketch for [Lab 1](https://thomaselove.github.io/500-2026/lab1.html) is now available our **Shared Drive** (500 Spring 2026 Students and Dr Love). Sarah will post grades and individual feedback on Canvas as she completes her assessments.
    - Note that [Lab 2](https://thomaselove.github.io/500-2026/lab2.html) is due on 2026-02-24.
2. Today's class will include a discussion of Chapter 4 (Adjustments for Measured Covariates) from Rosenbaum *Causal Inference*. See some thoughts below.
3. Much of next week's class 4 will focus on learning how to use R to do propensity score analyses, following [the Toy Example](https://thomaselove.github.io/500-examples/#the-toy-example) from our [500-examples page](https://thomaselove.github.io/500-examples/).
4. Prior to our next class, we want you to read Rosenbaum Chapter 5 (Sensitivity to Unmeasured Covariates) and skim through [Normand 2001](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Normand%20et%20al%202001%20Propensity%20Score%20Matching%20Analysis%20on%20Acute%20MI%20in%20Elderly%20Patients.pdf)
5. Please be sure to email me your [OSIA selections](https://thomaselove.github.io/500-2026/osia.html) by Noon on 2026-02-10.
    - We'll spend a moment today to discuss the [OSIA (Observational Studies in Action) assignment](https://thomaselove.github.io/500-2026/osia.html).
    - Current selections [are posted here](https://github.com/THOMASELOVE/500-classes-2026/tree/main/osia).
6. It would be very wise to have your [Project Data](https://thomaselove.github.io/500-2026/proj500.html) ingested into R by class time on 2026-02-12, so that you won't have trouble completing your [Project Proposal](https://thomaselove.github.io/500-2026/proj500.html) by 2026-03-03.

---

## Three Focal Points from Rosenbaum Chapter 4 (Adjustments for Measured Covariates) for your consideration

- The importance of balance in measured covariates for eventual assessment of outcomes after (for example) building a matched sample.
- How *matching* on the propensity score improves that covariate balance.
- Comparing outcomes after matching (on the propensity score, and/or something else.)

### Our Usual Three Questions for Discussion as a Small Group

1. What was the most important thing you learned from reading Chapter 4?
2. What was the muddiest, least clear thing that arose in your reading?
3. What questions are at the front of your mind now?

---

## Sources from Today's Slides

### Available on our [Sources Page](https://github.com/THOMASELOVE/500-sources)

1. Connors Alfred F et al. 1996 [The Effectiveness of Right Heart Catheterization in the Initial Care of Critically Ill Patients](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Connors%20et%20al%201996%20JAMA%20The%20Right%20Heart%20Catheterization%20Study.pdf) *Journal of the American Medical Association*
2. Rubin Donald B 2004 [On principles for modeling propensity scores in medical research](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Rubin%202004%20editorial%20Pharmacoepidemiology%20and%20Drug%20Safety%20on%20Propensity%20Score%20Principles.pdf) *Pharmacoepidemiology and Drug Safety*
3. Weitzen Sherry et al. 2004 [Principles for modeling propensity scores in medical research: A systematic literature review](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Weitzen%20et%20al%202004%20Systematic%20Literature%20Review%20of%20Propensity%20Score%20Usage.pdf) *Pharmacoepidemiology and Drug Safety*
4. Weitzen Sherry et al. 2005 [Weaknesses of goodness-of-fit tests for evaluating propensity score models: the case of the omitted confounder](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Weitzen%20et%20al%202005%20Why%20goodness%20of%20fit%20tests%20aren't%20appropriate%20for%20evaluating%20propensity%20score%20models.pdf) *Pharmacoepidemiology and Drug Safety*
5. Rosenbaum Paul E and Rubin Donald B 1983 [The Central Role of the Propensity Score in Observational Studies for Causal Effects](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Rosenbaum%20and%20Rubin%201983.pdf)
6. Rosenbaum Paul E and Rubin Donald B 1984 [Reducing Bias in Observational Studies using Subclassification on the Propensity Score](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Rosenbaum%20and%20Rubin%201984%20JASA.pdf)
7. Rosenbaum Paul E and Rubin Donald B 1985 [Constructing a Control Group using Multivariate Matched Sampling Methods that incorporate the Propensity Score](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Rosenbaum%20and%20Rubin%201985.pdf)
8. Gum Patricia A et al. 2001 [Aspirin Use and All-Cause Mortality among Patients being Evaluated for Known or Suspected Coronary Artery Disease](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Gum%202001%20JAMA%20Aspirin%20Use%20Propensity%20Analysis.pdf) *Journal of the American Medical Association*
9. D'Agostino Ralph B Jr. 1998 [Tutorial in Biostatistics: Propensity Score Methods for Bias Reduction in the Comparison of a Treatment to a Non-Randomized Control Group](https://github.com/THOMASELOVE/500-sources/blob/main/articles/D'Agostino%201998%20SIM%20Tutorial%20on%20Propensity%20Scores.pdf) *Statistics in Medicine*
10. Rubin Donald B 2001 [Using Propensity Scores to help Design Observational Studies: Application to the Tobacco Litigation](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Rubin%202001%20Tobacco%20Litigation%20article.pdf) *Health Services & Outcomes Research Methodology*


### Not posted to our Sources page

1. McCaffrey et al 2004 Propensity score estimation with boosted regression for evaluating causal effects in observational studies [PubMed](https://pubmed.ncbi.nlm.nih.gov/15598095/)
2. Brookhart 2006 Variable selection for propensity score models [PubMed](https://pubmed.ncbi.nlm.nih.gov/16624967/)
3. D'Agostino and Rubin 2000 [Estimating and Using Propensity Scores with Partially Missing Data](https://www.jstor.org/stable/2669455)

## Sources for Next Time include...

1. Normand Sharon-Lise T et al. 2001 [Validating recommendations for coronary angiography following acute myocardial infarction in the elderly: A matched analysis using propensity scores](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Normand%20et%20al%202001%20Propensity%20Score%20Matching%20Analysis%20on%20Acute%20MI%20in%20Elderly%20Patients.pdf) *Health Services & Outcomes Research Methodology*
2. Our [500-examples page](https://thomaselove.github.io/500-examples/)

--------

Please contact us at **500-help at case dot edu** if you have any questions.
