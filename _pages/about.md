---
permalink: /
title: "Welcome to my website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor of Financial Economics at the **Halle Institute for Economic Research (IWH)** and **Martin Luther University Halle-Wittenberg**.

## Research Group and Interests

At the institute, I head the research group **Data Science in Financial Economics**, where we focus on developing and applying novel data science and AI methods in the field of financial economics. These methods are used to generate economic indicators from unstructured data, such as textual data, satellite imagery, or web scraping. These indicators are then utilized in econometric analysis to address pertinent questions in financial economics.

Current projects of the group deploy such indicators to study, for instance:
* Information frictions in financial markets, such as asymmetric information, market efficiency and the quality of firm disclosures and governance.
* Bank lending behavior and risk-shifting in real estate markets as a response to macroprudential regulation.
* Markets’ adaptation to climate change and the limits thereof.

The research group also develops and maintains IWH’s **European Real Estate Index (EREI)**, which systematically tracks European real estate markets. EREI provides data on quoted prices, supply-side depth (number of listings), and liquidity (dwell time). Harmonized at the NUTS-3 regional level, the index supports consistent cross-country comparisons and spatial analyses for researchers, policymakers, and the public.

## Publications

### Peer-Reviewed Publications

<ul>{% assign peer_reviewed = site.publications | where: "publication_type", "peer_reviewed" | sort: "date" | reverse %}{% for post in peer_reviewed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

### Working Papers

<ul>{% assign working_papers = site.publications | where: "publication_type", "working_paper" | sort: "date" | reverse %}{% for post in working_papers %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
