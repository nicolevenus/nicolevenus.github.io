---
title: "Research"
permalink: /research/
layout: single
author_profile: true
---

## Working papers

[**Sources and Consequences of Systemic Content Bias: Evidence from Wikipedia**](https://nicolevenus.github.io/assets/NVenus_systemic_content_bias.pdf)  
[Show Abstract](#){: .abstract-link data-target="abs1" }

<div id="abs1" class="abstract-modal">
  <div class="abstract-content">
    <button class="close-btn" onclick="closeAbstract('abs1')">&times;</button>
    <p>
      This paper examines the systemic bias against female scholars in Wikipedia content. Based on Wikipedia meta-data matched with rich panel data on a large sample of economists, psychologists and mathematicians, I estimate the gender gap in the likelihood that scholars receive a biographical entry conditioning on Wikipedia's own metric of relevance, the notability criteria. I show that while female economists are unconditionally around half as likely to have a biographical entry than their male colleagues, the gender gap in representation reduces to 9% conditioning on the notability criteria. This gap is even larger in psychology and reversed in mathematics. Over time the conditional gender gap in the representation of economists has closed, supported by Wikipedia editors organized in grassroots activist groups aimed at combating systemic bias on the platform. Leveraging the staggered introduction of a new content translation tool across language editions to predict page creations, I estimate the causal effect of having a biographical entry on Wikipedia on a researcher's news mentions. My findings underscore the importance of systemic biases: having a Wikipedia biography generates two additional news mentions per year. This demonstrates that content biases on digital knowledge platforms have implications that extend far beyond the platforms themselves, affecting which scientific knowledge is transmitted to a wider audience.
    </p>
  </div>
</div>

---

[**Women in Editorial Boards: An Investigation of Female Representation in Top Economic Journals**](https://nicolevenus.github.io/assets/editor_gender_FunkIriberriVenus.pdf) (submitted)  
with [Patricia Funk](https://sites.google.com/site/patriciafelicitasfunk/patricia-funks-research-webpage) and [Nagore Iriberri](https://sites.google.com/site/nagoreiriberri/)  
[Now available as CEPR DP19303](https://cepr.org/publications/dp19303)  
[Show Abstract](#){: .abstract-link data-target="abs2" }

<div id="abs2" class="abstract-modal">
  <div class="abstract-content">
    <button class="close-btn" onclick="closeAbstract('abs2')">&times;</button>
    <p>
      We study the evolution of female representation in editorial roles for 15 top journals in economics from 1960 to 2019. We first document that the share of women in editorial roles has steadily increased over the past six decades. Second, we investigate whether this increase is due to an expansion of the pool of qualified female economists, or due to a change in the preference for appointing women. We find evidence for both using a large database on detailed CVs of more than 37,000 economists. Third, we study the implications of female editors on topic diversity, the quality of accepted papers and potential trickle down effects on female authors' publishing prospects. Finally, to understand whether there are gender gaps in the probability of being offered and/or of accepting editorial positions, we administer a large-scale survey among most prominent scholars in economics. We only find evidence for the offering channel.
    </p>
  </div>
</div>

---

## Work in progress

**The Role of Family Policies in Female Labour Supply and Fertility Decisions**  
[Show Abstract](#){: .abstract-link data-target="abs3" }

<div id="abs3" class="abstract-modal">
  <div class="abstract-content">
    <button class="close-btn" onclick="closeAbstract('abs3')">&times;</button>
    <p>
      This paper investigates the role of family policies—in particular child-related taxes and transfers, along with public childcare provision and subsidization—in fertility and female labour supply decisions. I develop, quantify and solve a life-cycle model with human capital accumulation, featuring heterogeneous households that jointly make fertility and labour supply decisions, conditional on their national family policy environment. The model is calibrated based on tax-transfer functions from the OECD Tax-Benefit model and childcare expenditure data. Using this framework, I first demonstrate that revenue-neutral reallocations from child cash benefits to childcare subsidies can increase both fertility rates and female labour supply, if the elasticity of substitution between maternal and market-provided care is sufficiently high. Second, I assess the extent to which differences in family policies explain the cross-country variation in fertility rates and women's effective hours worked by simulating counterfactual policy environments. An elasticity of substitution of 5 best predicts both fertility and female labour supply across countries, with family policies accounting for 11% of the variation in fertility rates and 5% of the variation in women’s hours worked.
    </p>
  </div>
</div>

---

<!-- Styling -->
<style>
.abstract-link {
  font-size: 0.9rem;
  color: #0366d6;
  cursor: pointer;
}
.abstract-link:hover {
  text-decoration: underline;
}
.abstract-modal {
  display: none;
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background-color: rgba(0,0,0,0.6);
  justify-content: center;
  align-items: center;
  z-index: 9999;
}
.abstract-content {
  background: white;
  color: #222;
  padding: 2em;
  max-width: 700px;
  max-height: 80vh;
  overflow-y: auto;
  border-radius: 10px;
  box-shadow: 0 0 20px rgba(0,0,0,0.4);
  font-size: 0.95rem;
  line-height: 1.5;
}
.close-btn {
  position: absolute;
  top: 8px; right: 12px;
  background: none;
  border: none;
  font-size: 1.5rem;
  color: #444;
  cursor: pointer;
}
</style>

<!-- Script -->
<script>
function openAbstract(id) {
  document.getElementById(id).style.display = "flex";
}
function closeAbstract(id) {
  document.getElementById(id).style.display = "none";
}
document.addEventListener("click", function(e) {
  if (e.target.classList.contains("abstract-modal")) {
    e.target.style.display = "none";
  }
});
document.querySelectorAll(".abstract-link").forEach(link => {
  link.addEventListener("click", e => {
    e.preventDefault();
    const target = link.getAttribute("data-target");
    openAbstract(target);
  });
});
</script>
