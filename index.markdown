---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
list_title: News
---

{%- if site.path.address -%}
  {% include {{  site.path.address  }} %}
{%- endif -%}
      
## Short bio

Louis Garénaux is born in France. He studied mathematics at the [Université de Rennes 1][url-rennes], and obtained a doctoral degree in applied mathematics at the [Institut de Mathématiques de Toulouse][url-toulouse].

His research focuses on the analysis of partial differential equations, with an emphasis on long-time stability of patterns and travelling waves. He worked as a post-doctoral researcher at [Karlsruher Institut für Technologie][url-kit] as a member of the [Collaborative Research Center 1173][url-crc]. During summer 2024, he was visiting the [Leiden Mathematisch Instituut][url-leiden]. 

He is currently working at [INRIA Saclay][url-inria], as a member of the project [Ovopause][url-ovopause] in the team [MUSCA][url-musca].

[url-rennes]: https://www.univ-rennes.fr/
[url-toulouse]: https://www.math.univ-toulouse.fr/en/
[url-kit]: https://www.kit.edu/english/
[url-crc]: https://www.waves.kit.edu/
[url-leiden]: https://www.universiteitleiden.nl/en/science/mathematics
[url-inria]: https://www.inria.fr/en/inria-saclay-centre
[url-musca]: https://team.inria.fr/musca/
[url-ovopause]: https://team.inria.fr/musca/ovopause/
