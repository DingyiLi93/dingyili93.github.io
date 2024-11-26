---
title: "Research"
layout: single
permalink: /research/
---

## Job Market Paper

**[Identification and Estimation of Finite Mixtures of Multinomial Logit Models](https://dingyili93.github.io/files/Pure_products_for_consideration_set__write_up.pdf)** 

<button class="abstract-button" onclick="toggleAbstract('abstractContent1', this)">▶ Abstract</button>
<div id="abstractContent1" class="abstract-content" style="display: none;">
Finite mixtures of multinomial logit models can be used to capture consumer choice heterogeneity across multiple markets when only aggregate consumer choices per market are available. A motivating example is a nested logit where the composition of each mixture component (each nest of alternatives) is unknown a priori. We show that in order to identify these models, it suffices to require that each mixture component includes at least two component-exclusive alternatives. We refer to our assumption as the pure-alternatives condition, and we argue it is a natural extension of the anchor-word assumption used commonly in nonnegative matrix factorization problems in machine learning. Our identification result enables a consistent two-step estimator as the number of consumers, markets, and alternatives grow large. Applying this framework to the U.S. vehicle market, we find that consumer heterogeneity does not yield substitution patterns between electric and internal combustion engine vehicles, suggesting consumer segments are distinctly aligned with specific vehicle types without crossover substitution.
</div>

## Working Papers

**[On the Testability of the Anchor-Words Assumption in Topic Models](https://dingyili93.github.io/files/Testing_for_Anchor_Words.pdf)** 
with [Simon Freyaldenhoven](https://simonfreyaldenhoven.github.io/), [Shikun Ke](https://sites.google.com/site/fannan2316/), and [Pepe Montiel Olea](https://www.sagarsxn.com/) 

<button class="abstract-button" onclick="toggleAbstract('abstractContent2', this)">▶ Abstract</button>
<div id="abstractContent2" class="abstract-content" style="display: none;">
Topic models are a simple and popular tool for the statistical analysis of textual data. Their identification and estimation is typically enabled by assuming the existence of \emph{anchor words}; that is, words that are exclusive to specific topics. In this paper we show that the existence of anchor words is statistically testable: There exists a hypothesis test with correct size that has nontrivial power. This means that the anchor-words assumption cannot be viewed simply as a convenient normalization. Central to our results is a simple characterization of when a column-stochastic matrix with known nonnegative rank admits a \emph{separable} factorization. We test for the existence of anchor words in two different data sets derived from monetary policy discussions in the Federal Reserve  and reject the null hypothesis that anchor words exist in one of them.
</div>

**Systemic Risk, FOMC Statements, and Monetary Policy Shocks: A New Topic Model to Associate Text with Metadata** \[_Draft upon request_\]
with [Shawn Mankad](https://mankad-research.github.io/) 

**Pollution Avoidance and Willingness-to-Pay: Evidence from Travel Mode Choice in Beijing** \[_Draft upon request_\]
with [Shanjun Li](https://shanjunli6.github.io/) and [C.-Y. Cynthia Lin Lawell](https://clinlawell.dyson.cornell.edu/)

## Work in Progress

**Weak Sparse Models and Methods for Instrumental Variables** 

<script>
    function toggleAbstract(abstractId, button) {
        var abstractContent = document.getElementById(abstractId);
        var button = document.querySelector(".abstract-button");
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
