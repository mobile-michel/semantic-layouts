---
title: Semantic Layouts
description: 6 differents versions of semantic layouts.
layout: base
---
{% for item in collections.layouts %}
- [{{item.data.title}}]({{item.url}})
{% endfor %}