---
toc: true
toc_label: "Table of Contents"
layout: single
classes: wide
title: "Undergraduate Honors Reseach"
excerpt: "A summary of my undergraduate research paper, "Examining the Effects of Faculty Salary and Work Experience on Student Outcomes at Southern 4-Year Colleges and Universities," along with a download link for the full paper."
author_profile: true
---

## ABSTRACT

Literature has shown that compensation and work experience are linked to improved employee performance [18] [23]. Four-year institution faculty are essential determinants of student outcomes; thus, their performance is essential to the institution’s success. Retention, graduation rates, and graduate earnings are outcome metrics used by institutions to benchmark effectiveness. Due to the COVID-19 pandemic, institutions are falling short in these areas [22]. Through regression techniques, this research determines that instructional staff experience and compensation significantly impacts each of these metrics. Therefore, through optimized human resources policies, institutions could indirectly influence student outcomes thus improving their ability to meet desired benchmark figures.

## INTRODUCTION

### Introduction

Proactive colleges and universities in the United States are continuously looking for ways to improve and innovate their practices to meet benchmark figures. Due to the COVID-19 pandemic, which has negatively impacted students and their willingness to stay enrolled in these institutions, many institutions are beginning to fall short in some of these areas [22]. The fundamental purpose of higher education institutions is to maximize positive outcomes for students. Previous research has examined how institutional characteristics, which often also include instructional staff variables, affect student retention [1] [6] [26], graduation [7] [8] [16], and labor market success [4]. It was hypothesized that since instructional staff directly interact with students, they are perhaps the most influential part of a student’s undergraduate experience. While some research does look more closely at instructional staff’s effect on these, no research could be found that combines these staff characteristics to examine the three aforementioned outcome metrics. 

It is imperative that institutions allocate their resources appropriately so that they are positioned to promote student success. Financially, staff expenses, especially salaries, are the largest, regular, component of instructional expenditures at four-year schools. Thus, by knowing what instructional staff characteristics are most influential in promoting a positive outcome, schools can better distribute their resources to help promote a more efficient staff which is an essential strategic commitment if they wish to provide the best outcome for students. Furthermore, with staff expenses being so significant, these freed resources could be utilized in other areas to promote strategies that would further improve the student experience such as improved facilities or providing more financial support. 

It was determined that the instructional staff experience and compensation should be examined as these are metrics that can be influenced through appropriate human resource policies and procedures are four-year institutions. Within these two categories were multiple independent variables that were available for nearly all the institutions represented in the data set, thus providing fair metrics for comparison between the institutions. These two categories of variables will be subjected to both univariate and multivariate regressions, the results of which will be extensively analyzed, to determine their relationship with one another and their impact on student retention, six-year graduation rate, and earnings after college.

Starting with univariate linear regression models, each of the 14 variables of interest were explored individually to examine the relationships that existed between student outcomes and instructional staff characteristics. This was important to the study as it provided justification to create larger models to explore which variables created the “best” environment for student success. Ultimately, there were multiple independent variables that seemed to exhibit a significant relationship with student retention, graduation, and earnings after graduation. This information was then used to perform a backward stepwise regression analysis which provided the final model which could be used to provide prescriptive recommendations to four-year institutions on how they could potentially improve the student outcome metrics examined by making strategic changes to their current and future staff through human resource policies and hiring criteria. This model, after some manually removals were made due to variable insignificance and multicollinearity, showed that institutional expenditure on instructional wages and the level of experience among full-time faculty members make a significant, positive, contribution towards student outcomes and are thus areas that institutions may consider allocating more time to improve upon should they wish to meet desired benchmarks.

### Literature Review

The theory that student outcomes, specifically graduation rates, are influenced by characteristics of the institution’s faculty was not simply developed based on presumptions. One study, conducted by Mehta et. al. (2021), examined the use of genetic algorithm assisted regression techniques to predict graduation rate and included independent variables that were tied to the institution’s faculty [16]. Genetic algorithms are used to optimize the performance of a model and do so by following a process like that of humans: selection, crossover, and mutation [16]. Genetic algorithms were not used in this study, however the structure of their model and which variables they found to be the most significant were used during the formation of the hypothesis of what would impact graduation rates the most.  They found that the two most significant classes of variables were institute characteristics, which accounted for 80% of their final model, and human resource characteristics, which accounted for 12% of their final model [16, p. 2275]. While they do not provide details on the 142 independent variables within these categories, they gathered their data from IPEDS [16, p. 2271]. The variables that describe the faculty characteristics of interest to this study (compensation and experience indicators) are all included in the human resources section of IPEDS. Since Mehta et. al. used the human resource variables from IPEDS, it can safely be assumed that 12% of an effective model predicting graduation would use variables from that same category. This indicates that faculty characteristics do have a significant impact on graduation rate, and therefore it is possible that they may also affect other student outcomes such as retention and earnings after college.  

When evaluating the overall performance of a higher-ed institution it is essential to look at more than one metric. In the literature examined, the primary indicators of institutional success have been graduation rates, retention rates, and success in the labor market [11] [15] [16] [27] [29]. However, many studies tend to focus on retention or graduation. It was hypothesized that the most successful institutions would have faculty that encouraged and indirectly contributed towards not only above-average graduation and retention rates, but also higher median earnings after graduation. In this study all three of these factors and the chosen faculty characteristics, the independent variables, will be examined in an attempt to determine how they affect one another. While it has been shown that student characteristics, such as GPA and standardized test scores, certainly influences all these factors, especially retention rates, existing literature also expresses that institution-level variables, including faculty characteristics, have a large impact as well [3] [16]. Graduation rates have also been found to be positively correlated with faculty characteristics such as number full-time faculty members, faculty-to-student ratios, and others that will be examined further in this study [8]. 

This study will use regression techniques to evaluate the effect of different categories of faculty characteristics. While there is little literature that discusses the application of regression techniques on the College Scorecard Dataset, there are numerous studies that have been conducted using the National Center for Education Statistics’ (NCES) Integrated Postsecondary Education Data System (IPEDS). To justify the use of this technique, the study done by Horn and Lee (2015) was examined in which they determined whether regression residuals are a legitimate way to measure student outcome, specifically they sought to assign an effectiveness score that reflected how effectively institutions were promoting degree completion [12, p. 491]. In their discussion, they concluded that their regression results could be reproduced and were therefore consistent, furthermore they state that the results seemed to be consistent over consecutive years [12, p. 491]. Their work implies that regression is a reliable method of examining institutional effectiveness at influencing student outcomes. 

Aside from determining the reliability and validity of regression, there are studies that employ this method to determine the effectiveness of specific variables in promoting a positive student outcome [6] [11] [15] [21]. These studies tend to use hierarchical regression which creates multiple regression models using different variables of interest to improve the overall performance of the model. This is a helpful technique when evaluating variables that can fit into different categories which was how Marsh (2014) implemented this. As more levels are added to the regression, more variance is typically explained and thus it is possible to infer the total impact of each variable in the overall model.  Hobson et. al. (2022) utilized regression to examine the differences between white and Hispanic college student six-year graduation rates that they retrieved from IPEDS. This shows that regression not only is a viable method, but also that IPEDS data is compatible with the technique as are a variety of the variables that it contains. 

The work of Dahlvig et. al. (2020) helps readers understand the relationship between different types of institutional expenditure and how they impact student retention and graduation. They found that institutional expenditure on instruction per full-time equivalent (FTE) student was positively correlated with graduation [6, p. 361]. It is well known that the largest part of instructional expenditures is faculty salary, so knowing that instructional spending is positively correlated with student graduation could imply that faculty salary would reflect these results. However, this goes against the findings of Aaron (2013) who found that there was no correlation, negative or positive, between instructional spending or faculty salaries and student retention [1, p. 73]. They did, however, state that as the regional normalized wages increased student retention increased slightly [1, p. 73]. 

