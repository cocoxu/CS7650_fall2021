---
layout: home
title: CS 7650
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

Georgia Institute of Technology

- Instructor: [Wei Xu](https://cocoxu.github.io) 
- [Piazza](https://piazza.com/class/ksjq7xenrbp3g5) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/292811) (homework assignments, submission and grading)

{% for module in site.modules %}
{{ module }}
{% endfor %}
