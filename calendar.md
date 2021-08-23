---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1FXwMmHpuWTy0U8p1RvrxdJMoafCaf80L21N-3Naez0Y/edit?usp=sharing).


{% for module in site.modules %}
{{ module }}
{% endfor %}
