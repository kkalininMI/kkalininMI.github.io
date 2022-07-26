---
layout: archive
title: "Book Project"
permalink: /book/
author_profile: true
---

"Election Fraud in Authoritarian Regimes: Methods and Theories"
------

My book is based on my dissertation [The Essays on Election Fraud in Authoritarian Regimes](https://deepblue.lib.umich.edu/bitstream/handle/2027.42/138588/kkalinin_1.pdf?sequence=1&isAllowed=y), which focuses on methodological and theoretical aspects of statistical detection of election fraud in authoritarian regimes.  The purpose of the book is to improve our theoretical understanding of election fraud in autocracies, especially in Russia, to develop methodological toolkit of election forensics, and to test new methods of election forensics on all Russian federal elections (2000-2021).


Book Structure
------


**Chapter 1. Election Fraud: Methods and Tools**

Election forensics methods are based on the idea that human manipulations tend to leave distinctive traces in vote counts. Some manipulations are frauds and some stem from the normal strategic activities inherent to politics. Anomalies must be detectable by statistical methods.  This chapter covers the most popular methodological approaches to analysis of election fraud: digit tests, parametric and nonparametric models, quasi-experimental designs.


**Chapter 2. Election Forensics Toolkit and Its Application**

The <i>Election Forensics Toolkit</i> website (also, an R package) is a prototype that implements several methods that have been proposed as useful accuracy diagnostics. The Toolkit reflects the idea that anomalous patterns are more likely to be evidence of fraud if found consistently across multiple statistical techniques.  This Chapter is designed to demonstrate the basic functionality of the <i>Election Forensics Toolkit</i>.


**Chapter 3. Validating New Methods of Election Forensics Analysis**

Using the data from Russian federal elections (2000-2021) this chapter aims to compare two election forensics methods: Bayesian version of the finite mixture model developed by Walter Mebane, and nonparametric approach based on vote-turnout histograms proposed by Sergey Shpilkin.  This part includes election forensics analysis and four validation studies from different elections. In addition, this chapter proposes two alternative methods based on univariate finite mixture models, as well as an algorithm designed to extract precinct-level estimates of election fraud from a nonparametric method.


**Chapter 4. Election Fraud and Signaling Approach**

In this chapter I propose that the pattern of fraudulent elections in Russia can be explained by combining an idea about federalism with a game-theoretic model of the relationship between the Kremlin and a single regional governor. Specifically, election fraud becomes a basic signaling mechanism of regional bosses' loyalty and of their ability to control the administrative resources to the Kremlin's benefit. If electoral signaling occurs, data manipulation is most likely to take place with 0s and 5s in the last digit of rounded percentages of turnout and electoral support, which is the easiest and most readily detected way to report basic information to superiors. Based on the Russian electoral and financial data for 2000-2018, my analysis shows strong evidence of election fraud associated with the post-electoral interbudgetary transfers.


**Chapter 5. Election Fraud and Preference Falsification**

This chapter sheds new light on whether responses to public opinion polls, namely, preference falsification, can affect the level of election fraud by employing the Kuran's model of preference falsification, which is empirically tested on the data collected from the most recent presidential campaign in Russia (2012).  My research findings reveal the presence of a statistically significant effect of preference falsification on election fraud, thus enabling me to conclude that preference falsification is, indeed, conducive to election fraud. My findings can be generalized to a broad set of electoral autocracies, enabling scholars to get a better understanding of the mechanism by which survey polls can incentivize officials to commit election fraud.


**Chapter 6. Election Fraud and Political Protests**

This chapter explores whether new measures of election fraud from Chapter 3, can serve as good predictors of the Russian post-electoral protests in the 2011 parliamentary and 2012 presidential elections.  For the purpose of this research I'll be utilizing highly disaggregated electoral data from both elections, as well as the data on protests from the ICEWS dataset.


**Chapter 7. Election Fraud and Political Survival of Subnational Actors**

Since the political survival of governors in Russia largely depends on their ability to address the Kremlin's electoral needs during the federal elections, the governors tend to resort to election fraud in both parliamentary and presidential elections. This Chapter aims to study the degree to which election fraud helps governors to extend their terms in office by analyzing three major periods: 2000-2005 electoral period, when the governors were elected by their regional electorate; 2005-2012 appointment period, when the governors were appointed by the Kremlin; 2012-present post-appointment electoral period, when the gubernatorial elections were restored. In this chapter I develop the theory of gubernatorial survival in Russia, formulate research hypotheses and test said hypotheses using a Cox proportional hazards model, which includes finite mixture estimates and last digits in percentages tests as primary measures of election fraud.


Parts of the book project have been previously published in the following forms:


Kalinin, Kirill (2022). [Signaling Games of Election Fraud: A Case of Russia]("https://brill.com/view/journals/rupo/7/2/article-p210_3.xml"). <i>Russian Politics</i>.

Kalinin, Kirill (2019). [Validation of the Finite Mixture Model Using Quasi-Experimental Data and Geography](http://electoralpolitics.org/en/articles/validatsiia-konechnoi-smeshannoi-modeli-s-ispolzovaniem-kvazieksperimentalnykh-i-geograficheskikh-dannykh/). <i>Electoral Politics</i>.

Kalinin, Kirill (2017). [Linking Preference Falsification and Election Fraud In Electoral Autocracies](http://journals.sagepub.com/doi/abs/10.1177/0032321717706013).  <i>Political Studies</i>. 

Kalinin, Kirill (2016). [A Study of Social Desirability Bias at the Russian Presidential Elections 2012](http://www.tandfonline.com/doi/abs/10.1080/17457289.2016.1150284).  <i>Journal of  Elections, Public Opinion and Parties</i>.