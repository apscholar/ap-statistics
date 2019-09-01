---
date: "2019-05-05T00:00:00+01:00"
draft: true
linktitle: Tips 3-4
menu:
  example:
    parent: Example Topic
    weight: 2
title: Example Page 2
toc: true
type: docs
weight: 2
---



# Research Question {#intro}

You can label chapter and section titles using `{#label}` after them, e.g., we can reference Chapter <a href="#intro">1</a>. If you do not manually label them, there will be automatic labels anyway, e.g., Chapter <a href="#qualmethods">8</a>.

Figures and tables with captions will be placed in `figure` and `table` environments, respectively.

<!-- You can write citations, too. For example, we are using the **bookdown** package [@R-bookdown] in this sample book, which was built on top of R Markdown and **knitr** [@xie2015]. -->



# Literature Review

List resources for conducting literature review.
Show example of literature review with inline citations.
Show ways to keep track of sources for bibliography.

* [How to Write a Literature Review](https://writing.wisc.edu/handbook/assignments/reviewofliterature/)
    - contains example literature reviews from political science, philosophy, and chemistry.
    
Consider using a reference management system like Mendeley to organize your sources as you conduct your literature review. In fact, Mendeley has a Literature Search function, so you can manage sources and conduct literature reviews at the same time. See the Bibliography Management Section for more information on managing sources.

* Databases for Literature Reviews

    - [Directory of Open Access Journals](https://doaj.org/subjects)
        + Browse by subjects in the humanities and sciences. This can be your starting point if you have not developed a research topic.
    
    - [arXiv](https://arxiv.org/)
        + Open-access journal articles in fields such as mathematics, statistics, economics, physics, quantitative biology, quantiative finance, and electrical engineering
        + [arXiv to BibTex](https://arxiv2bibtex.org): Outputs automated citations in BibTeX and other formats by typing the arXiv number of the article. For instance, just type in 1905.03758 into the search engine if the article is labeled arXiv: 1905.03758.
        + Alternatively, use [Mendeley Web Importer](https://www.mendeley.com/reference-management/web-importer#id_2) to import article into Mendeley Desktop for automated citation outputs.
        
    - [Mendeley Literature Search](https://blog.mendeley.com/2013/07/08/new-release-literature-search-from-within-mendeley-deskop/)
        + Download [Mendeley Desktop](https://www.mendeley.com/download-desktop/) and register for a free account. Mendeley Desktop syncs with your online Mendeley account, but the literature search is currently only available in the desktop version.
        + Mendeley is primarly a reference managements software, so you can organize your citations as you conduct your literature review.
    
    - [CORE](https://core.ac.uk/)
        + Search engine with the world's largest collectin of open-access research papers.
        + For batch searches of metadata and full texts, you may consider requesting a free API key to use the [Core API](https://core.ac.uk/services/api/).
        
    - [ScienceOpen](https://www.scienceopen.com)
        + Search for content, authors, collections, and journals in the [advanced search](https://www.scienceopen.com/search#advanced), where you have the option to search by discipline or key word.
        
    - [Dimensions](https://app.dimensions.ai/discover/publication)
        + Search for articles in clincial sciences, biochemistry, public health, physical chemistry, and materials engineering.
        
    - [EBSCO Open Access](https://www.ebsco.com/open-access)
        + Search open-access journals and dissertations. Note that dissertations can vary in quality, since they have not gone through peer review. 
        + AP Research students should have access to a free EBSCO account from the AP Capstone program.
    
    - [SSRN](https://papers.ssrn.com/sol3/DisplayJournalBrowse.cfm)
        + Many of the social science articles are free access. 
        
    - [ERIC: Institute of Educadtion Sciences](https://eric.ed.gov/)
        + Search for articles related to to education research.
        + The search engine includes the open to search for full-text articles.
        
    - [dblp: Computer Science Bibliography](https://dblp.org/)
        + Index of major computer science publications.
        + Option to search for open-access articles.
    
    - [EconBiz](https://www.econbiz.de/)
        + Search for journal articles, working papers, and conference papers in economics and business.
        + Option to search for open-access articles.
        
    - [MyJSTOR](https://support.jstor.org/hc/en-us/articles/115004760028-MyJSTOR-How-to-Register-Get-Free-Access-to-Content)
        + You can sign up for a free MyJSTOR account to access up to six articles a month for free.
        + This may be helpful for accessing articles that are not open access.
        
* Tips for Accessing Paywalled Articles

    - Search for the author's website. Many researchers have draft manuscripts on their websites or research profiles on sites such as [ResearchGate](https://www.researchgate.net/).
    - Consult your school's research librarian for other ways to access the article.
    - Send the author an e-mail to request for a digital copy of the article. You should provide context in the e-mail request by including a brief description of your AP Research project and its relevance and connection to the author's article.


# Bibliography Management

While the bibliography is placed at the end of research papers, reference management begins as soon as you begin your literature review.

* [Managing Citations in LaTeX](https://guides.library.yale.edu/bibtex/bibstyles)

* [Mendeley Desktop Download](https://www.mendeley.com/download-desktop/)

    - The download will prompt you to create a free account. Mendeley Desktop is synced with your online account.
    
* [Mendeley Web Importer](https://www.mendeley.com/reference-management/web-importer#id_2)

    - As you search for research articles online, you can use the Mendeley Web Importer to import citations into your Mendeley Desktop. If the importer can recognize the online article's metadata, it will automatically populate the citation entries. If not, you can still enter the citation entries manually and import into the Mendeley Desktop to keep track of your sources.
    
* [Mendeley Tutorials](https://guides.library.yale.edu/mendeleybasics/mendeley/mendeley-desktop)

* Exporting .bib files from Mendeley Desktop
* Install MS Word plugin
* [Import Mendelay sources into LyX](https://onhavingwords.wordpress.com/2013/03/19/mendeley-lyx/)

* [Import .RIS Files into Mendeley](https://libguides.nus.edu.sg/c.php?g=145734&p=1433095)
  
# Paper Guidelines

* [AP Research Proposal Guidelines](https://www.overleaf.com/read/ncvzdvcvfxdx)
* [AP Research Paper Guidelines (LaTeX)](https://www.overleaf.com/read/hxctjpdnvffw)
    + draft in progress

# File Organization


# Research Concepts

## Reliability & Validity
## Accuracy vs. Precision
## Bias vs. Variance Tradeoff

  * [Understanding the Bias-Variance Tradeoff](https://towardsdatascience.com/understanding-the-bias-variance-tradeoff-165e6942b229)
      - As you introduce more variables to a model, bias tends to decrease. This means that on average the model will make predictions closer to the true value. 
      - However, at the same time, variance tends to increase with the added variables. This means that each time you input the model with another random set of data, the outputted predictions will vary a lot. Why? More variables in the model means you might be in danger of overfitting your specific data. This means your model is so specifically tailored to your data at hand that it probably won't generalize well if you applied the model to other randomly drawn datasets.

      
## Curse of Dimensionality
## Correlation vs. Causation


# Research Design

Before you decide how you will conduct your research, read through the [list of research designs](https://libguides.usc.edu/writingguide/researchdesigns) in the USC library guide.

  * [What is Research Design?](https://www.nyu.edu/classes/bkg/methods/005847ch1.pdf)

## Action
## Case Study

## Case-Control Study

  * [Case-Control Studies](https://sph.unc.edu/files/2015/07/nciph_ERIC5.pdf)
      - The diagram on the first page provides a clear overview of case-control study design.
  * [Overview of Case-Control Design](http://sphweb.bumc.bu.edu/otlt/MPH-Modules/EP/EP713_Case-Control/EP713_Case-Control_print.html)
      
## Causal
## Cohort
  
  1. Sample a cohort of people from a population of interest
  2. Follow this cohort for many years (often decades)
  3. Record their attributes and exposures.
  4. Record who develops outcome of interest (ongoing process).
  
  * This method can be costly, both monetarily and time-wise.
  * Compare this method with case-control studies, which are a type of observational study often used in epidemiology.

  
## Cross Sectional
## Descriptive
## Experimental
## Exploratory
## Historical
## Longitudinal
## Meta-Analysis
## Mixed Methods
## Observational
## Philosophical
## Sequential
## Systematic Review

## Quasi-experimental



# Qualitative Research Methods {#qualmethods}

- [Qualitative Research Methods Field Guide](https://course.ccs.neu.edu/is4800sp12/resources/qualmethods.pdf)

## Case Study
## Narrative
## Phenomenological
## Ethnography
## Grounded Theory

  * [Grounded Theory as Scientific Method](https://pdfs.semanticscholar.org/5886/43f9ded159acc42daeefed6f1d1952bea546.pdf)

# Quantitative Methods

## Causal Inference {-}

These notes are based on Professor Masten's [online course](https://modu.ssri.duke.edu/topic/introduction-causal-inference) on Causal Inference at the Social Science Research Institute at Duke.

  * Causal effect is often easy to detect with simple actions for which the effect immediately follows (e.g., you caused the alarm clock to stop ringing by pressing the snooze button)
  * With multiple causes and delayed effects, causality is much harder to detect.
  
  * Measurement:
    - Unit of analysis: countries, city blocks, people, firms, etc.
    - Outcome variable: the characteristic of the unit of analysis that we want to affect
    - Policy/treatment variable: the characteristic that we use to change the outcome varialbe
  * A lot of characteristics cannot readily be quantified, so we often use proxy variables. For example, GDP could be a proxy for economic development.
  * Causality: how an intervention in the policy variable affects the outcome variable
  
  * Data:
    - The value of the policy variable has to vary in the dataset. Without this variation, you can't analyze how changes in the policy variable might affect the outcome variable.
    - Larger standard deviation = larger variation
  
  * Correlation vs. Causation
    - If the policy and outcome variables are correlated, this does not necessarily imply a casual relationship.
    - Selection Problem: when units get to choose their policy variable, correlations between policy and outcome variables are unlikely to be causal.
      + Example: Neighborhoods with a lot of trees tend to have less crime.
      + If this were a casual relationship, then we could plant more trees in a neighborhood and expect crime to go down. However, this is unlikely. More likely, people who tend to commit less crimes chose to live in neighborhoods with tree-lined streets.
      
  * Average Treatment Effect
    - Causal effects vary among people, so there is a distribution of causal effects in the population.
    - Theoretical ideal: you would know the unit level of causal effect for each person and thus make individualized treatment decisions. This is impossible in practice. You can't know the effect of receiving and not receiving treatment for an individual.
    - Unit-level causal effect: difference in outcome between treatment & control, holding all other variables fixed
    - Avg. treatment effect (ATE): avg. of all values for unit-level causal effects in a population
    - Avg. outcome under the policy: avg. outcome when everyone is affected by the policy (i.e., receives treatment)
    - Avg. outcome without the policy: avg. outcome when everyone is not affected by policy (i.e., does not receive treatment)
    - ATE = Avg. outcome under policy - Avg. outcome w/o policy
  

### Experiments

  * Controlled Experiments
    - Control group does not receive treatment
    - Experimental group receives treatment
    - All possible factors that could affect the outcome are identical for both groups, except for the treatment
    - Difference in the outcome between the two groups is the treatment effect
    - Typically used in hard sciences, but difficult to achieve in social sciences given the myriad of factors, many of which are difficult to measure and control
  
  * Randomized Experiments
      - Split units randomly into two large groups: treatment or control
      - Right after randomization and before the experiment, both groups should be similar (i.e., avg. values of factors should be about the same), because the split was done randomly and the groups are very large
      - Since the two groups are similar in all factors except treatment, changes in the *average* outcomes are due to treatment
      - Complications:
          + Noncompliance: Even when you randomly assign treatment, people in the treatment group may not all decide to take the treatment. Also, some people in the control group, who should not receive the treatment, might decide to get the treatment. 
              * Solution 1: Intent to Treat Analysis
                  - The *intent* to provide treatment is by design random regardless of treatment non-compliance.
                  - Thus, we can examine the causal effect of the option of providing treatment.
                  - Downside: cannot analyze causal effect of treatment itself
                  - For example, in the Oregon Health Experiment, while a lottery randomly selected people to receive free Medicaid, there was noncompliance in both the treatment/control groups. Original interpretation (effect of Medicaid on health outcomes) can be revised to effect of Medicaid lottery assignment on health outcomes.
                  
              * Solution 2: Instrumental Variables
                  - Advantage: We can analyze the causal effect of the treatment (not just the option of treatment) for a subset of the population.
                  - Downside: cannot analyze average treatment effect over the entire population
              * Solution 3: Assume random compliance
                  - Assume people comply with their treatment assignment.
                  - Just drop the entries of the non-compliers.
                  - Advantage: We can analyze the causal effect of the treatment over the entire population.
                  - Downside: Decision to not comply is probably not random. We don't observe the reasons for non-compliance.
              * Solution 4: Bounds analysis
                  - Get lower/upper bounds of average treatment effects using extreme scenarios.
                  - Upper bounds: assume maximum value for outcome variable for noncompliers
                  - Lower bounds: assume minimum value for outcome variable for noncompliers
          + Survey nonresponse
              * If nonresponse is not random, you cannot interpret the treatment effect as causal.
              * Example: People in the treatment group with negative outcomes responded to surveys at higher rates than those with positive experiences. Data becomes biased toward negative outcomes for the treatment group.
          + Sample Size: Even with a great research design, small sample size limits statistical inference.
          + Control: You may not be able to control the assignment of treatment.
          
      - Issues:
          + Ethics: Random assignment of treatment may have difficult ethical considerations (e.g., withholding a potentially life-saving drug to a terminally ill patient assigned to a control group in a randomized trial).
          + Extrapolation: It may be hard to extrapolate the results of a randomized experiment to another study if the treatment conditions and features are different.
  
  * Natural Experiments
      
      - Researchers not involved in the research design and data collection in natural experiments, unlike in randomized experiments.
      - observational data used instead
      - Example: charter school lotteries
      
      1. True Natural Experiments
          + treatment was randomly assigned, just not by researcher

      2. As-If Natural Experiments
          + treatment not actually randomly assigned, but the treatment/control groups appear randomized as though treatment assignment were random)
          + treatment assignment not related to any variables that could affect outcome
          + balance check: characteristics of all observed variables (other than outcome variable) need to be similar between the treatment/control groups
              - There could still be differences between groups in unobserved variables.
              - Thus, we cannot prove treatment assignment is truly random, but balanced observed variables between groups would be part of a convincingly arugment that the observational data represents an as-if natural experiment.

### Regression

In general, regression analysis can show only correlations between variables but not causation. The following are some factors that would prevent you from making the leap from correlation to causation in regression analysis:

1. Confounding Variables
  
  * A confounding variable is a hidden variable that has an influence on both the dependent variable and independent (or outcome) variable.
  * This distorts the asssocation between the dependent and independent variable.
  * Example: Suppose we want to test the effect of the number of books at home (dependent variable) on a child's reading proficiency (independent variable). A confounding factor could be the mother's level of education, which could effect both the number of books at home and the child's reading proficiency. Without accounting for the mother's level of education, we could be overstating the effect of books on reading proficiency.

  
2. Reverse Causality

  * In your study of the effect of A on B, you spot an association between the two variables. However, the direction of causality acturally could be reversed (i.e., B has an effect on A).
  * Example: Suppose you notice that as the debt of a country increases, its economic growth decreases. The cause-and-effect relationship could be the other way around. Maybe a faltering economy is the reason that countries have to accumulate more debt to meet their budgets.

3. Simultaneity

  * Similar to reverse causality, except that that direction of causality goes both ways at the same time. X causes Y, and Y causes X.

4. Mediating Variable

  * Example: Does consuming caffeine stunt children's growth? We might question this causal link if we examine the mediating variable of sleep duration. Perhaps drinking coffee disrupts sleep patterns, which in turn affects growth.
  
**Unconfoundedness Assumption**

  * Under the unconfounded assumption (a.k.a. **selection on observables assumption**), we have controlled for enough variables that we assume no confounding variables exists. With this assumption, we can consider the association between the treatment and outcome variable to be causal, since conditioning on all the other variables makes the treatment assignment essentially random.
  
  * In practice, this assumption is difficult to make, because we cannot truly account for every possible variable relevant to the outcome variable. You would have to assume that all unobserved variables are not related to the treatment and do not contribute any effects to the outcome variable.

**Ordinary Least Squares (OLS) Regression**

  * In OLS regressions, we want to draw a line through a set of points that represents the data.
  * We calculate the distance between each data point and the line. We then square that distance. Do this for all data points and find the sum of all thes squared distances.
  * The OLS regression line is the line that minimizes the sum of all these squared distances.
  * Assumptions:
      - sample is random
      - outcome variable is continuous

**Interaction Effects**

  * If an independent variable `\(z\)` changes the effect of another independent variable `\(x\)` on the outcome variable `\(y\)`, we have an **interaction effect** between `\(x\)` and `\(z\)`. The original regression model `\(y=\beta_0 +\beta_1 x + e\)` turns into `\(y=\beta_0 +\beta_1 x + \beta_2z + \beta_3~x*z + e\)`.
  
  * This concept is also called **statistical moderation**, since `\(z\)` moderates the effect of `\(x\)` on `\(y\)`.

**Calculating Average Treatment Effects**


```
## 
## Attaching package: 'dplyr'
```

```
## The following objects are masked from 'package:stats':
## 
##     filter, lag
```

```
## The following objects are masked from 'package:base':
## 
##     intersect, setdiff, setequal, union
```


-------------------------------------------------------------------------------------
 Person   Gender   Treated     Outcome        Outcome        Unit-Level     Observed 
                             with Policy   without Policy   Causal Effect   Outcome  
-------- -------- --------- ------------- ---------------- --------------- ----------
   1        M         Y          80              60              20            80    

   2        M         Y          75              70               5            75    

   3        M         Y          85              80               5            85    

   4        M         N          70              60              10            60    

   5        F         Y          75              70               5            75    

   6        F         N          80              80               0            80    

   7        F         N          90             100              -10          100    

   8        F         N          85              80               5            80    
-------------------------------------------------------------------------------------

Table: Table 1  Potential Outcomes of Treatment by Gender

  * In the example table above, we have two potential outcomes for each person: `Outcome with Policy` and `Outcome without Policy`. In practice, you would never be able to observe both potential outcomes for each person. You either observe `Outcome with Policy` if the person received treatment or `Outcome without Policy` if the person did not receive treatment. In actual data, you would only obtain `Observed Outcome`.
  * Unit-Level Causal Effect = Outcome with Policy - Outcome without Policy
  * Average Treatment Effect (ATE) = average of all the unit-level causal effects
      - Using the example data above, ATE `\(= \frac{20+5+5+10+5+0-10+5}{8}= 5\)`.
  * Conditional Avg. Treatment Effect (CATE) = average treatment effect for a subset of the units
      - Example: CATE for men is `\(\frac{20+5+5+10}{4} = 10\)`.
      - Example: CATE for women is `\(\frac{5+0-10+5}{4} = 0\)`.
  * Average Treatment Effect on the Treated (ATT) = average treatment effect for only the people who received treatment
      - In the table above, Persons 1, 2, 3, and 5 received treatment.
      - To calculate ATT, we take the average of the unit-level causal effects of these treated people.
      - ATT `\(= \frac{20+5+5+5}{4} = 8.75\)`
  * Difference in Mean Outcomes b/w Treated and Untreated (Control) Groups = ATT + Bias
      - left-hand side (LHS) = `\(\frac{80+75+85+75}{4}-\frac{60+80+100+80}{4} =\)` -1.25
      - ATT = 8.75
      - Bias = difference in the averages in `Outcome without Policy` between treated and untreated groups
          + If this bias term is nonzero, we can say that the data has **selection bias**, because the selection into treatment is associated with potential outcomes.
          + For `Treated = Y`, average `Outcome without Policy` = `\(\frac{60+70+80+70}{4}\)` = 70.
          + For `Treated = N`, average `Outcome without Policy` = `\(\frac{60+80+100+80}{4}\)` = 80.
          + Bias = 70 - 80 = -10.
          + In this example, people selected for treatment have a much lower potential outcome without treatment than that of people not selected for treatment.
          + This negative selection bias will understate the actual impact of the treatment.
          + Similarly, positive selection bias will overstate the actual impact of the treatment.
      - right-hand side (RHS) = ATT + Bias = `\(8.75 - 10 = -1.25\)`
      - Thus, LHS = RHS.
      - In randomized experiments, the assignment of treatment is randomized, making the selection bias zero. Thus, the LHS (difference in the mean observed outcomes between the treated/untreated groups) equals ATT. Note that ATT is the average treatment effect (ATE) conditioned on being in the treatment group. Under randomization, we can assume that the potential outcomes are independent of the treatment assignment, so the average treatment effect is the same regardless of conditioning on treatment assignment. Thus, LHS = ATT + zero bias = ATE.
      - In this example data, we know that treatment is not randomly assigned, since more men received treatment than women. This means that treatment is correlated with gender. Thus, the calculations done above *do not* represents estimates of the average treatment effect due to the selection bias.
      - Instead, we assume that treatment assignment is randomized within each gender group. We calculate the estimated conditional average treatment effects `\(\widehat{CATE}(m)\)` and `\(\widehat{CATE}(f)\)` for males and females, respectively, by taking the difference between the average treatment group outcome and the average control (untreated) group outcome *within* each gender.
          + `\(\widehat{CATE}(m) = \frac{80+75+85}{3}-60 = 20\)`
          + `\(\widehat{CATE}(f) = 75 - \frac{80+100+80}{3} = -11.67\)`
      - We add a hat on top of CATE to denote that the calculations are estimates. These estimates `\(\widehat{CATE}(m)=20\)` and `\(\widehat{CATE}(f)=-11.67\)` are different from `\(CATE(m)=10\)` and `\(CATE(f)=0\)` that we calculated earlier. The CATEs without the hats are the true conditional average effects based on the difference in the two potential outcomes (with/without treatment) for each person. In practice, we will never be able to calculate the true CATEs, because we can never know both potential outcomes for each person. We only have one observed outcome for each person that we use to estimate CATE with `\(\widehat{CATE}\)`.
      - To estimate ATE, we take the weighted average of the estimated CATEs. In this case, both gender groups are equally weighted, so `\(\widehat{ATE} = \frac{1}{2}\widehat{CATE}(m)+\frac{1}{2}\widehat{CATE}(f) = 20 - 11.67 = 4.16\)`.
      - Note that `\(\widehat{ATE} = 4.16\)` is positive, whereas earlier calculation of LHS (difference in the mean observed outcomes in the treated/untreated groups) is negative, which understates the average treatment effect due to negative selection bias arising from non-random assignment of treatment between gender.

### Matching Methods

In this method, we want to find units with similar explanatory variables but assigned to different treatments. One way to do this is propensity score matching. 

### Instrumental Variables



## Statistical Tests {#stat}

  * [Choosing a Statistical Test](http://rcompanion.org/handbook/D_03.html)
  * [Hypothesis Testing Roadmap](http://www.bmgi.org/sites/bmgi.org/files/HTR%20MT17.pdf)
  * [Chosing the Correct Statistical Test in SAS, Stata, SPSS, and R](https://stats.idre.ucla.edu/other/mult-pkg/whatstat/)
  * [Uses & Misuses of Statistics](http://influentialpoints.com/Training/statistical_mistakes_in_research_use_and_misuse_of_statistics_in_biology.htm)
  * [Statistical Tests in R](http://r-statistics.co/Statistical-Tests-in-R.html)
  
  * 1 group
      - interval variables
          + 1-sample t test for the mean
          + chi-squared test for variance
      - categorical variables
          + z test for proportions (2 categories)
          + chi-squared goodness-of-fit
      - ordinal or interval
          + one-sample median test
          
  * 2 groups (independent groups)
      - interval variables
          + 2 independent sample t-test (equal variances)
          + 2 independent sample t-test (unequal variances)
          + F test for difference between 2 variances
      - categorical variables
          + z test for difference between 2 proportions
          + chi-squared test for difference between 2 proportions
          + Fisher's exact test
          
  * 2 groups (dependent or paired groups)
      - paired t-test (interval variables)
      - McNemar's test (categorical variables)
      - Wilcoxon signed ranks test (oridinal or interval variables)

  * more than 2 groups (independent groups)
      - one-way ANOVA (for interval variables)
      - Kruskal Wallis (for ordinal or interval variables)
      - chi-squared test (for categorical variables)
      
  * more than 2 groups (dependent groups)
      - one-way repeated measures ANOVA (for interval variables)
      - repeated measures logistic regression (for categorical variables)
      - Friedman test (for ordinal or interval)
          
### 1-sample t-test

  * Assumptions:
      - data is a simple random sample from population 
      - sample mean follows a normal distribution 
      - by the Central Limit Theorem, with sample size `\(n>=30\)`, the sample mean is normally distributed regardless of the population distribution

  * Two-tailed Hypothesis:
  $$ H_0: \mu = \mu_0 $$
  $$ H_1: \mu \neq \mu_0 $$

  * Test Statistic:
  $$ T = \frac{\overline{X}-\mu_0}{\frac{S}{\sqrt{n}}} \sim t_{(n-1)} $$

      - `\(\overline{X}\)` = sample mean
      - `\(\mu_0\)` = hypothesized population mean
      - `\(S\)` = sample standard deviation
      - `\(t_{(n-1)}\)` = `\(t\)` distribution with `\(n-1\)` degrees of freedom

### chi-squared test for variance

### z test for proportions

  * Assumptions:
      - sample proportion `\(p = \frac{X}{n}\)` comes from random sample in population, where `\(X\)` is number of events of interest in sample size `\(n\)`.
      - `\(p\)` follows a binomial distribution, but we can assume normality when `\(X\)` and `\(n-X\)` are each at least 5 (old standards) or at least 15 (current standards)
  * Two-tailed Hypothesis:
  $$ H_0: \pi = \pi_0 $$
  $$ H_1: \pi \neq \pi_0 $$

  * Test Statistic:
  $$ z = \frac{p-\pi_0}{\sqrt{\frac{\pi_0 (1-\pi_0)}{n}}} \sim \mathcal{N}(0,1) $$

    - `\(\pi_0\)` = hypothesized proportion
    - `\(p\)` = sample proportion
    
### t-test for 2 independent samples

  * Assumptions:
      - two independent samples are randomly selected from two populations with the same variance
      - if you cannot use the assumption of same variance, use the Welch two-sample t-test
        + test statistic is the same as below, but degrees of freedom are adjusted
        
      - if populations are not normally distributed, the sample sizes `\(n_1\)` and `\(n_2\)` from the two populations needs to be at least 30 to ensure that the distribution of the sample means are normal by the Central Limit Theorem
  * Two-tailed Hypothesis:
    $$ H_0: \mu_1 = \mu_2 $$
    $$ H_1: \mu_1 \neq \mu_2 $$

    - `\(\mu_1\)` = population mean of 1st sample
    - `\(\mu_2\)` = population mean of 2nd sample
  * Test Statistic:
  $$ \frac{ (\overline{X}_1-\overline{X}_2) - (\mu_1 - \mu_2) }{ \sqrt{S_p^2 \left( \frac{1}{n_1} + \frac{1}{n_2} \right) } } \sim t_{(n_1 + n_2 -2)} $$
  $$ S_p^2 = \frac{(n_1-1)S_1^2 + (n_2-1)S_2^2}{(n_1-1)+(n_2-1)} $$

    - `\(S_p\)` = pooled variance
    - `\(\overline{X}_1\)` = mean of 1st sample
    - `\(\overline{X}_2\)` = mean of 2nd sample
    - `\(S_1^2\)` = variance of 1st sample
    - `\(S_2^2\)` = variance of 2nd sample
  * [More Info](http://www.biostathandbook.com/twosamplettest.html)
  * [R Example](https://rcompanion.org/rcompanion/d_02.html)
    - includes examples under both assumptions of equal and unequal variances
    
    * Andrew Heiss provides a brief [tutorial](https://www.andrewheiss.com/blog/2019/01/29/diff-means-half-dozen-ways/#simulation-based-tests) with frequentist, simulation-based, and Bayesian approaches to comparing means between two groups. Also see Matti Vuorre's [tutorial](https://vuorre.netlify.com/post/2017/01/02/how-to-compare-two-groups-with-robust-bayesian-estimation-using-r-stan-and-brms/#equal-variances-t-test) for more details.
    
    
    
### paired t-test
  * Assumptions:
  
  * [More Info with R Example](http://rcompanion.org/handbook/I_04.html)
  

  
### chi-squared test for proportions

  * The chi-squared test for 2 x 2 frequency tables is equivalent to the square of the z-test for two proportions. See this [link](http://rinterested.github.io/statistics/chi_square_same_as_z_test.html) for detailed explanation.

### chi-squared test for independence

  * Explain connection between chi-squared test for independence and log-linear models, which are Poisson models for categorical data.
  
### ANOVA

  * [F Distribution and Basic Principle Behind ANOVAs](http://www.bodowinter.com/tutorial/bw_anova_general.pdf)
  
## Regression

### Simple Linear Regression

A simple linear regression has the form `\(y=\beta_0 + \beta_1 x + e\)`, where

  * `\(y\)` is the dependent (or outcome) variable
  * `\(x\)` is the indepndent (or explanatory) variable
  * `\(\beta_0\)`, the regression intercept, represents the average value of the outcome variable `\(y\)` when `\(x=0\)`
  * `\(\beta_1\)` is the regression coefficient of `\(x\)`
      - for each 1-unit increase in `\(x\)`, `\(y\)` changes by `\(\beta_1\)`
      - `\(\beta_1\)` is the slope of this regression line
  * `\(e\)` is the error term. Some textbooks will use the variable `\(u\)` instead of `\(e\)` to emphasize that this term includes all unobserved variables.
  
### Multiple Linear Regression

Linear regressions with multiple explanatory variables are called **multiple linear regressions**. If we have `\(n\)` explanatory variables, the multiple linear regression will have the form `\(y=\beta_0 + \beta_1 x_1 + \beta_2 x_2 + ... + \beta_n x_n + e\)`, where

  * `\(\beta_0\)`, the regression intercept, represents the average value of the outcome variable `\(y\)` when all the explanatory variables `\(x_1, x_2,...,x_n\)` are zero.
  * `\(\beta_1\)` represents how much `\(y\)` changes when `\(x_1\)` increases by 1 unit, holding all other explanatory variables constant. The Latin phrase *ceteris paribus*, meaning "other things equal," is often used to describe this concept. This does not mean the other explanatory variables do not change. Rather, we are isolating the effect of `\(x_1\)` on `\(y\)` under the theoretical condition that the other explanatory variables are held constant.
  * This interpretation of `\(\beta_1\)` extends to all the other regresssion coeffients.

### Logistic Regression

  * outcome variable is binary (e.g., 0 or 1; yes or no)
  
### Mixed Effects Models

  * [Linear Models and Linear Mixed Effects Models in R: Tutorial 1](http://www.bodowinter.com/tutorial/bw_anova_general.pdf)
  * [A Very Basic Tutorial for Performing Linear Mixed Effects Analyses: Tutorial 2](http://www.bodowinter.com/tutorial/bw_LME_tutorial2.pdf)
  
  
## Numerical Methods

In AP Calculus, you mostly encountered problems that can be solved analytically. However, in research, many differential equation models do not have analytical forms and must be solved numerically. Matlab is often used in applied math, engineering, and physical sciences for such cases as well as other modeling applications. Octave is an open-source alternative to Matlab. While R not the first language that comes to mind for numerical methods, many [numerical R packages](https://cran.r-project.org/web/views/NumericalMathematics.html) have been developed as well as integration with Matlab, Octave, and Julia.

  * [Numerical Computing with Matlab](https://www.mathworks.com/moler/chapters.html)
      - This site has PDF versions of Cleve Moler's textbook on numerical computing alongside a [video series](https://www.mathworks.com/academia/courseware/learn-differential-equations.html) with lectures on differential equations and linear algebra by Prof. Gilbert Strang and computational video tutorials by Moler.
      
  * [Numerically Solving Differential Euqations with R](http://rstudio-pubs-static.s3.amazonaws.com/32888_197d1a1896534397b67fb04e0d4899ae.html)
  
### Root-Finding Algorithms

  * [Newton-Raphson Method Using R](https://rpubs.com/aaronsc32/newton-raphson-method)
  * [Bisection Method Using R](https://rpubs.com/aaronsc32/bisection-method-r)
  * [Secant Method Using R](https://rpubs.com/aaronsc32/secant-method-r)

### Numerical Solutions to Differential Equations

  * [Integrating ODEs in R](https://kingaa.github.io/thid/odes/ODEs_in_R.pdf)
  * [Euler Method Using Matlab](http://www.ohiouniversityfaculty.com/youngt/IntNumMeth/lecture30.pdf)
  * [Euler Method with Python](http://faculty.washington.edu/heathml/2018spring307/euler_method.pdf)
  * Runge-Kutta Methods
  
  

## Text Analysis

  * [Text Mining with R](https://www.tidytextmining.com/ngrams.html)
  
  * Mosteller and Wallace (1963) and the Federalist Papers
  
      - [How Statistics Solved a 175-Year-Old Mystery About Alexander Hamilton](https://priceonomics.com/how-statistics-solved-a-175-year-old-mystery-about/)
      
      - [Replication of Analysis in Mosteller and Wallace (1963)](http://ptrckprry.com/course/ssd/lecture/federalist.html)
  
## Network Analysis

  * [Introduction to Network Analysis with R](https://www.jessesadler.com/post/network-analysis-with-r/)
  
## Geospatial Analysis

  * [Geocomputation with R](https://geocompr.robinlovelace.net/)
  

# Resources by Discipline {-}

## Biology & Biostatistics {-}
 - [Handbook of Biological Statistics](http://www.biostathandbook.com/)
 - [An R Companion for the Handbook of Biological Statistics](https://rcompanion.org/rcompanion/index.html)
 
## Economics & Econometrics {-}
 - [Introduction to Econometrics with R](https://www.econometrics-with-r.org)
 - [Principles of Econometrics with R](https://bookdown.org/ccolonescu/RPoE4/)
 - [Introduction to Data Science](https://bookdown.org/ronsarafian/IntrotoDS/)
 - [Using R for Introductory Econometrics](http://www.urfie.net/read.html)
 
 * Examples:
    
    - [Annotated Sample Econometrics Paper](https://minerva.union.edu/dvorakt/43/sample_paper.htm)
 
    - [Microeconomic example of utility maximization constrained by budget lines](https://www.andrewheiss.com/blog/2019/02/16/algebra-calculus-r-yacas/)
 
## Psychology {-}

 - [Psychology Research Methods](https://www.simplypsychology.org/qualitative-quantitative.html)
 
## Public Health & Epidemiology {-}

  * Examples:
  
    - [SIR Model Using R](https://rpubs.com/choisy/sir)

 
## Social Sciences {-}

 - [Social Science Methods Modules](https://modu.ssri.duke.edu/)
 - [Applied Causal Analysis](https://bookdown.org/paulcbauer/causal_analysis/)

Here are some more tips for getting started with Academic:

## Tip 3

### Tip 3A
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

Nullam vel molestie justo. Curabitur vitae efficitur leo. In hac habitasse platea dictumst. Sed pulvinar mauris dui, eget varius purus congue ac. Nulla euismod, lorem vel elementum dapibus, nunc justo porta mi, sed tempus est est vel tellus. Nam et enim eleifend, laoreet sem sit amet, elementum sem. Morbi ut leo congue, maximus velit ut, finibus arcu. In et libero cursus, rutrum risus non, molestie leo. Nullam congue quam et volutpat malesuada. Sed risus tortor, pulvinar et dictum nec, sodales non mi. Phasellus lacinia commodo laoreet. Nam mollis, erat in feugiat consectetur, purus eros egestas tellus, in auctor urna odio at nibh. Mauris imperdiet nisi ac magna convallis, at rhoncus ligula cursus.

Cras aliquam rhoncus ipsum, in hendrerit nunc mattis vitae. Duis vitae efficitur metus, ac tempus leo. Cras nec fringilla lacus. Quisque sit amet risus at ipsum pharetra commodo. Sed aliquam mauris at consequat eleifend. Praesent porta, augue sed viverra bibendum, neque ante euismod ante, in vehicula justo lorem ac eros. Suspendisse augue libero, venenatis eget tincidunt ut, malesuada at lorem. Donec vitae bibendum arcu. Aenean maximus nulla non pretium iaculis. Quisque imperdiet, nulla in pulvinar aliquet, velit quam ultrices quam, sit amet fringilla leo sem vel nunc. Mauris in lacinia lacus.

Suspendisse a tincidunt lacus. Curabitur at urna sagittis, dictum ante sit amet, euismod magna. Sed rutrum massa id tortor commodo, vitae elementum turpis tempus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean purus turpis, venenatis a ullamcorper nec, tincidunt et massa. Integer posuere quam rutrum arcu vehicula imperdiet. Mauris ullamcorper quam vitae purus congue, quis euismod magna eleifend. Vestibulum semper vel augue eget tincidunt. Fusce eget justo sodales, dapibus odio eu, ultrices lorem. Duis condimentum lorem id eros commodo, in facilisis mauris scelerisque. Morbi sed auctor leo. Nullam volutpat a lacus quis pharetra. Nulla congue rutrum magna a ornare.

Aliquam in turpis accumsan, malesuada nibh ut, hendrerit justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque sed erat nec justo posuere suscipit. Donec ut efficitur arcu, in malesuada neque. Nunc dignissim nisl massa, id vulputate nunc pretium nec. Quisque eget urna in risus suscipit ultricies. Pellentesque odio odio, tincidunt in eleifend sed, posuere a diam. Nam gravida nisl convallis semper elementum. Morbi vitae felis faucibus, vulputate orci placerat, aliquet nisi. Aliquam erat volutpat. Maecenas sagittis pulvinar purus, sed porta quam laoreet at.


## Tip 4

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

Nullam vel molestie justo. Curabitur vitae efficitur leo. In hac habitasse platea dictumst. Sed pulvinar mauris dui, eget varius purus congue ac. Nulla euismod, lorem vel elementum dapibus, nunc justo porta mi, sed tempus est est vel tellus. Nam et enim eleifend, laoreet sem sit amet, elementum sem. Morbi ut leo congue, maximus velit ut, finibus arcu. In et libero cursus, rutrum risus non, molestie leo. Nullam congue quam et volutpat malesuada. Sed risus tortor, pulvinar et dictum nec, sodales non mi. Phasellus lacinia commodo laoreet. Nam mollis, erat in feugiat consectetur, purus eros egestas tellus, in auctor urna odio at nibh. Mauris imperdiet nisi ac magna convallis, at rhoncus ligula cursus.

Cras aliquam rhoncus ipsum, in hendrerit nunc mattis vitae. Duis vitae efficitur metus, ac tempus leo. Cras nec fringilla lacus. Quisque sit amet risus at ipsum pharetra commodo. Sed aliquam mauris at consequat eleifend. Praesent porta, augue sed viverra bibendum, neque ante euismod ante, in vehicula justo lorem ac eros. Suspendisse augue libero, venenatis eget tincidunt ut, malesuada at lorem. Donec vitae bibendum arcu. Aenean maximus nulla non pretium iaculis. Quisque imperdiet, nulla in pulvinar aliquet, velit quam ultrices quam, sit amet fringilla leo sem vel nunc. Mauris in lacinia lacus.

Suspendisse a tincidunt lacus. Curabitur at urna sagittis, dictum ante sit amet, euismod magna. Sed rutrum massa id tortor commodo, vitae elementum turpis tempus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean purus turpis, venenatis a ullamcorper nec, tincidunt et massa. Integer posuere quam rutrum arcu vehicula imperdiet. Mauris ullamcorper quam vitae purus congue, quis euismod magna eleifend. Vestibulum semper vel augue eget tincidunt. Fusce eget justo sodales, dapibus odio eu, ultrices lorem. Duis condimentum lorem id eros commodo, in facilisis mauris scelerisque. Morbi sed auctor leo. Nullam volutpat a lacus quis pharetra. Nulla congue rutrum magna a ornare.

Aliquam in turpis accumsan, malesuada nibh ut, hendrerit justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque sed erat nec justo posuere suscipit. Donec ut efficitur arcu, in malesuada neque. Nunc dignissim nisl massa, id vulputate nunc pretium nec. Quisque eget urna in risus suscipit ultricies. Pellentesque odio odio, tincidunt in eleifend sed, posuere a diam. Nam gravida nisl convallis semper elementum. Morbi vitae felis faucibus, vulputate orci placerat, aliquet nisi. Aliquam erat volutpat. Maecenas sagittis pulvinar purus, sed porta quam laoreet at.
