---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Research
---


## External links

- [HAL][hal]
- [ORCID][orcid]
- [arXiv][arxiv]
- [Research Gate][researchgate]
- [zbMATH][zbmath]

[hal]: https://hal.science/search/index/?q=*&authIdPerson_i=736625
[orcid]: https://orcid.org/0000-0001-5729-5995
[arxiv]: https://arxiv.org/a/garenaux_l_1.html
[researchgate]: https://www.researchgate.net/profile/Louis-Garenaux-2
[zbmath]: https://zbmath.org/?ml=3&ml-1-f=any&ml-1-v=&ml-1-op=and&ml-2-f=au&ml-2-v=Garenaux&ml-2-op=and&ml-3-f=ti&ml-3-v=&dt=j&dt=a&dt=b&dt=p


## Research texts

### Preprints

{%- if site.path.preprints -%}
  {% include_relative {{ site.path.preprints }} %}
{%- endif -%}

### Published articles

{%- if site.path.publications -%}
  {% include_relative {{ site.path.publications }} %}
{%- endif -%}

### Unpublished notes

{%- if site.path.notes -%}
  {% include_relative {{ site.path.notes }} %}
{%- endif -%}

### Memoir

{%- if site.path.memoirs -%}
  {% include_relative {{ site.path.memoirs }} %}
{%- endif -%}