To determine if faculty salary really would have an impact on student outcomes, one would need to examine whether student success and teaching are incentivized monetarily in high education institutions. Some research has been done in this area [17]. Melguizo and Strober (2007) found in their study that most faculty were compensated more because of their contribution to the institution’s overall prestige as it was perceived by those outside of the college [17]. Additionally, they concluded that there was a negative, though very small, correlation between time spent instructing students and salaries [17, p. 662]. This would imply that there are no significant financial incentives for instructors who choose to focus on instruction alone. This is an important conclusion as it could provide an explanation for the low impact salaries had on student outcomes described by Aaron (2014). In this study, the relationship between faculty compensation and student outcomes will be reexamined to determine if a correlation exists between them. Unlike previous studies, however, outcomes other than graduation will be examined such as retention and graduate earnings after graduation. 

Zong and Davis (2022) conducted a similar study to this one where they examined the retention and graduation rates of 706 public institutions in the United States. Their focus was on testing and potentially improving upon an existing theoretical model developed by Fung (2010) [7] [29]. One of the key takeaways from this model is its use of categories of variables to further break down the different factors affecting retention and graduation. In the study, they ultimately developed a model that included variables that could be categorized within institutional performance, student commitments, student background, student finance, academic environment, and social environment [29, p. 6-7]. Contained within their academic environment variables was student-to-faculty ratio, which was examined in other literature examined [15]. This is a common theme in previous research, faculty characteristics are typically either combined with institutional influences or it is summarized by using student-to-faculty ratios. However, there are many other characteristics of faculty that could influence student outcomes when they are examined individually before being placed in a model. 

Studies such as Marsh (2014), include faculty qualities as a part of the overall characteristics of the institution and attempt to determine a relationship between these measures and student retention. Marsh emphasizes the importance of retention especially in the growing age of data transparency [15]. Using hierarchical regression techniques, they found that the faculty characteristics included in the model, percentage of full-time faculty and student-to-faculty ratio, had a relatively low impact on the overall R¬¬¬2 of their model [15, p. 139]. They go on, however, to say that these lower figures may be due to previous stages of the model accounting for variance that could also be explained by faculty characteristics [15, p. 144]. Furthermore, they reference previous studies such as Tinto (2006) that argued many larger institutions use part-time or less experienced faculty in their first-year courses which could lead to students not getting the same quality of instruction as upper-level students [15, p. 144] [26]. 

The theory that part-time faculty may have an impact on student outcomes is not a new one and has been examined by Thirolf and Woods (2018) who explored the role of contingent faculty at community colleges and the importance of providing them adequate support. Adequate support for part-time faculty, in this instance, means better compensation and access to groups and training workshops on campus. Compensation for contingent faculty in four-year schools has historically been a concern as full-time faculty salaries decrease which has also led to a decrease in the already low salary of adjuncts and lectures [13]. While this study aims to examine faculty’s impact at four-year institutions, one could argue that community and technical schools are a good source of information when examining the effects of part-time faculty members on students since historically contingent faculty have been a majority at these types of schools [25]. They concluded that part-time faculty ultimately are a valuable resource to students and should be provided resources such as professional development and opportunities to engage with other faculty members [25]. They also briefly discuss the findings of Yu, Campell, and Mendoza (2015) who found that there was not a negative correlation between the percentage of part-time faculty and student’s ability to graduate [28]. 

A study by Xu and Ran (2020), sought to find the relationship between the type of faculty members a student interacted with and their outcomes in the labor market [27]. Their analysis was based on the idea that in recent years, higher education institutions have become increasingly reliant on adjunct and non-tenured track faculty members due to the higher cost of full-time instructors. They found that while at two-year colleges there was a negative impact on student performance when exposed to more part-time instructors, there was no such effect on students at four-year institutions [27, p. 252]. However, it could be possible that this lack of an effect at four-year institutions is a result of the disproportionate number of adjuncts and faculty present at two-year institutions. If this is the case, the argument could be made that the percentage of instructors that are adjuncts or temporary lecturers is still an important metric to examine in a study relating faculty characteristics to student outcome for if an institution is more reliant on part-time instructors, for their first-year students especially, there could be a negative impact on outcome. In addition to adjunct faculty lacking motivation due to their lower compensation and lack of available resources [13] [25], there are concerns surrounding their level of interaction with students outside of the classroom which has recently been a focus among higher education institutions as it has been tied to higher retention and graduation rates [19]. 

While there certainly appears to be validity to the claim that student exposure to different types of faculty members can influence their outcome, it appears as though the primary dependent variable affected by part-time faculty ratios is student retention [25] [27]. In fact, according to existing literature, the level of exposure a student has to adjuncts has no effect on labor market outcomes [27]. This is supported by other literature that suggests that there is a minimal effect on labor market effectiveness influenced by instructor characteristics and that even instructors that are effective in the classroom may not lead to increased success in the job market [4]. In this study instructional staff characteristics will be broken down further and the effectiveness of not just part-time staff, but also the ranks of those staff members such as lecturers and adjuncts as well as the different ranks of full-time faculty members including professors, assistant professors, and associate professors will be examined. While there may not have been an impact on earnings when looking at just part-time instructors, it is possible that more experienced faculty could lead to increased earnings. Additionally, based on the findings of Xu and Ran (2020), it was hypothesized that when retention and graduation rates are examined, the institutions with the highest proportion of senior faculty members will show higher levels of successful student outcomes than those with more junior or part-time instructors. 

## METHODOLOGY 

### The Data

In this study, data was gathered from two locations, the College Scorecard Dataset, which is provided by the U.S. Department of Education, and the Integrated Post-Secondary Education Data System (IPEDS), maintained by the National Center for Education Statistics’ (NCES). The IPEDS data was the primary source for all independent variables examined (faculty characteristics) while the College Scorecard was the source of the dependent variables (student outcome). 

Both data sets are updated annually, typically a few months apart from one another, and include information on all institutions in the United States that are eligible for Title IV funding. All data collected was from the 2020-2021 academic year which is the most recent year for which data was available for download. Any variable that examined faculty characteristics that are subject to change (academic rank, salary, etc.) are from the start of the fall semester at each institution. This means that if an instructional staff member were to receive an increase in compensation or a new title during the academic year examined it would not be reflected in the data. 

All variables extracted from the IPEDS data came from the Human Resources category which includes salary outlays, tenure status, academic rank, and other characteristics for all full and part-time staff at an institution. Independent variables were selected from the dataset based on the belief that they may impact student outcomes. The independent variables selected fit into two categories: (1) instructional staff compensation and (2) instructional staff rank, experience, and status. Once the data had been extracted, numerous aggregations, summarized in Appendix I, were completed to provide more normalized values which allows for a more accurate and fair comparison between institutions.

College Scorecard was used as the source for student outcome variables. Both retention and graduation rates are available through the IPEDS website, however College Scorecard includes graduate earnings after college, gathered from documents filed by alumni to the Internal Revenue Service, which was an outcome of interest in this study. 

The final data set contained 401 institutions in the United States. They were all 4-year colleges and universities according to their Carnegie Classification that predominantly grant bachelor’s degrees. Additionally, they were all accredited by the Southern Association of Colleges and Schools Commission on Colleges (SACSCOC). Once the sample had been reduced to this smaller subset, any columns that were suppressed for privacy reasons or any columns that were missing data for 15% or more of the institutions included were removed.  

