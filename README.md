# Adult Attachment Application in R

This is a psychometrics project delivered to the *Pyschometric Analysis* course I took in Italy. The data was collected from answers to the interactive version of the <a href="https://openpsychometrics.org/tests/ECR.php" target="_blank">Experiences in Close Relationships Scale</a> on adult romantic attachment style developed in 1998 by Kelly Brennan, Catherine Clark and Phillip Shaver. Attachment style is how an individual behaves in relationships with others. The theory behind it is the theory of romantic, or pair-bond and attachment as it was originally formulated by C. Hazan and P. R. Shaver in 1987. 

Ever since Hazan and Shaver (1987) showed that it is possible to use a self-report questionnaire to measure adolescent and adult romantic-attachment orientations, that is, secure, anxious, and avoidant (the three patterns identified by Ainsworth, Blehar, Waters, and Wall in 1978 in their studies of infant-caregiver attachment), a steady stream of variants and extensions of their questionnaire have been proposed. The resulting diversity often gave rise to frustration and confusion in newcomers to the field who wonder which of the many measures to use. In their study Self-report measurement of adult romantic attachment: An integrative overview (1998), Brennan by K. A., Clark, C. L., & Shaver, P. R. attempted to solve this problem by creating an all-purpose reply to future attachment researchers who wish to use self-report measures. 

From their study chapter, the results were promising and suggest that self-report attachment research might benefit from the use of the two scales. One of the scales developed was ECR scale, and they used factor analysis on the ECR scale, they found an alpha of 0.94 for Avoidance and alpha of 0.91 for Anxiety dimensions. *The respective two dimensions of Avoidance and Anxiety and their corresponding alpha results are exactly what I obtained in the presented report.*

---
Dataset:
- <a href="https://openpsychometrics.org/_rawdata/" target="_blank">Answers to Experiences in Close Relationships Scale</a>
    - **Download**: ECR-data-1March2018.zip | **Updated**: 1/03/2018

---
References:
- <a href="https://www.researchgate.net/publication/301325948_Self-report_measurement_of_adult_attachment_An_integrative_overview" target="_blank">Original Paper: Self-report measurement of adult attachment: An integrative overview</a>
- <a href="https://labs.psychology.illinois.edu/~rcfraley/measures/measures.html" target="_blank">Elaborative Page</a>
- <a href="https://labs.psychology.illinois.edu/~rcfraley/measures/brennan.html" target="_blank">Summary Results</a>
- <a href="https://labs.psychology.illinois.edu/~rcfraley/measures/brennan.html" target="_blank">Choosing the Right Type of Rotation in PCA and EFA</a>


## Project Setup

It is sufficient to run the R notebook `psych.Rmd` in Rstudio with the `psy_data.csv`, and you will receive a pop-up notification to install all the package dependencies. 

In case that didn't happen for some reason, you can simply follow the following steps in the R terminal inside Rstudio:

- Install the package `renv`: `install.packages("renv")`
- Set the right R working directory: `setdw("~\\attachmentR")`
- Run the following: `renv::restore()`

If you want just to go through the already published report, you can view the `psych_report.html` for that purpose.