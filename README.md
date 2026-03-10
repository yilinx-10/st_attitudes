# Science and Technology Attitudes as a Product of Competing Epistemic Authorities

## Motivation
Scientific and technological progress increasingly shapes everyday life, from public health and energy policy to information access and social media interactions. Yet public attitudes toward science are far from uniform: some individuals embrace scientific advances enthusiastically, while others remain skeptical, cautious, or even hostile. These differences cannot be explained solely by variation in knowledge or scientific literacy. Rather, they reflect competing interpretations, social norms, and moral frameworks through which individuals evaluate the role of science in society. Understanding these attitudes is therefore critical, as they influence compliance with public health recommendations, support for evidence-based policy, and the social legitimacy of scientific institutions.

Importantly, attitudes toward science and technology are not simply preferences for scientific knowledge over other forms of understanding. Instead, they capture broader evaluations of the social consequences, moral implications, and practical relevance of scientific and technological change. Individuals may value scientific knowledge while simultaneously expressing concern that scientific advances undermine moral authority, conflict with religious beliefs, or challenge established social norms. As research in science and technology studies emphasizes, scientific knowledge and social order are often co-produced, meaning that debates about science frequently reflect broader struggles over values, authority, and institutional legitimacy (Jasanoff, 2004). Public engagement with science and technology is therefore deeply embedded in social, moral, and institutional contexts that shape whether science is trusted, valued, or questioned.

Science and technology attitudes have also become increasingly politicized, particularly in domains with high societal stakes or moral implications. Examples include compliance with COVID-19 public health measures, beliefs about climate change and energy policy, and public responses to social media algorithms, echo chambers, and filter bubbles.

Motivated by the significance and complexity of these dynamics, this study asks the following research question: How do spirituality, institutional trust, and traditional social norms shape individual attitudes toward science and technology, and how does cross-national variation in institutional trust condition these relationships?

## Research Question

I propose the following research question to guide my examination of individual- and country-level variation in attitudes toward science and technology: How do moral norms and scientific institutions influence individual and collective attitudes toward science and technology across countries?

## Research Design
See [Theoretical Framework](theoretical_framework.md).

**Data Source:**

* Wave 7 of the **World Values Survey (WVS, 2017–2019)**.
* Individual-level responses on moral values, trust in institutions, and attitudes toward science and technology across **55 countries**.

**Analytical Strategy:**

* **Level 1 (Individual Positioning):**

  * Multilevel models with **random slopes by country** to capture how individual morality and institutional trust shape science attitudes.
  * Train-test split used to avoid overfitting and adjust for multiple testing.

* **Level 2A (Cultural Dominance):**

  * Country-level averages (means) of morality and trust predict **collective science attitudes**.
  * Explores which epistemic authorities are culturally dominant.

* **Level 2B (Conflict Intensity):**

  * Country-level dispersions (standard deviations) of morality and trust predict **polarization in science attitudes**.
  * Identifies contested domains driving societal disagreement.

**Variables:**

* **Moral domains:** Purity, civic, and violence morality.
* **Institutional trust:** Trust in universities (primary), with potential extension to other institutions.
* **Outcomes:** Individual science attitudes (Level 1), country mean attitudes (Level 2A), and country-level polarization (Level 2B).

**Key Features:**

* Combines **cross-sectional multilevel modeling** with **country-level aggregation**.
* Explicitly distinguishes effects on **overall attitudes** versus **polarization**.
* Supports cross-level inference while accounting for **heterogeneity in moral and institutional domains**.

## Key Insights: Cross-Level Dynamics of Moral and Institutional Effects on Science Attitudes

### 1. Polarization Drivers (Purity Morality & Trust in Universities)

* **Pattern:** Strong individual-level effects, weak country-level means, strong within-country dispersion.
* **Interpretation:** Purity and trust create the main fault lines in epistemic authority. High disagreement (dispersion) drives polarization; low disagreement allows consensus.
* **Takeaway:** Dispersion is a novel indicator of active cultural conflict over science. Country averages alone are insufficient to understand disagreement.

### 2. Progressive Alignment (Violence Morality)

* **Pattern:** Positive effects at both individual and country levels; minimal effect of dispersion.
* **Interpretation:** Anti-violence morality aligns individuals and societies with science, reflecting broader cultural modernization rather than conflict.
* **Takeaway:** Violence morality reinforces consensus and progressive cultural alignment without generating polarization.

### 3. Context-Dependent Meaning (Civic Morality)

* **Pattern:** Positive individual-level effects, negative or mixed country-level means, no clear dispersion effect.
* **Interpretation:** Civic morality supports science at the individual level but can correlate with lower collective acceptance at the country level.
* **Takeaway:** This cross-level reversal illustrates an ecological fallacy: the meaning and impact of civic norms are context-dependent and do not consistently structure epistemic authority conflicts.

**Overall Conclusion:**
Science attitudes are shaped by three distinct mechanisms: some domains drive polarization (purity, trust), others reinforce progressive consensus (violence), and some are contextually contingent (civic). Understanding these attitudes requires examining both **average effects** and **within-country heterogeneity**.