During the early stages of this preliminary analysis, it was acknowledged that faculty salaries may be skewed due to graduate instructors at some institutions. A potential limitation with this data is that the IPEDS data does not differentiate between graduate and undergraduate instructor salaries; This could cause issues when examining undergraduate outcomes as graduate instructors tend to receive higher compensation. To alleviate this issue, total spending variables were used rather than the average salary outlays for instructional staff. The three spending variables examined were: 1) total spending on instructional wages, 2) total spending on academic support wages, and 3) total spending on auxiliary service wages. All these variables were then divided by the entire student population, not just undergraduates, to provide a better figure for comparison between institutions. Support and auxiliary wages were included to ensure that tutors, athletic academic staff, and other instructional staff were included that may not be represented in instructional staff wages. Using spending on instructional wages also ensures that part-time salaries are included in the model, which would not be a guarantee if average faculty salary had been examined.

### Preliminary Analysis

Prior to building the final model, the relationship between each independent variable and the three dependent variables was examined. During the exploratory phase, the relationship between each predictor variable and the three dependent variables of interest were examined, starting with retention. This relationship was examined by conducting 13 univariate regression models for each of the dependent variables where the dependent variable remained the same and each independent variable was used as the sole predictor. Univariate regression would not be sufficient when trying to explain the primary driver for any single student outcome in this case as there is a great deal of variance to be explained and no single faculty characteristic can account of all of it. However, these simple regression models helped to determine which predictors were the most statistically significant and find their correlations to the dependent variables. This would help form hypotheses around which variables would most likely be used in the final model. Additionally, it led to conclusions regarding the validity of the research question, as if there were no significant predictors, then there would be little evidence to support further examination of faculty characteristics and their impact on student outcomes.

For each univariate regression, a confidence interval of 95% was specified. Meaning a p-value below 0.05 would indicate a statistically significant relationship in the model - that is to say, the null hypothesis can be rejected due to the relationship between the independent and dependent variables. Furthermore, the f-statistic was included in the model results to further support the significance of the independent variables. All the models had a single degree of freedom due to them having only a single predictor, however each model had at least 380 residual degrees of freedom. Using f-tables, the critical f-value necessary to reject the null hypothesis was found to be 3.8415 meaning that any model with an f-statistic exceeding this critical value is statistically significant and the null hypothesis can be rejected.

### Constructing the Final Models

After conducting the preliminary analysis, the final models were constructed. The best possible subset of variables that influenced the outcome measure of each model was desired, so various subset selection techniques were evaluated. Ultimately, stepwise regression was selected as the best method for this study. Stepwise regression allows the researcher to evaluate different model combinations without having to manually compute each one and produces a set of independent variables that have the highest degree of influence on the dependent variable. Traditionally, stepwise regression utilized the f-statistic as the selection criteria for the model where a critical value was used and any independent variable that failed to be greater than the critical value would not be included in the model. However, as Hastie et al point out, this method is dated and fails to take into account the problem of multiple testing [10]. Instead, the Akaike information criterion (AIC) was utilized which uses the log-likelihood to determine the fit of the model and penalizes the model for being overly complex. Equation 1 shows the equation used for calculating AIC. 

(1) $AIC = -2ln(\hat{\Beta})+2k$ 

When applied to regression, the procedure is to search for the set of independent variables that will minimize the AIC value of the overall model while also trying to simplify the model as much as possible. In this instance, this is helpful because it will, in theory, find the most significant subset of independent variables that are associated with student outcomes thus creating a smaller model as opposed to having a larger model with many variables that may have a miniscule contribution to the explanation of the variance in the dependent variable. 

There are two separate ways to approach a stepwise model. Forward stepwise models start with the most significant independent variable and then sequentially attempts to add one variable at each step. If the added variable hurts overall performance, it is not included. Once the variable is added, the model is reevaluated to ensure all variables are still significant and any that are deemed insignificant are dropped. Backward stepwise regression starts with a single, large, model that contains all independent variables. It then goes through and removes the least significant variable, based on the z-score of the variable, at each step. This is helpful because the “kitchen sink” model can be examined which is simply a model that contains all independent variables as predictors, something that is very unlikely to happen in a forward selection process. This allows the researcher to see how all their variables interact together and how effectively the predictors explain the variance of the dependent variable. It should be noted that these so called “kitchen sink” models are often never used as they contain numerous insignificant variables and typically fall victim to high levels of multicollinearity.

Once the models were constructed, a variety of tests were selected to examine their goodness of fit and attempt to detect any multicollinearity which may negatively affect their performance. Using variance inflation factors, the effect collinearity had on variance in the model could be examined. It was deemed that any VIF coefficient between four and nine was worthy of investigation and any variable with a coefficient greater than nine was removed from the model immediately. If a variable had a VIF coefficient below four, it was concluded that collinearity had little impact on that variable’s effectiveness in the model. Equation 2 shows the equation that can be used to calculate the variance inflation factor of a variable. In addition to the VIF coefficients, the condition indices for each model were examined and if any independent variable had a condition index value over 30 it was removed from the model as it was likely highly collinear with another variable. 

(2) $VIF = \frac{1}{1-R^2}$

Coefficient sign flips are also an indicator of collinearity. In instances where a sign flipped, the variable was removed from the model and it was reexamined.

Goodness of fit was tested by examining the models’ residual plots and R2 values. Adjusted R2 was the preferred measure as it considers the number of independent variables that are entered into the model and only increases as more variance is explained.

## RESULTS

### Preliminary Analysis Results

Table 1 shows the results of the first set of regressions that were conducted on retention. Using the R package purrr, the 13 univariate regressions could be run rather quickly, and the results could be mapped into a table for analysis. When paired with the dplyr and broom packages, purrr makes running multiple regression models with the same dependent variable quick and provides an easy to interpret output that allows summary statistics of interest to be specified, thus simplifying outputs for reporting. Furthermore, by utilizing R and other computer software, replication is more feasible in the future as there will be fewer hand calculations necessary to reach similar findings. 

#### Table 1: Retention Univariate Regression Results
|     Predictor    |     Coefficient    |     R^2    |     P-Value    |     F-Statistic    |
|---|---|---|---|---|
|     Total Spent on Instructional Wages per   Student    |     1.40E-05    |     0.2085    |     6.82E-22    |     104.3096    |
|     Total   Spent on Academic Support Wages per Student    |     8.67E-06    |     0.0521    |     4.23E-06    |     21.7616    |
|     Total Spent on Student Services and Aux.   Services per Student    |     2.27E-05    |     0.0744    |     3.19E-08    |     31.8447    |
|     % Full-Time Instructional Staff    |     0.26013    |     1.71E-01    |     7.88E-18    |     81.4570    |
|     % Full-Time Tenured Faculty    |     0.31784    |     0.17581    |     2.23E-18    |     84.4745    |
|     % Full-Time Tenure Tracked   Faculty    |     0.00311    |     7.60E-06    |     9.56E-01    |     0.0030    |
|     % Full-Time Non-Tenured Faculty    |     0.01775    |     0.00064    |     0.61616    |     0.2517    |
|     % Faculty - Professor    |     0.41089    |     0.10832    |     1.65E-11    |     48.1066    |
|     % Faculty - Associate Professor    |     0.19025    |     0.01702    |     0.00917    |     6.8561    |
|     % Faculty - Assistant Professor    |     -0.16448    |     0.02094    |     3.82E-03    |     8.4690    |
|     % Faculty - Instructor    |     -0.19012    |     0.01237    |     0.02647    |     4.9619    |
|     % Faculty - Lecturer    |     0.36968    |     0.05069    |     5.73E-06    |     21.1462    |
|     % Faculty - No Academic Rank    |     -0.08903    |     0.00152    |     0.43821    |     0.6022    |

