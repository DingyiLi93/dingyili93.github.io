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

**Short-Term Impact of the Trade War on U.S. Agricultural Commodities Futures Prices** \[_Draft upon request_\]

<button class="abstract-button" onclick="toggleAbstract('abstractContent1', this)">▶ Abstract</button>
<div id="abstractContent1" class="abstract-content" style="display: none;">
This study investigates the short-run effects of the U.S.-China trade war on U.S. agricultural futures
prices, focusing on five primary commodities: soybeans, corn, wheat, rice, and oats. Initiated in early 2018 by
President Trump, the trade war resulted in substantial tariffs imposed by both countries, severely impacting
the U.S. agricultural sector. To mitigate farmers’ losses, the U.S. government introduced $28 billion in trade
aid packages for farmers. This paper utilizes daily futures price data for these grains from 2004 to 2020 and
comprehensive supply and demand factors. Due to the non-stationarity of the data, first-difference regressions
are employed to quantify the price effects of tariffs and government payments. The findings indicate that
a 25% Chinese tariff on U.S. soybeans led to a significant decrease in soybean and wheat futures prices,
highlighting the severe short-term impacts of trade barriers on agricultural markets. Additionally, the analysis
reveals that the massive trade aid payments had mixed effects on futures prices, challenging the assumption
that such payments would not further distort the market.
</div>

## Publications

Yu, Shuo*, Nicola Falco, Nivedita Patel, Yuxin Wu, and Haruko Wainwright. "**Diverging climate response of corn yield and carbon use efficiency across the US.**" Environmental Research Letters 18, no. 6 (2023): 064049. [`Journal Version`](https://github.com/shuoy528/shuoyu/raw/master/files/Yu_2023_Environ._Res._Lett._18_064049.pdf) [`Replication`](https://github.com/shuoy528/erl-div-clim-resp)

<button class="abstract-button" onclick="toggleAbstract('abstractContent2', this)">▶ Abstract</button>
<div id="abstractContent2" class="abstract-content" style="display: none;">
In this paper, we developed an open-source package to analyze the overall trend and responses of
both carbon use efficiency (CUE) and corn yield to climate factors for the contiguous United
States. Our algorithm enables the automatic retrieval of remote sensing data through Google Earth
Engine (GEE) and U.S. Department of Agriculture (USDA) agricultural production data at the
county level through an application programming interface (API). Firstly, we integrated satellite
products of net primary productivity and gross primary productivity based on the Moderate
Resolution Imaging Spectroradiometer (MODIS) sensor, and climatic variables from the European
Centre for Medium-Range Weather Forecasts. Secondly, we calculated CUE and commonly used
climate metrics. Thirdly, we investigated the spatial heterogeneity of these variables. We applied a
random forest algorithm to identify the key climate drivers of CUE and crop yield, and estimated
the responses of CUE and yield to climate variability using the spatial moving window regression
across the U.S. Our results show that growing degree days (GDD) has the highest predictive power
for both CUE and yield, while extreme degree days (EDD) is the least important explanatory
variable. Moreover, we observed that in most areas of the U.S., yield increases or stays the same
with higher GDD and precipitation. However, CUE decreases with higher GDD in the north and
shows more mixed and fragmented interactions in the south. Notably, there are some exceptions
where yield is negatively correlated with precipitation in the Missouri and Mississippi River Valleys.
As global warming continues, we anticipate a decrease in CUE throughout the vast northern part
of the country, despite the possibility of yield remaining stable or increasing.
</div>

## Work in Progress

**Designing Insurance under Climate Change** 
with [Francis Annan](https://sites.google.com/site/fannan2316/) and [Sagar Saxena](https://www.sagarsxn.com/) \[_Model development stage_\]

**Optimal SWD Management in Michigan and North Carolina Blueberry: A Dynamic Structural Model with Unobserved Heterogeneity**  
with [Miguel I. Gómez](http://gomez.dyson.cornell.edu/), [Philip Fanning](https://sbe.umaine.edu/philip-fanning/), [Rufus Isaacs](https://www.canr.msu.edu/people/rufus_isaacs), [Sergio Puerto Gonzalez](https://www.sergiopuerto.com/), and [C.-Y. Cynthia Lin Lawell](https://clinlawell.dyson.cornell.edu/). [`Master's Thesis Version`](https://github.com/shuoy528/shuoyu/raw/master/files/Yu_cornell_0058O_10730.pdf) \[_Model development stage_\]

<button class="abstract-button" onclick="toggleAbstract('abstractContent3', this)">▶ Abstract</button>
<div id="abstractContent3" class="abstract-content" style="display: none;">
This paper analyzes the management strategies employed by Michigan highbush blueberry growers to combat Spotted Wing Drosophila (SWD), an invasive vinegar fly originating from East Asia that poses a significant threat to fruit crops. A dynamic structural econometric model is developed to study growers' decisions related to fly and larva monitoring as well as insecticide application. The model is applied to a comprehensive dataset comprising daily decision records of blueberry growers in Michigan. The findings provide insights into the effectiveness of various management strategies and their implications for economic outcomes in the agricultural sector.
</div>

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
    }
</style>
