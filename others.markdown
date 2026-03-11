---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Others
---


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

