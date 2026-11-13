---
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journal articles

{% assign journals = site.publications | where: "category", "journals" | sort: "date" | reverse %}
{% for paper in journals %}
**{{ paper.title }}**  
{{ paper.authors }} · *{{ paper.venue }}*, {{ paper.year }}  
[DOI: {{ paper.doi }}](https://doi.org/{{ paper.doi }})

{% endfor %}

## Book chapters

{% assign chapters = site.publications | where: "category", "chapters" | sort: "date" | reverse %}
{% for paper in chapters %}
**{{ paper.title }}**  
{{ paper.authors }} · *{{ paper.venue }}*, {{ paper.year }}  
[DOI: {{ paper.doi }}](https://doi.org/{{ paper.doi }})

{% endfor %}

## Ongoing research

Work in progress includes **structural validation of large-scale QKD networks**, **optoelectronic sensitivity analysis**, and **secret-key-rate-aware routing**. These are not presented as published articles.

[ORCID](https://orcid.org/0000-0002-9472-5613) · Scopus Author ID: 57219474099 · ResearcherID: AAO-1736-2021
