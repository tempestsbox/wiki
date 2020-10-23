---
title: "Alchemy Chamber"
reg_id: "alchemy_chamber"
description: "The Alchemy Chamber enchances the quality of blocks in front of it"
---

<!-- Obtaining -->
<!-- Breaking -->
{% include text/obtaining/breaking/barrel.md %}

### Crafting
{% include recipe.html ingredients="7 Iron Ingots, 1 Cobblestone, and 1 Blaze Rod" %}

## Usage
### Machine
When powered, the  {{ page.title }} will convert blocks into higher tier versions of themselves. Conversions are as follows:
- Iron Ore → Iron Block
- Gold Ore → Gold Block
- Cobblestone → Magma
- Netherrack → Magma
- Magma Block → Obsidian
- Prismarine → Sea Lantern
- Sandstone → Quartz Block
- Any Log → Coal Block
- Soul Sand → Glowstone
- Any Damaged Anvil → Anvil

{% include fig.html src="/assets/docs/alchemy_chamber/showcase_angled.gif" caption="6 Alchemy Chambers, each one level of ascension higher than the last" %}
#### Ascension
Ascension of the {{ page.title }} increases the distance of blocks affected by 1 per level.
- *See [Machine § Ascension](Machine#ascension)*

#### Mysteriosity
The {{ page.title }} does not have Mysterious functionality.
- *See [Machine § Mysteriosity](Machine#mysteriosity)*

### Tempite Component
{{ page.title }}s can be powered from the back by [Tempite Wire](Tempite_Wire).
- *See [{{ page.title }} § Machine ](#machine)*
{% include data_table/machine_cost.html block_name=page.title block_texture_path="block/alchemy_chamber_front" cost_base=40 cost_ascension=8 cost_reduction=6 %}

### Breaking
{% include data_table/obtaining/breaking/barrel.html block_name=page.title block_texture_path="block/alchemy_chamber_front" %}

<!-- Data Values -->
<!-- ID -->
{% include data_table/data_values.html block_name=page.title block_id=page.reg_id block_texture_path="block/alchemy_chamber_front" %}