These models show there are numerous predictor variables with p-values less than 0.05 meaning that they are statistically significant and could be used to disprove the null hypothesis. Furthermore, expenditure on instructional salary per student, the percentage of instructional staff holding professor ranks, the percentage of full-time staff, and the percentage of full-time instructional staff that holds tenure each had R2 values of 0.10 or greater indicating that they may explain more than 10% of the variance in student retention. This indicates that experienced faculty likely have a positive impact on student retention. There was concern regarding collinearity between salaries and instructional staff experience, however by using the slightly broader variable of instructional salary expenditure per student, part-time staff salaries are included. Additionally, the wage spending variables were normalized based on class size which further helps eliminate some of this error. 

After examining retention, six-year graduation rate was examined using the same methodology. Six-year graduation rate was chosen over four-year due to the greater number of students that would be captured by this variable. Should a student require additional semesters of coursework due to factors such as inability to meet major requirements or athletics, they would not be included in the four-year graduation rate of an institution. By using the six-year rate, which is often not caused by institutional factors, this issue is mostly eliminated, and thus the variable is more likely to showcase institutional effectiveness in helping students reach their desired outcomes. Table 2 shows the output from the regression models built for six-year graduation.

#### Table 2: Six-Year Graduation Rate Univariate Regressions
|     Predictor    |     Coefficient    |     R^2    |     P-Value    |     F-Statistic    |
|---|---|---|---|---|
|     Total Spent on Instructional Wages per   Student    |     2.59E-05    |     0.3362    |     6.11E-37    |     199.5089    |
|     Total   Spent on Academic Support Wages per Student    |     0.000015    |     0.0702    |     8.72E-08    |     29.7455    |
|     Total Spent on Student Services and Aux.   Services per Student    |     0.000053    |     0.1927    |     4.44E-20    |     94.0229    |
|     % Full-Time Instructional Staff    |     0.3177    |     1.17E-01    |     2.57E-12    |     52.2367    |
|     % Full-Time Tenured Faculty    |     0.4538    |     0.1675    |     2.01E-17    |     79.2627    |
|     % Full-Time Tenure Tracked   Faculty    |     -0.0441    |     7.15E-04    |     5.96E-01    |     0.2817    |
|     % Full-Time Non-Tenured Faculty    |     -0.0229    |     0.0005    |     0.6584    |     0.1958    |
|     % Faculty - Professor    |     0.6864    |     0.1407    |     1.13E-14    |     64.5016    |
|     % Faculty - Associate Professor    |     0.3592    |     0.0284    |     0.0008    |     11.5180    |
|     % Faculty - Assistant Professor    |     -0.2334    |     0.0195    |     5.42E-03    |     7.8189    |
|     % Faculty - Instructor    |     -0.4032    |     0.0259    |     0.0013    |     10.4796    |
|     % Faculty - Lecturer    |     0.3118    |     0.0165    |     1.06E-02    |     6.5940    |
|     % Faculty - No Academic Rank    |     -0.1309    |     0.0015    |     0.4357    |     0.6088    |

Again, the model showed that instructional salary expenditure was significant and had the highest R2 value, but in addition it appears as though auxiliary support and student services salary expenditure was significant. Additionally, professor ranked instructional staff and full-time staff with tenure were again found to be significant and had R2 values over 0.10.

These results show that there are faculty characteristics that play a significant role in determining student outcome in four-year institutions. Furthermore, the claim that, depending on the outcome being measured, a different combination of faculty characteristics may be more significant than others can be justified, which in turn also justifies the creation of multiple models to examine different student outcomes to provide more specific areas for improvement to institutions. While prior research discussed in the literature review tends to examine only one outcome measure, such as retention, these results show that there are differences in how the outcomes are influenced, and thus multiple dependent variables should be considered when determining the most effective instructional staff make up at four-year institutions.

Finally, univariate regressions were conducted on independent graduate earnings eight years after entering the institution. College Scorecard includes earnings data for students six, eight, and ten years after entering their undergraduate program. It was determined that eight years would be the most useful for this study because 1) it would include the students that did not graduate within four years and 2) it was soon enough after most students graduate that their experience in an undergraduate program would likely still influence their earnings. This second point would not be true ten years after program entry as this could be as many as six years after graduation, at which point employees are likely compensated more based on experience than education. Table 3 shows the results of the univariate regressions conducted on graduate earnings. 

#### Table 3: Earnings Eight Years After Program Entry Univariate Regressions
|     Predictor    |     Coefficient    |     R^2    |     P-Value    |     F-Statistic    |
|---|---|---|---|---|
|     Total Spent on Instructional Wages per   Student    |     1.46E+00    |     0.2979    |     1.67E-32    |     169.2638    |
|     Total   Spent on Academic Support Wages per Student    |     7.62E-01    |     0.0528    |     3.34E-06    |     22.2322    |
|     Total Spent on Student Services and Aux.   Services per Student    |     2.54E+00    |     0.1235    |     4.27E-13    |     56.2027    |
|     % Full-Time Instructional Staff    |     15454.1599    |     7.95E-02    |     9.18E-09    |     34.4554    |
|     % Full-Time Tenured Faculty    |     22994.2281    |     0.1218    |     6.31E-13    |     55.3257    |
|     % Full-Time Tenure Tracked   Faculty    |     -4673.8427    |     2.27E-03    |     3.42E-01    |     0.9060    |
|     % Full-Time Non-Tenured Faculty    |     -2104.5762    |     0.0012    |     0.4928    |     0.4713    |
|     % Faculty - Professor    |     33775.4510    |     0.0970    |     1.79E-10    |     42.8819    |
|     % Faculty - Associate Professor    |     16052.0723    |     0.0160    |     0.0112    |     6.4955    |
|     % Faculty - Assistant Professor    |     -11244.7455    |     0.0130    |     2.25E-02    |     5.2464    |
|     % Faculty - Instructor    |     -29764.2327    |     0.0400    |     5.48E-05    |     16.6318    |
|     % Faculty - Lecturer    |     14581.7784    |     0.0104    |     4.15E-02    |     4.1828    |
|     % Faculty - No Academic Rank    |     -4083.8758    |     0.0004    |     0.6825    |     0.1676    |

Fascinatingly, there again was a positive correlation between the salary expenditure variables and the dependent variable. This would indicate that as institutions spend more on the salaries of individuals that directly contribute to student’s academic success, there is an increase in the student’s earnings after college. This could be due to several factors, but it was hypothesized the most reasonable explanation for this relationship is that students experience better academic performance which in turn would increase their likelihood and ability to negotiate higher entry level salaries. Another potential explanation could be that institutions that pay their instructional staff and student services employees better likely compensate their career and professional development staff equally as well leading students to have more resources on campus that would improve their likelihood of a more lucrative job or internship placement. 

Another relationship to make note of in these results is tenured faculty. While in the previous models created professor status and the percentage of full-time instructional staff were found to be significant predictors, in this case only tenure status was found to add significant value to the model. The other independent variables had low R2 values but appeared to have significant F-statistic and p-values leading to the conclusion that they may account for more overall variance in the final model when examined alongside other variables. 

### Retention Model Results

The retention model consisted of 398 institutions rather than 401 due to three being removed from the data prior to analysis due to them missing the dependent variable. Table 4 shows the shows the variables removed from the model during the stepwise process. Table 4.2 shows any additional variables removed as well as the reason for their removal. The percentage of staff that held the instructor rank being dropped from the model was not entirely surprising since this is a relatively uncommon rank, however associate professor is much more common and was also deemed insignificant. This is likely due to other experience variables such as the percentage of staff holding the professor rank accounted for variance that was partially explained by these less significant predictors. Auxiliary service wages per student also dropped during the backward steps. This variable includes the wages of academic support staff that work with student athletes as well as other academic support staff not directly connected to either a specific degree program or the academic support program of the institution. Some may assume that these programs are instrumental to the success of student athletes, but the initial results from this model indicate that perhaps the wages of their instructors and regular academic support staff may be more influential.

