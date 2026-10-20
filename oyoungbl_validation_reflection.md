# Validation reflection

I validated five fields (HasRecovered, WhyRecovered, ActivityPattern, Currentstatus, RecentThemes) across jaktseat's ten projects. 36 of the 50 comparisons agreed before discussion, and 14 did not: 6 in RecentThemes, 4 in WhyRecovered, 2 in HasRecovered, 2 in ActivityPattern, and none in Currentstatus. A live discussion was not possible, so my evidence-based values became the consensus.

**What came before long gaps.** The long gaps followed a burst of work and then a quiet period, or a single maintainer's attention moving elsewhere. In fredros\_pypmc, heavy activity in 2013 to early 2015 was followed by a 12-month gap (2015-08 to 2016-07). In pbs-assess\_gftrends, activity comes in bursts (73, 130 and 47 commits in 2021 to 2023) with near-zero months between. In my own MiniProject2 projects, jalammar\_ecco and skuschel\_postpic had one main maintainer and went quiet when that person did. Several gaps also fall in a project's first months (eclipse\_sumo, ecp-copa\_cabana, rpng\_open\_vins, and florianhartig\_dharma in my own set), where the project had barely started.

**What triggered recovery.** Recovery usually came from new people or from outside pressure. In fredros\_pypmc a new maintainer (Frederik Beaujean) bumped the version to 1.1 and updated the docs. In my own projects, new contributors restarted druid-io\_pydruid and jalammar\_ecco, and a dependency and packaging cleanup (nose to nose2) restarted skuschel\_postpic. A recurring data or report cycle also pulled work back, as in pbs-assess\_gftrends (the 2023 report data update) and nwfsc-cb\_ocnms (the yearly data update).

**When gaps don't mean project death.** Gaps of one or two months (eclipse\_sumo, ecp-copa\_cabana) are normal pauses, not inactivity. florianhartig\_dharma's 15-month gap was a repository waiting for its package to be written. radiomics\_pyradiomics paused commits for 4 months while issues kept being opened and answered. juliamolsim\_dftk.jl shows regular peaks and troughs rather than decay. By contrast, some projects look alive in the data but are close to dormant, like pbs-assess\_gftrends, which has 0 to 3 commits a month after 2023-03.

**Recurring pitfalls and how they were resolved.**

* **Theme labels used as reasons.** The author's WhyRecovered values were theme labels (for example, Other, Documentation updates) instead of an explanation. I used a before -> after description based on the post-gap commits.
* **"Other" and bot misclassification.** An automated classifier labeled a 2005 gap as bot-driven (cp2k\_dbcsr), and defaulted to Other for most RecentThemes. Reading the actual commits fixed these.
* **Blank versus not applicable.** The author left HasRecovered and WhyRecovered blank for projects with no gap. I treated these as "No" and "no recovery phase" and noted it.
* **Gap thresholds.** A 1 or 2-month gap was counted as a recovery. I applied the 3-month rule consistently.
* **Different data windows.** The author's data ended in 2020 and 2021 for some repositories, so "recent" commits differ from the repository's real latest commits. Where I used the latest commits instead, I said so in KeyEvidence.
* **Judgment calls in ActivityPattern.** Steady versus cyclical (iqss\_dataverse) and cyclical versus irregular (juliaopt\_jump.jl) depend on how regularly the peaks repeat. I checked the spacing of peaks in the plots instead of relying on peak size.

