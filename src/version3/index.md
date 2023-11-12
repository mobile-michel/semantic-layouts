---
title: Version 3
layout: base
date: 2023-11-03
tags:
  - layouts
  - version3
---

## Layouts

{% for nav in collections.version3 %}
    - [{{ nav.data.title }}]({{ nav.url }})
{% endfor %}

## width

* w-auto (auto, remove an element's assignement)
* w-1/2 (50%)
* w-full (100%)
* w-screen (100vw)
* w-min (min-content)
* w-max (max-content)
* w-fit (fit-content)
* w-[32rem] (arbitrary value)

## min-width

* min-w-full (100%)
* min-w-min (min-content)
* min-w-max (max-content)
* min-w-fit (fit-content)

## max-width

* max-w-full (100%)
* max-w-min (min-content)
* max-w-max (max-content)
* max-w-fit (fit-content)
* max-w-prose (65ch)
* max-w-screen-sm (640px)...

## height

* h-auto (auto, remove an element's assignement)
* h-1/2 (50%)
* h-full (100%)
* h-screen (100vh)
* h-min (min-content)
* h-max (max-content)
* h-fit (fit-content)
* h-[32rem] (arbitrary value)