#### Table 4.1 Variables Removed from the Retention Model During Stepwise Process 
|     VARIABLE REMOVED    |     aic   (Variable)    |     AIC   (Model)    |
|---|---|---|
|     Auxiliary wage spending per   student    |     -724.264    |     -722.544    |
|     % FACULTY – INSTRUCTORS    |     -725.862    |     -724.264    |
|     % FACULTY – ASSOCIATE PROFESSORS    |     -727.375    |     -725.862    |
|     % FACULTY – TENURED    |     -728.251    |     -727.375    |

#### Table 4.2 Additional Variables Removed from the Retention Model
|     VARIABLE REMOVED    |     aic   (Variable)    |     AIC   (Model)    |
|---|---|---|
|     Auxiliary wage spending per   student    |     -724.264    |     -722.544    |
|     % FACULTY – INSTRUCTORS    |     -725.862    |     -724.264    |
|     % FACULTY – ASSOCIATE PROFESSORS    |     -727.375    |     -725.862    |
|     % FACULTY – TENURED    |     -728.251    |     -727.375    |

Once variables had been removed for collinearity, the model was reconstructed, and variables were dropped due to insignificance. Table 5 contains the independent variables that made up the final model.

#### Table 5: Retention Model Independent Variables
|  |     estimate    |     std.error    |     p.value    |
|---|---|---|---|
|     (Intercept)    |     0.591    |     0.018    |     8.27E-114    |
|     Instructional   Wage spending Per Student    |     9.42E-06    |     1.37E-06    |     2.31E-11    |
|     %   faculty – full-time    |     0.174    |     0.032    |     6.37E-08    |
|     %   faculty - professor    |     0.193    |     0.056    |     < 0.001    |
|     %   faculty – Assistant Professor    |     -0.260    |     0.050    |     2.75E-07    |
|     %   faculty – lecturers    |     0.180    |     0.070    |     0.011    |
|     %   faculty – no academic rank    |     -0.223    |     0.094    |     0.018    |

The p-value of the independent variables all indicate a high level of significance and the preliminary analysis seemed to indicate that these variables were also correlated with retention, leading to the conclusion that this model is valid and its performance can be examined before proceeding on to making assumptions with these findings. 

The statistical software used returned a p-value that was equal to 2.2x10-16 which is the minimum figure that R will report to indicating a p-value that is extremely close to zero. This means that the p-value is likely smaller than 2.2x1016 which is far below the threshold required to disprove the model’s significance. The f-statistic is the more easily interpreted figure in this case and for this model it was found to be 37.82 which, according to the critical f-value of 2.0096, also shows that the model is statistically significant. 
While the model is significant according to both the f-statistic and the p-value, the adjusted R2 value of 0.358 may be lower than some desire. In this case, however, a lower R2 value was anticipated, as there are undoubtedly additional variables that contribute to student retention at higher-education institutions aside from those included. With these figures meeting or exceeding the minimum expectations of this study, model fit could then be examined to further prove the validity of the model’s ability to guide policies.

#### Figure 1: Retention Model's Plotted Residuals
<img src="/assets/images/honors_research/ret_residuals.png" alt = "Retention Residuals">

Figure 1 shows the plotted residuals of this model which gives an idea of the model’s goodness of fit. Ideally, this plot would show characteristics of a null residual plot, one that shows no apparent relationship between the data points. In this case, while there seems to be a cluster of points on the left of the graph and a slight skew to the right, overall, there does not appear to be a clear relationship between the points which indicates a well-fit model. Once model performance had been evaluated, the relationship between the independent variables and retention could be more carefully examined. 

As stated above, each of the variables in the final model had p-values less than 0.05 indicating they were overall statistically significant. Beyond their significance, they all held some level of correlation with the dependent variable. Figure 2 shows the highest correlation in the model which was instructional wage spending per student. Note that 10 institutions were removed from this visualization due to not reporting the instructional wage figures. Furthermore, there were three outliers that, while included in the model, made evaluating the relationship between the variables difficult so they were also removed from this visualization. When removing these outliers, the R2 of relationship experienced an insignificant change and the p-value remained well below the threshold of 0.05 and thus remained significant, so these removals did not significantly influence the relationship.

#### Figure 2: Retention and Instructional Wage Spending per Student
<img src="/assets/images/honors_research/ret_wage_spend.png" alt = "Retention and Wage Spend">

This figure shows a clear, positive, correlation between the two variables indicating that instructional staff salaries in some way influence retention rates at four-year institutions in a positive manner. The same can be said about the relationship between full-time instructional staff and retention as seen in Figure 3. 

#### Figure 3: Retention and % of Full-Time Instructional Staff
<img src="/assets/images/honors_research/ret_fulltime.png" alt = "Retention and Full-Time Instructors">

These results will be discussed further in the discussion portion of this paper, however the positive relationships between these independent variables and retention support the hypothesis that more experienced and more highly compensated staff have a positive impact on student retention. Furthermore, this positive relationship with full-time staff provides and explanation for the collinearity that existed prior to the removal of the tenured faculty variable which would have been closely related to the number of full-time instructional staff. 

### Graduation Model Results

This model included all 401 institutions. Unlike retention, all the institutions in the data set reported their graduation rates meaning the dependent variable was present for all observations. The graduation model’s stepwise process dropped the variables in Table 5.

#### Table 6: Variables Removed from Graduation Model During Stepwise Process
|     VARIABLE REMOVED    |     aic   (Variable)    |     AIC   (Model)    |
|---|---|---|
|     % faculty – lecturers    |     -483.994    |     -482.186    |
|     % faculty – tenured     |     -485.341    |     -483.994    |
|     academic support wage spending   per student    |     -485.492    |     -485.341    |

Unlike the retention model, only three variables were dropped due to insignificance during the backwards steps. However, as Table 6 shows, there were additional variables removed for insignificant p-values. 

#### Table 7: Additional Variables Removed from Graduation model
|     VARIABLE REMOVED    |     Reason       |     justification    |
|---|---|---|
|     % faculty – associate   professors    |     Insignificance    |     p =   0.093 > 0.05    |
|     % faculty – instructors    |     Insignificance    |     p = 0.155 > 0.05    |

In this instance two variables were removed from the model for insignificance and no variables were deemed to have collinear relationships that negatively impacted performance. This model included more variables than the retention model and seemingly performed better. Interestingly, it contained many of the same variables as the previous model, however it also added two new variables, both of which had to do with tenure status. While the percentage of faculty who held tenure was removed from the model for insignificance, the percentage of tenure track faculty and those without tenure status were kept. These variables likely explain more overall variance in the model and hold a higher degree of significance. It can also be assumed that tenure track faculty  
The graduation model’s variables are summarized in Table 8.

#### Table 8: Graduation Model Independent Variables
|  |     estimate    |     std.error    |     p.value    |
|---|---|---|---|
|     (Intercept)    |     0.355    |     0.025    |     7.14E-37    |
|     Instructional   wage spending per student    |     1.68E-05    |     2.20E-06    |     2.19E-13    |
|     Auxiliary   Services Wage spending Per Student    |     1.51E-05    |     5.82E-06    |     0.010    |
|     %   Full-time faculty    |     0.253    |     0.056    |     7.26E-06    |
|     %   faculty – tenure track    |     -0.354    |     0.106    |     0.001    |
|     %   faculty - without tenure    |     -0.209    |     0.061    |     0.001    |
|     %   Faculty – professor    |     0.270    |     0.082    |     0.001    |
|     %   Faculty – assistant professor    |     -0.313    |     0.072    |     1.61E-05    |
|     %   faculty – no academic rank    |     -0.345    |     0.126    |     0.006    |

