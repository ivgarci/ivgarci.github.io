---
title: "Publications"
permalink: /publications/
author_profile: true
---

This page distinguishes **peer-reviewed publications** from **unpublished research manuscripts**. The published bibliography is based on my FECYT CVN (13 November 2026); DOI links lead to publishers or persistent records.

## Journal articles

{% assign journals = site.publications | where: "category", "journals" | sort: "date" | reverse %}
{% for paper in journals %}
### {{ paper.title }}

**{{ paper.authors }}**  
*{{ paper.venue }}* ({{ paper.year }}).  
[DOI: {{ paper.doi }}](https://doi.org/{{ paper.doi }})

{{ paper.excerpt }}

{% endfor %}

## Book chapters

{% assign chapters = site.publications | where: "category", "chapters" | sort: "date" | reverse %}
{% for paper in chapters %}
### {{ paper.title }}

**{{ paper.authors }}**  
*{{ paper.venue }}* ({{ paper.year }}).  
[DOI: {{ paper.doi }}](https://doi.org/{{ paper.doi }})

{{ paper.excerpt }}

{% endfor %}

## Doctoral thesis

*Generación y validación de redes QKD a gran escala bajo restricciones físicas y tecnológicas*. **Universidad de Salamanca**, 2026. Supervisor: Ángel M. Martín del Rey. Distinction: *Sobresaliente cum laude*.

## Unpublished manuscripts and ongoing research

The following are **not presented as published or accepted articles**:

- **Post-design structural validation of geographically realistic QKD networks** — ongoing manuscript on network connectivity, robustness and post-design checks.
- **From Optoelectronic Parameters to Network-Level Performance: A Global Sensitivity Analysis of Geographically Realistic Quantum Key Distribution Networks** — manuscript in preparation.
- **SKR-aware QKD routing and service resilience** — ongoing research.

## Academic identifiers

[ORCID](https://orcid.org/0000-0002-9472-5613) · **Scopus Author ID:** 57219474099 · **ResearcherID:** AAO-1736-2021

For the most up-to-date bibliographic record, see my [ORCID profile](https://orcid.org/0000-0002-9472-5613).
