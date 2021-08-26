---
layout: page
title: Class Schedule
description: Listing of course modules and topics.
---

# {{ page.title }}

*All readings and modules are **preliminary** and subject to change without notice before the semester starts on 8/26.
Once the semester starts, the class will be advised of any changes using Canvas.*

{% for module in site.modules %}
{{ module }}
{% endfor %}