This model yielded a higher adjusted R2 value, 0.4528, and a higher f-statistic, 41.76. These figures indicate the model was statistically significant and that the combination of variables used in the model make a significant contribution to the explanation of variance in the dependent variable, in this case graduation. As the higher adjusted R2 value would indicate, the goodness of fit of this model was acceptable. 

Figure 4 shows the plotted residuals which further support this claim. The apparent randomness of the points supports the hypothesis that the model accurately depicts a relationship between faculty experience and compensation and student graduation rates. There were, once again, outliers that appeared to skew the residuals right, however the overall plot exhibits no relationship among the points.

#### Figure 4: Graduation Rate Model’s Plotted Residuals
<img src="/assets/images/honors_research/grad_residuals.png" alt = "Grad Model Residuals">

When examining the relationships in the model more closely, again instructional wages per student appeared to be the most significant variable with a p-value of 2x10-16. However, the relationship between the percentage of professor ranked faculty was the next most significant variable with a p-value of 0.0001. When plotted, this relationship becomes clear, as seen in Figure 5.

#### Figure 5: Graduation Rate and % Faculty with Rank of Professor
<img src="/assets/images/honors_research/grad_faculty.png" alt = "Grad Rates and Professors">

This relationship suggests that while the difference between full-time and part-time faculty is less significant in the overall graduation rate of an institution, the experience level of the faculty is. 

### Graduate Earnings Model Results

One issue encountered with this model was that some institutions did not have a figure listed for their graduates’ earnings, and therefore a zero was inserted as a placeholder. These outliers caused a great deal of interference, so any institution that had a zero listed for the independent variable was removed from the sample. This means that instead of 401 observations the dataset included 395. Since this data comes from the internal revenue service, it certainly exists, so it was likely excluded due to the agency not having enough data to report. 

In the early stages of this study, it was hypothesized that earnings would have the least significant model, meaning instructor rank and compensation would have little effect on graduate earnings eight years after program entry. However, with an F-statistic of 70.73 and an adjusted R2 of 0.415, this model was the second best fit and significant of the three evaluated which implies that faculty experience and compensation are better indicators of graduate earnings than they are of retention. 

Table 9 summarizes the variables removed from the model during the backward stepwise regression. Interestingly, both auxiliary wage spending and support wage spending were removed during the stepwise process, unlike the other models where only one of the spending variables was removed. Aside from this oddity, there were no “unusual” removals from the model.

#### Table 9: Variables Removed from Graduate Earnings Model During Stepwise Process
|     VARIABLE REMOVED    |     aic   (Variable)    |     AIC   (Model)    |
|---|---|---|
|     Auxiliary services wage   spending per student    |     8112.578    |     8114.448    |
|     % FACulty  – Associate Professors    |     8110.879    |     8112.578    |
|     Academic support wage spending   per student    |     8109.669    |     8110.879    |

Following the stepwise process, the model was evaluated for collinearity and significance and additional variables, listed in table 8, were removed to improve the overall performance of the model. In this instance, the variance inflation factor was sufficient in catching cases of multicollinearity, and no variables were removed for this reason aside from those that failed the VIF test.

#### Table 10: Additional Variables Removed from Graduate Earnings Model
|     VARIABLE REMOVED    |     Reason    |     justification    |
|---|---|---|
|     % FACULTY –Full-time    |     Collinearity    |     VIF =   23.286 > 9    |
|     % FACULTY– with tenure    |     Collinearity    |     VIF = 17.340 > 9    |
|     % FACULTY – No Academic rank    |     Collinearity    |     CI =   53.394 > 30    |
|     % FACULTY – without Tenure    |     Insignificance    |     p = 0.132 > 0.05    |
|     % FACULTY – assistant professor    |     Insignificance    |     p = 0.163   > 0.05    |
|     % Faculty – instructors    |     Insignificance    |     p = 0.160 > 0.05    |

Unlike any of the previous models, both the full-time and tenured variables were removed from the model. This lack of a significant relationship could potentially be linked back to the relationship between students and professors. Students often build relationships with their instructors that can often lead to connections with potential employers. Many part-time staff continue to work in industry while they teach, meaning that they are able to maintain a connection with those in their field and these current industry connections could lead to fruitful connections between students and employers negating some of the benefits of full-time faculty.

The variables for the graduate earnings model are summarized in table 11.

#### Table 11: Graduate Earnings Model Independent Variables
|  |     estimate    |     std.error    |     p.value    |
|---|---|---|---|
|     (Intercept)    |     32504.12    |     925.2541    |     7.13E-123    |
|     Instructional   wage spending per student    |     1.226119    |     0.094427    |     2.73E-32    |
|     %   Faculty – tenure track    |     -8503    |     3337.899    |     0.011236    |
|     % faCulty   – professor    |     18535.57    |     3925.721    |     3.27E-06    |
|     %   faculty – lecturer    |     22791.09    |     5047.684    |     8.39E-06    |

Figure 6 displays the model’s residual plot. As with the other models, the plot exhibits characteristics of a null residual plot, which is desirable. This, coupled with the adjusted R2 value, indicates a well-fit model, and thus it is safe to say that the model provides a good indication of the relationship between the independent and dependent variables. 

#### Figure 6: Graduate Earnings Model’s Plotted Residuals
<img src="/assets/images/honors_research/earn_residuals.png" alt = "Earnings Residuals">

The graduate earnings model’s performance, as previously mentioned, was considerably better than anticipated, and, like graduation, the strongest variables were instructional wages per student and the percentage of faculty holding the rank of professor. The similar performance and variable relationships exhibited by both the earnings and graduation models prompted an exploration of the relationship between the dependent variables. If there was a positive relationship between these outcomes it would indicate that the pursuit of one of these outcomes would, by consequence, lead to an increase in the other which turned out to be true as seen in Figure 7. This relationship is, of course, relatively intuitive, however it does provide institutions with the ability to pursue two benchmark figures simultaneously without having to implement multiple complicated initiatives as the positive influence of one of the outcomes would have influence on the other. 

#### Figure 7: Six-Year Graduation Rate and Graduate Earnings Eight Years after Entry
<img src="/assets/images/honors_research/grad_earnings.png" alt = "Grad Rate and Earnings">

## Discussion & Conclusion

### Discussion

The results from each of these models show that student first-year retention, graduation rates, and earnings eight years after program entry are significantly influenced by the level of experience held by and compensation of the institution’s instructional staff.  This study both confirms and expands upon some areas of previous work that examined these outcomes and that also seemingly implicated the importance of institutional characteristics, especially the characteristics of instructional staff, to institutional effectiveness at promoting positive student outcomes [1] [4] [6] [16]. Furthermore, it examined three separate outcomes as dependent variables rather than choosing only one, thus providing a clearer indication of how a more robust model can provide indicators of student success. This relationship can be used to help institutions reach their targeted benchmarks through human resource policies and improved hiring criteria.

The positive relationship between staff holding the rank of professor and retention indicated that first-year students are more satisfied with their academic environment when they are exposed to more experienced faculty. This claim is further supported by the apparent negative relationship with negative relationship with the proportion of associate professors, a rank that is commonly held by new or less experienced faculty. Furthermore, there was a negative relationship between non-tenured faculty and retention as seen in Table 5, this could also be used as justification to have a more experienced faculty, as tenure status is typically acquired only after an instructor has been teaching for several years at the institution. 

