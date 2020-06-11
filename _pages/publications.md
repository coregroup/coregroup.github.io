---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Recent Publications (selected and in English only)

## 2019

## 2012
<li><a href="#"><i class="ai ai-orcid-square ai-fw"></i> ORCID</a></li>
Costa E., Silva P., Silva M., Silva E., Santos A. (2012) A Multiagent-Based ITS Using Multiple Viewpoints for Propositional Logic. In: Cerri S.A., Clancey W.J., Papadourakis G., Panourgia K. (eds) Intelligent Tutoring Systems. ITS 2012. Lecture Notes in Computer Science, vol 7315. Springer, Berlin, Heidelberg.

{% include base_path %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
