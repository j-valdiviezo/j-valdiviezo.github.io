---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


<p>This browser does not support PDFs. Please download the PDF to view it: <a href="/files/CV_JesusValdiviezo.pdf">Download PDF</a>.</p>

fdsfdsf
