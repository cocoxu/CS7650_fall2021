---
layout: page
title: Schedule
description: The weekly event schedule.
---

A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1FXwMmHpuWTy0U8p1RvrxdJMoafCaf80L21N-3Naez0Y/edit?usp=sharing).


# Weekly Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
