---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
description: "Publications by Guy Khazma on key-value stores, storage engines, distributed systems and big data analytics."
---

You can also find my articles on [Google Scholar]({{ site.author.googlescholar }}).

<ul class="pubs">
{% assign pubs = site.publications | sort: "date" | reverse %}{% for pub in pubs %}{% include publication.html %}{% endfor %}
</ul>
