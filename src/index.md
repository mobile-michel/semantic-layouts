---
title: Semantic Layouts
description: 6 differents versions of semantic layouts.
layout: base
---
{% for item in collections.layouts %}
- [{{item.data.title}}]({{item.url}})
{% endfor %}

## Repos

- **version 6**: nouvelle version pour tester. Intégré à semantic-layouts.
- version 5 **semantic-layouts** [GitHub](https://github.com/mobile-michel/semantic-layouts) - [Netlify](https://semantic-layouts.netlify.app/): version utilisée pour rassembler toutes les autres versions.
- version 4 **basic-layout2** [GitHub](https://github.com/mobile-michel/basic-layout2) - [Netlify](https://basic-layout2.netlify.app/): squelette utilisant Tailwind. Intégré à semantic-layouts.
- version 3 **layouts-with-background-image** [GitHub](https://github.com/mobile-michel/layouts-with-background-image) - [Netlify](https://layouts-with-background-image.netlify.app/)
- version 2 **tailwind-templates-v1** [GitHub](https://github.com/mobile-michel/tailwind-templates-v1) - [Netlify](https://tailwind-templates-v1.netlify.app/)
- version 1 **tailwind-layouts-v1** [GitHub](https://github.com/mobile-michel/tailwind-layout-v1) - [Netlify](https://tailwind-layout-v1.netlify.app/): zones en niveaux de gris. Intégré à semantic-layouts.