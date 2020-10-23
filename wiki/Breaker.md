---
title: "Breaker"
reg_id: "breaker"
description: "The Breaker breaks blocks in the direction it faces"
---

<!-- Obtaining -->
<!-- Breaking -->
{% include text/obtaining/breaking/barrel.md %}

### Crafting
{% include recipe.html ingredients="4 Vulcaanium Crystals, 7 Red Nether Bricks, 1 Lava Bucket, and 1 Iron Bar" %}

## Usage
### Machine
When powered, the Breaker will break blocks directly in front of its front face.
{% include fig.html src="/assets/docs/breaker/demo.png" border=true %}
#### Ascension
Ascension of the {{ page.title }} increases the distance broken by 1 per level.
- *See [Machine § Ascension](Machine#ascension)*
  
#### Mysteriosity
The {{ page.title }} does not have Mysterious functionality.
- *See [Machine § Mysteriosity](Machine#mysteriosity)*

### Tempite Component
- *See [{{ page.title }} § Machine ](#machine)*

{{ page.title }}s can be powered from the back by [Tempite Wire](Tempite_Wire).
{% include data_table/machine_cost.html block_name=page.title block_texture_path="block/breaker_front" cost_base=20 cost_ascension=4 cost_reduction=3 %}

### Breaking
{% include data_table/obtaining/breaking/barrel.html block_name=page.title block_texture_path="block/breaker_front" %}

<!-- Data Values -->
<!-- ID -->
{% include data_table/data_values.html block_name=page.title block_id=page.reg_id block_texture_path="block/breaker_front" %}
