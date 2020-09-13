---
---

## Tempite Stone
------------


<!-- Obtaining -->
<!-- Breaking -->
{%- comment -%}{% include text/obtaining/breaking/barrel.md %}{%- endcomment -%}
### Tempite Insulator
When a [Tempite Insulator](/wiki/Tempite_Insulator) is placed on a Tempite Stone, it will hiss three times before breaking with a small explosion, dropping itself and the Tempite Stone.
### Crafting
![tempite_stone/recipe.png](/assets/docs/tempite_stone/recipe.png)

## Usage
### Tempite component
Using a Hopper, you can feed a Tempite Stone [Amethyst](/wiki/Amethyst). For every 1 [Amethyst](/wiki/Amethyst), 1000 [Tempite](/wiki/Tempite) is added to the Tempite Stone. The maximum amount of Tempite that can be in a Tempite Stone is `64000`.
### Redstone component
When a Tempite Stone is activated, any adjacent glass blocks will be powered with [Tempite](/wiki/Tempite), sending out a wire-like charge. If this charge hits a machine's back, the machine will be powered.
{%- comment -%}{% include fig.html src="/assets/docs/tempite_wire/showcase.gif" %}{%- endcomment -%}
### Breaking
When broken in any way, the Tempite Stone will drop its Tempite in the form of Amethyst, at a ratio of `1000:1`. This is rounded down by Minecraft, so if there's `999` Tempite, it will drop no Amethyst.

<!-- Data Values -->
<!-- ID -->
{%- comment -%}{% include data_table/data_values.html block_name=page.title block_id=page.reg_id block_texture_path="block/tempite_stone" %}{%- endcomment -%}

## Gallery
{%- comment -%}{% include fig.html src="/assets/docs/tempite_stone/semi_powered.gif" caption="A Tempite Stone getting powered without any Tempite<br>(semi-powered)" %}{%- endcomment -%}
<br>
{%- comment -%}{% include fig.html src="/assets/docs/tempite_stone/display.png" caption="Tempite Stone action bar Tempite display" %}{%- endcomment -%}

