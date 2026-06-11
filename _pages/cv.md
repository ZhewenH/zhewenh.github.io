---
layout: page
permalink: /cv/
title: CV
nav: false
nav_order: 5
description: Curriculum vitae document.
---

{% assign cv_pdf = site.data.home.profile.cv_pdf | default: '/assets/pdf/example_pdf.pdf' %}

<p>
  <a href="{{ cv_pdf | relative_url }}">Open CV PDF</a>
</p>

<iframe
  src="{{ cv_pdf | relative_url }}"
  title="CV PDF"
  style="width: 100%; min-height: 82vh; border: 1px solid #d9e0e8; border-radius: 8px;"
></iframe>
