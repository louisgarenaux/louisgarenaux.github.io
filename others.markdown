---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Others
---


### Open problems

Please let me know if you are aware of partial or complete resolutions of these.

- *Connection between SDE and PDE.* The Feynman-Kac formula links Brownian processes to heat equation. Can this link be extended to other PDEs? For example, does there exists a random process whose expectation solves the linear Korteweg-de Vries equation? Personal guess: look for a process with non-zero cubic variation.
- *Spectral measure for differential operator with non-constant coefficients.* Heteroclinic waves are associated to a two dimensional continuous spectrum. Can a spectral measure be associated to it? Explicit computation is known for constant coefficients using Fourier transform.


### Tools

- Text comparison software [Meld][meld]. 
- Time-schedule LaTeX [package][time-schedule].
- Regular expressions [tutorial][regexp] for search and replace.


### Internship reports

{%- if site.path.internships -%}
  {% include {{ site.path.internships }} %}
{%- endif -%}


[meld]: https://meldmerge.org/
[time-schedule]: assets/time-schedule.zip
[regexp]: https://regexone.com/
[url-assertion]: https://framaforms.org/what-do-you-think-of-this-assertion-1769675854

