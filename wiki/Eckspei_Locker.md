---
title: "Eckspei Locker"
reg_id: "eckspei_locker"
widget_description: "The Eckspei Locker absorbs experience orbs in the direction it faces, and is used to manage Eckspei Rods"
---

The {{ page.title }} absorbs {% include mcwiki.html url="Experience_Orb" title="experience orbs" %} in the direction it faces, and is used to manage [Eckspei Rods](Eckspei_Rod).

<!-- Obtaining -->
<!-- Breaking -->
{% include text/obtaining/breaking/barrel.md %}

### Crafting
{% include recipe.html ingredients="6 Iron Ingots, 1 Glass Pane, 1 Glass Bottle, and 1 Observer" %}

## Usage
### Machine
When powered, the {{ page.title }} absorbs {% include mcwiki.html url="Experience_Orb" title="experience orbs" %} in a 3x1x2 range in front of itself.
{% include fig.html src="/assets/docs/eckspei_locker/demo.png" border=true %}
#### Ascension
Ascension of the {{ page.title }} increases the range of absorption forwards by 1 per level.
- *See [Machine § Ascension](Machine#ascension)*

#### Mysteriosity
The {{ page.title }} does not have Mysterious functionality.
- *See [Machine § Mysteriosity](Machine#mysteriosity)*

### Tempite Component
- *See [{{ page.title }} § Machine ](#machine)*

{{ page.title }}s can be powered from the back by [Tempite Wire](Tempite_Wire).
{% include data_table/machine_cost.html block_name=page.title block_texture_path="block/eckspei_locker_front" cost_base=10 cost_ascension=2 cost_reduction=1 %}
### Eckspei Rod
If an [Eckspei Rod](Eckspei_Rod) is placed in the first crystal-slot of an {{ page.title }}, the [Eckspei Rod](Eckspei_Rod) will gain 1 durability per tick - 20 durability per second.

- [*See demonstration* (`1:36`)](https://youtu.be/dpjh2LFJU0E)

### Breaking
{% include data_table/obtaining/breaking/barrel.html block_name=page.title block_texture_path="block/eckspei_locker_front" %}

<!-- Data Values -->
<!-- ID -->
{% include data_table/data_values.html block_name=page.title block_id=page.reg_id block_texture_path="block/eckspei_locker_front" %}

## Gallery
{% include fig.html src="/assets/docs/eckspei_locker/display.png" caption="Eckspei Locker action bar experience display" %}
