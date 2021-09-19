---
layout: term
title:  Uncertain items
image: /assets/terms/uncertain.jpeg
description: Items refered to as beeing **uncertain** are those that is part of a forecast and that the stakeholders can not **[expect](terms/expected.html)** to be completed accordingly.
date:   2021-06-23 22:45
categories: term
---
![uncertain](../assets/terms/uncertain.jpeg)

Items referred to as beeing **uncertain** are those that is part of a forecast and that the stakeholders can not expect to be completed accordingly.

In contradiction to **[expected](expected.html)** items, uncertain items are connected to a risk. It is that risk that makes the plan uncertain.

<div class="mermaid">
  graph TD;
  A(forecast)
  B(expected items)
  C(uncertain items)
  A -- contains --> B & C
  style C fill:#dd9dae,stroke:#333,stroke-width:4px
  click B "{{ '/terms/expected.html' | relative_url }}"
</div>