Faculty experience, therefore, should be a priority of an institution that wishes to maximize retention past the first year. This, coupled with the findings in the graduation model that seem to point towards full-time faculty having a more positive impact on graduation rates, lead to the implication that southern four-year institutions hoping to reduce student attrition should change direction and focus their efforts on trying to retain faculty. This is contrary to the current trend of some institutions that are beginning to fill their vacancies with part-time faculty. This move towards fewer permanent instructors could be due to the lower salaries commanded by adjuncts and part-time lecturers as well as the reduced spending on additional resources that are often not made available to temporary employees [25]. According to the findings of this study, this practice could be undermining attempts to increase retention and graduation rates, factors that play a significant role in the overall performance of institutions.

Regarding the influence of instructor compensation, the most significant and correlated variable across all models was instructional wage spending per student. This is in line with the findings of Syahreza et al who found that employee productivity is higher at firms where they are compensated higher [23]. The idea that compensation is an incentive for performance is not a new claim by any means, however in the scope of this study, the target of which was student outcomes, it shows that instructors are impacting students in a more meaningful and positive way through their interactions as a result of their higher compensation. While no literature could be found specifically examining wage spending per student at institutions, other research examining instructional expenditure has also revealed a relationship between spending and student outcomes, specifically graduation rates, which is significant as wage spending is typically the dominant segment of instructional expenditure [6]. The choice to use instructional wage spending per student over instructional spending per student was essential given that this study sought to examine faculty’s influence on student outcomes and the instructional spending variable often includes additional expenses sometimes entirely unrelated to instructional staff such as academic building depreciation.

While institutions will most likely try to reduce expenditure in coming years due to the unfavorable macroeconomic circumstances the United States is currently facing, this study would suggest that in terms of allocating remaining funds to encourage desirable outcome metrics, instructor salaries need to be a higher priority. While the relationship between salary expenditure and graduate earnings may partially be influenced by the cost of living of the region in which the institution is located, the clear correlation between retention and graduation would not experience any interference because of this. In fact, with instructional wage spending being the only independent variable to make the final model for all three dependent variables, it appears that this is the single most influential instructional staff characteristic examined by this study that could be used to correct student outcomes that are falling short of benchmark figures.

As stated above, it is difficult to compare graduate earnings and instructional wage expenditure since they would both be influenced by the cost of living of the area in which the institution is located. However, the experience of faculty was also significant in the graduate earnings model, specifically the percentage of the faculty holding the rank of professor, which was also significant in the retention model. This would imply, once again, that the more experienced the staff, the more likely student success becomes.

Thus, this study confidently asserts that there is a clear positive relationship between the spending on instructional staff compensation and the degree of experience held by faculty members are essential determinants in student success. There is no doubting the fact that there are other influential characteristics of both institutions and students that will impact these outcomes. However, the relationships uncovered by this paper imply that by spending more on instructional wage expenses and by employing experienced faculty that show signs of being a long-term fit, schools will position themselves more efficiently to reach their targeted benchmarks. 

### Limitations and Areas for Future Study

This study examined the compensation of faculty by looking at institution-level expenditure on instructional wages per student. However, the argument could be made that cost-of-living in some locations may cause a degree of bias in some states. In future studies that plan to explore instructional staff compensation, there should be an attempt to adjust these figures according to the cost-of-living index for the state in which they operate. This may not be possible using expenditure values, however the existing data that looks at the average salaries of instructional staff often overlooks part-time instructors and in many cases, graduate-level instructor salaries cause these values to be inflated. In this study this was overcome by using institution wide expenditure per student which should help, to an extent, provide a more accurate depiction of how an institution compensates their instructors. This did not, however, help in solving issues related to cost-of-living. 

Another limitation of this study was that the characteristics beyond those of instructional staff that influence student outcomes, which were not included in any of the models created. It is possible that other institutional characteristics could partially explain the variance of the dependent variables that was also explained in this study. To alleviate this, and to provide a better indication of the importance of the compensation and experience of instructional staff, multiple other models could be created and compared utilizing a method such as AIC to find which is the “best” subset of institutional characteristics. 

In addition to the implementation of the above improvements, researchers could examine how instructional staff experience prior to entering academia affects their effectiveness at promoting positive student outcomes. Other studies could examine instructional staff at the institution-level and see if there is a relationship between different characteristics. A final recommended course of study could examine instructional staff in different fields to see if faculty differences exist at the major level, as this could provide more specific hiring criteria depending on the department in which the instructor will be teaching.

### Conclusion

This study demonstrates the importance of instructional staff and how their experience and level of compensation influence positive student outcomes. Fortunately, these characteristics can be altered by the institution through the implementation of effective human resource policies, thus creating a faculty body that is more effective. The strategic initiative implied here can be summarized as a “quality over quantity” approach, meaning institutions should focus their efforts on retaining faculty so that they can eventually achieve tenure status. Additionally, institutions should be adequately compensating faculty for their efforts, even at the cost of having fewer instructors overall, as the models created for all three outcome measures showed that instructional wage spending per student was by far the most significant indicator of success. According to the findings of this study, an institution that follows this approach may reach benchmark standards for student outcomes more consistently than those who are relying on solely on adjunct and other part-time instructional staff or are paying their instructional staff at a below average rate.

## Appendix I
### Summary List of Data Aggregations
|  |  |  |  |
|---|---|---|---|
|     Total Spent on Instructional   Wages per Student    |     The total amount that was spent on instructional wages   reported by IPEDS divided by the institution’s total enrollment.    |  |  |
|     Total Spent on Academic Support   Wages per Student    |     The total amount that was spent on academic support   wages reported by IPEDS divided by the institution’s total enrollment.    |  |  |
|     Total Spent on Student Services   and Aux. Services per Student    |     The total amount that was spent on student services and auxiliary   support wages reported by IPEDS divided by the institution’s total   enrollment.    |  |  |
|     Instructional Staff per   Undergrad    |     Total number of instructional staff (IPEDS) divided by   number of undergraduate students.    |  |  |
|     % Full-Time faculty     |     Number of full-time instructional staff divided by total   instructional staff.    |  |  |
|     % Full-Time Tenured Faculty    |     Number of tenured full-time faculty divided by total   instructional staff.    |  |  |
|     % Full-Time Tenure-Tracked   Faculty    |     Number of tenure-tracked full-time faculty divided by   total instructional staff.    |  |  |
|     % Full-Time Non-Tenured Faculty    |     Number of non-tenured full-time faculty divided by total   instructional staff.    |  |  |
|     % Faculty - Professor    |     Number of professor-ranked faculty divided by total   instructional staff    |  |  |
|     % Faculty - Associate Professor    |     Number of associate professor-ranked faculty divided by   total instructional staff    |  |  |
|     % Faculty - Assistant Professor    |     Number of assistant professor-ranked faculty divided by   total instructional staff    |  |  |
|     % Faculty - Instructor    |     Number of instructor-ranked faculty divided by total instructional   staff    |  |  |
|     % Faculty - Lecturer    |     Number of lecturer-ranked faculty divided by total   instructional staff    |  |  |
|     % Faculty - No Academic Rank    |     Number of faculty without an academic rank divided by   total instructional staff    |  |  |

## References

[1] Aaron, B.P. (2013). The Relationship Between Faculty Salary Outlays and Student Retention in Public Four-Year Universities in the Sixteen States of the Southern Regional Education Board. Louisiana State University Doctoral Dissertations. Retrieved on October 2, 2022, from https://digitalcommons.lsu.edu/cgi/viewcontent.cgi?article=4976&context=gradschool_dissertations.

