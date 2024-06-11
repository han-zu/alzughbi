---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for pub in site.publications %}

## [{{ pub.title }}]({{ pub.url }})

**Authors:** {{ pub.authors }}  

**{{ pub.booktitle }}{{ pub.institution ? ', ' + pub.institution : '' }}{{ pub.year ? ', ' + pub.year : '' }}**  



{{ pub.abstract }}



**Citation:**  

{{ pub.authors }}. **"{{ pub.title }}."** {{ pub.booktitle ? 'In ' + pub.booktitle + '.' : '' }} {{ pub.institution }} {{ pub.year }}. DOI: [{{ pub.doi }}]({{ pub.url }})



{% endfor %}
