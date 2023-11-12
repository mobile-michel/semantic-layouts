---
title: Semantic Layouts
description: 6 differents versions of semantic layouts.
layout: base
---
{% for item in repos.items %}
- [{{item.name}}]({{item.url}}): {{item.description}} - old name: {{item.old-name}} - [GitHub]({{item.github}}) - [Netlify]({{item.netlify}}) ![screenshot](/assets/images/{{item.screenshot}})
{% endfor %}