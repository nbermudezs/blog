---
layout: default-cv
title: "About"
permalink: /cv/
---

{% include career-profile.html %}

{% if site.education_in_main %}
    {% include education.html %}
{% endif %}

{% include experience.html %}

{% include publications.html %}

{% include skills.html %}

{% include awards.html %}