[2] Adamowicz, C. (2007). On adjunct labor and community colleges. Academe, 93(6), 24-27. 

[3] Astin, A.W. (1997). How “Good” is Your Institution’s Retention Rate? Research in Higher Education, 38(6), 647-658. Retrieved October 4, 2022, from https://www.jstor.org/stable/40196281.

[4] Braga, M., Paccagnella, M., & Pellizzari, M. (2016). The Impact of College Teaching on Students’ Academic and Labor Market Outcomes. Journal of Labor Economics, 34(3), 781–822. doi: https://doi.org/10.1086/684952.

[5] Cuseo, J. (2010). The Empirical Case Against Large Class Size. Retrieved November 7, 2022, from https://ir.stonybrook.edu/xmlui/bitstream/handle/11401/68616/2010-09-28%20Regarding_Class_Size.pdf.

[6] Dahlviga C.A., Dahlvig J.E., & Chatriand, C.M. (2020). Institutional Expenditures and Student Graduation and Retention. Christian Higher Education, 19(5), 352-364. doi: https://doi.org/10.1080/15363759.2020.1712561.

[7] Fung, T.Y. (2010). Analysis of Graduation Rates for Four-year Colleges: A Model of Institutional Performance Using IPEDS. University of North Texas ProQuest Dissertations Publishing. Retrieved on October 4, 2022, from https://www.proquest.com/openview/b3c2abe8a3c54747cb6301b72c7d6d1e/1?cbl=18750&pq-origsite=gscholar.

[8] Goenner, C.F. & Snaith S.M. (2004). Predicting Graduation Rates: An Analysis of Student and Institutional Factors at Doctoral Universities. Journal of College Student Retention: Research, Theory & Practice, 5(4), 409-420. doi: https://doi.org/10.2190/LKJX-CL3H-1AJ5-WVPE.

[9] Griffin, K.A. & Reddick, R.J. (2011). Surveillance and Sacrifice: Gender Differences in the Mentoring Patterns of Black Professors at Predominantly White Research Universities. American Education Research Journal, 48(5), 1032-1057. doi: https://doi.org/10.3102/0002831211405025.

[10] Hastie, T., Tibshirani, R., & Friedman Jerome. The Elements of Statistical Learning. New York, NY: Springer-Verlag, 2009. doi: 10.1007/b94608.

[11] Hobson, C.J., Griffin, A., Novak, J.M., Mitchell, M.B., Szostek, J., Burosh, J., & Hobson, A. (2022). Comparing Trends in Hispanic and White College Student Six-Year Graduation Rates using IPEDS Data. Journal of Hispanic Higher Education, 0(00), 1-12. Advance online publication. doi: https://doi.org/10.1177/153819272211172.

[12] Horn, A.S. & Lee, G. (2015). The Reliability and Validity of Using Regression Residuals to Measure Institutional Effectiveness in Promoting Degree Completion. Research in Higher Education, 57, 469-496. doi: 10.1007/s11162-015-9394-7.

[13] Kane, T., & Orszag, P. (2003). Funding restrictions at public universities: Effects and Policy implications. Retrieved on October 4, 2022, from https://www.brookings.edu/research/funding-restrictions-at-public-universities-effects-and-policy-implications/.

[14] Love D (2009). Student Retention Through the Lens of Campus Climate, Racial Stereotypes, and Faculty Relationships. Journal of Diversity Management, 4(3), 21–26. doi: https://doi.org/10.19030/jdm.v4i3.4962.

[15] Marsh, G. (2016). Institutional Characteristics and Student Retention in Public 4-Year Colleges and Universities. The Journal of College Student Retention, 16(1), 127-151. doi: https://doi.org/10.2190/CS.16.1.

[16] Mehta, M.H., Chauhan, N.C., & Gokhale, A. (2021). Predicting Institute Graduation Rate with Genetic Algorithm Assisted Regression for Education Data Mining. ICTACT Journal on Soft Computing, 11(2), 2266-2278. Retrieved October 2, 2022, from https://ictactjournals.in/paper/IJSC_Vol_11_Iss_2_Paper_4_2266_2278.pdf.

[17] Melguizo, T., & Strober, M. H. (2007). Faculty Salaries and the Maximization of Prestige. Research in Higher Education, 48(6), 633–668. Retrieved October 4, 2022, from https://www.jstor.org/stable/25704522.

[18] Rozi, A., & Sunarsi, D. (2020). The Influence of Motivation and Work Experience on Employee Performance at PT. Yamaha Saka Motor in South Tangerang. Jurnal Office, 5(2), 65-74.

[19] Schmidt, P. (2008). Use of part-time instructors tied to lower student success. Chronicle of Higher Education, 55(12). Retrieved October 4, 2022, from https://www.chronicle.com/article/use-of-part-time-instructors-tied-to-lower-student-success/.

[20] Stout, R., Archie C., Cross, D., & Carman, A.C. (2018) The Relationship Between Faculty Diversity and Graduation Rates in Higher Education. Intercultural Education, 29(3), 399-417. doi: https://doi.org/10.1080/14675986.2018.1437997.

[21] Sumali, M. (2020). College Cost-Benefit Analysis Using Linear Regression Analysis, Pandas, and Seaborn. New Mexico Journal of Science, 54(2), 122-137.

[22] Swani, K., Wamwara, W., Goodrich, K., Schiller, S., & Dinsmore, J. (2022). Understanding business student retention during covid-19: roles of service quality, college brand, and academic satisfaction, and stress. Services Marketing Quarterly, 43(3), 329-352. doi: 10.1080/15332969.2021.1993559.

[23] Syahreza, D. S., Lumbanraja, P., Dalimunthe, R. F., & Absah, Y. (2017). Compensation, Employee Performance, and Mediating Role of Retention: A Study of Differential Semantic Scales. European Research Studies Journal, 20(4A), 151-159. Retrieved November 6, 2022, from https://www.um.edu.mt/library/oar/handle/123456789/32576.

[24] Hollingsworth R. (2012). Retention Improvement: Reflecting on Current and Future Actions to Improve Retention – a Brief Written by Jason Pieratt on Behalf of the Division of Undergraduate Education. Undergraduate Education Faculty Presentations, 4. Retrieved October 16, 2022, from https://uknowledge.uky.edu/uge_present/4.

[25] Thirolf, K.Q. & Woods, R. (2018). Contingent Faculty at Community Colleges: The Too-Often Overlooked and Under-Engaged Faculty Majority. New Directions for Institutional Research, 176, 55-65. doi: https://doi.org/10.1002/ir.20244.

[26] Tinto, V. (2006). Research and Practice of Student Retention: What Next? Journal of College Student Retention. 8, 1-19. Retrieved October 2, 2022, from https://journals.sagepub.com/doi/pdf/10.2190/4YNU-4TMB-22DJ-AN4W.

[27] Xu, D. & Ran, F.X. (2020). The Impacts of Different Types of College Instructors on Students’ Academic and Labor Market Outcomes. Journal of Policy Analysis and Assessment, 40(1), 225-257. doi: https://doi.org/10.1002/pam.22270.

[28] Yu, H., Campell, D., & Mendoza, P. (2015). The Relationship Between the Employment of Part-Time Faculty and Student Degree and/or Certificate Completion in Two-Year Community Colleges. Community College Journal of Research and Practice, 39(11), 986-1006. doi: 10.1080/10668926.2014.918910.

[29] Zong, C. & Davis, A. (2022). Modeling University Retention and Graduation Rates Using IPEDS. Journal of College Student Retention: Research, Theory, and Practice, 0(00), 1-23. Advance online publication. doi: https://doi.org/10.1177/15210251221074379.
