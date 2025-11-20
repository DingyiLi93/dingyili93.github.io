---
title: "Research"
layout: single
permalink: /research/
---

## Job Market Paper

**[Efficient and Doubly Robust Estimation of the Average Treatment Effect with Confounders Missing Not at Random](https://dingyili93.github.io/files/doubly_robust_mnar.pdf)**

<button class="abstract-button" onclick="toggleAbstract('abstractContent1', this)">▶ Abstract</button>
<div id="abstractContent1" class="abstract-content" style="display: none;">
When confounders are missing not at random, the conditional independence required for causal inference does not hold, undermining identification of causal parameters. We consider scenarios where confounder missingness depends on themselves but is independent of the outcome conditional on the treatment and confounders. We propose an efficient and doubly robust estimator of the average treatment effect (ATE) that adjusts for confounder missingness through novel propensity scores and conditional average treatment effects. The adjustment relies on two integral equations, one of which is new. Solving integral equations relies on the completeness of the full-data distribution in the outcome. We propose a low-rank assumption on the missingness mechanism, extending the analysis to empirical settings with limited outcome variation, such as binary outcomes. Our estimator is doubly robust, remaining consistent if either integral equation holds, and rate doubly robust, achieving $\sqrt{n}$--consistency when both propensity scores and conditional average treatment effects converge at the fourth-root rate. We then derive the semiparametric efficiency bound for the ATE under the outcome-independent missingness condition and show that our estimator achieves the bound. We evaluate our estimator with simulations and three empirical applications: the impact of the Job Corps program on employment, the effect of smoking on blood lead levels, and the influence of education on general health satisfaction.
</div>


## Working Papers

**[Identification and Estimation of Finite Mixtures of Multinomial Logit Models](https://dingyili93.github.io/files/Pure_products_for_consideration_set__write_up.pdf)** 

<button class="abstract-button" onclick="toggleAbstract('abstractContent2', this)">▶ Abstract</button>
<div id="abstractContent2" class="abstract-content" style="display: none;">
Finite mixtures of multinomial logit models can be used to capture consumer choice heterogeneity across multiple markets when only aggregate consumer choices per market are available. A motivating example is a nested logit where the composition of each mixture component (each nest of alternatives) is unknown a priori. We show that in order to identify these models, it suffices to require that each mixture component includes at least two component-exclusive alternatives. We refer to our assumption as the pure-alternatives condition, and we argue it is a natural extension of the anchor-word assumption used commonly in nonnegative matrix factorization problems in machine learning. Our identification result enables a consistent two-step estimator as the number of consumers, markets, and alternatives grow large. Applying this framework to the U.S. vehicle market, we find that consumer heterogeneity does not yield substitution patterns between electric and internal combustion engine vehicles, suggesting consumer segments are distinctly aligned with specific vehicle types without crossover substitution.
</div>

**[On the Testability of the Anchor-Words Assumption in Topic Models](https://dingyili93.github.io/files/Testing_for_Anchor_Words.pdf)** 
\[_Revision at Quantitative Economics_\] with [Simon Freyaldenhoven](https://simonfreyaldenhoven.github.io/), [Shikun Ke](https://sites.google.com/site/fannan2316/), and [José Luis Montiel Olea](https://www.sagarsxn.com/) 

<button class="abstract-button" onclick="toggleAbstract('abstractContent3', this)">▶ Abstract</button>
<div id="abstractContent3" class="abstract-content" style="display: none;">
Topic models are a simple and popular tool for the statistical analysis of textual data. Their identification and estimation is typically enabled by assuming the existence of anchor words; that is, words that are exclusive to specific topics. In this paper we show that the existence of anchor words is statistically testable: There exists a hypothesis test with correct size that has nontrivial power. This means that the anchor-words assumption cannot be viewed simply as a convenient normalization. Central to our results is a simple characterization of when a column-stochastic matrix with known nonnegative rank admits a separable factorization. We test for the existence of anchor words in two different data sets derived from monetary policy discussions in the Federal Reserve  and reject the null hypothesis that anchor words exist in one of them.
</div>

## Work in Progress

**Systemic Risk, FOMC Statements, and Monetary Policy Shocks: A New Topic Model to Associate Text with Metadata** \[_Draft Upon Request_\]
with [Shawn Mankad](https://mankad-research.github.io/) 

<button class="abstract-button" onclick="toggleAbstract('abstractContent4', this)">▶ Abstract</button>
<div id="abstractContent4" class="abstract-content" style="display: none;">
In this research paper, we investigate the regulations guiding monetary policy communications through the development of a novel machine learning method called the Cluster Sentence Structural Topic Model (CSSTM). Our approach incorporates covariates in the data generation process and accounts for the correlation of sentences within each document by utilizing the equilibrium of sentences’ topics. In the estimation process, we sort the equilibrium in the M step. Our method outperforms the Latent Dirichlet Allocation (LDA) and the Structural Topic Model (STM) by increasing the held-out likelihood by 20 percent and 10 percent. Using our method, we analyze FOMC statements and observe that the Fed places more emphasis on inflation expectations as opposed to current rates. According to our results, FOMC statements rely more on production instead of consumption. More importantly, we find that monetary policy commu-nication started to consider systemic risk shortly after the 2007 financial crisis. By our method, we are able to decompose monetary policy shocks. The new measure has large and significant effects on systemic risk.
</div>

**Pollution Avoidance and Willingness-to-Pay: Evidence from Travel Mode Choice in Beijing** \[_Draft Upon Request_\]
with [Shanjun Li](https://shanjunli6.github.io/) and [C.-Y. Cynthia Lin Lawell](https://clinlawell.dyson.cornell.edu/)

<button class="abstract-button" onclick="toggleAbstract('abstractContent5', this)">▶ Abstract</button>
<div id="abstractContent5" class="abstract-content" style="display: none;">
We estimate the short-term willingness-to-pay (WTP) to avoid air pollution by developing a model to capture the trade-offs between avoidance behavior and its costs. In particular, we use fine-scale travel survey data in Beijing to model the trade-offs between indoor and outdoor travel modes for compulsory work trips during highly polluted hours. Our model indicates that the short-term WTP, which we estimate to be 0.00223 dollars per hour to avoid 1 µg/m3 of ambient fine particles (PM2.5), forms the lower bound for the long-term WTP, which is around 11.536 dollars per year to avoid 1 µg/m3 PM2.5. Our estimation strategy uses a machine learning IV method in a high-dimensional econometrics setting. We find that longer potential exposure to air pollution prevents people from walking and cycling. People older than 55 years old, who are more vulnerable to pollution and thus more likely to avoid pollution, have a 28% higher WTP than the young. Likewise, richer people, who value their health more, are willing to avoid a unit of pollution with 36% more cost. Finally, we find evidence that information affects the behavioral adjustment: people start to reduce their exposure to the toxic air only after extensive media coverage of air pollution.
</div>

**Weak Sparse Models and Methods for Instrumental Variables** 

<script>
    function toggleAbstract(abstractId, button) {
        var abstractContent = document.getElementById(abstractId);
        if (abstractContent.style.display === "none" || abstractContent.style.display === "") {
            abstractContent.style.display = "block";
            button.innerHTML = "▼ Abstract";
        } else {
            abstractContent.style.display = "none";
            button.innerHTML = "▶ Abstract";
        }
    }
</script>

<style>
    .abstract-button {
        background: none;
        border: none;
        color: #333; /* Adjust the color to match your text */
        cursor: pointer;
        font-size: 1rem;
        padding: 0;
        text-align: left;
        display: inline;
    }

    .abstract-button:hover {
        text-decoration: underline; /* Optional: add underline on hover */
    }
    
    .abstract-content {
        display: none;
        margin-bottom: 1.5rem; /* Ensure space after abstract content */
        font-size: 1rem; 
        text-align: justify; /* Justify text alignment */ 
    }
</style>
