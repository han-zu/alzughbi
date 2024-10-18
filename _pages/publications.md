---
layout: single
title: "Publications & Reports"
permalink: /publications/
author_profile: true
---
<hr style="border: 1px solid;">

{% assign sorted_publications = site.publications | sort: 'year' | reverse %}

{% for pub in sorted_publications %}

## [{{ pub.title }}]({{ pub.url }})

**Authors:** {{ pub.authors }}  

{% if pub.booktitle %}
**{{ pub.booktitle }}{% if pub.institution %}, {{ pub.institution }}{% endif %}{% if pub.year %}, {{ pub.year }}{% endif %}**  
{% endif %}

<hr> 

{% endfor %}
