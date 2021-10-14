---
description: How to manually edit blockstates json files
---

# Manual editing blockstates

## Edit note_block.json

{% hint style="warning" %}
Update to ItemsAdder 2.4.20
{% endhint %}

You can manually edit the file `assets\minecraft\blockstates\note_block.json` adding your own rules inside.

**ItemsAdder **will automatically merge your custom json file with the **ItemsAdder **custom blocks if you created any.

## Editing other .json blockstates

You can edit any blockstate file you want, but you have to read this in order to edit some of them.

In order to edit the some blockstates files you have to disable the ItemsAdder custom blocks feature based on the type you want to edit. In the future I may allow manual editing of these files without disabling the ItemsAdder blocks feature (it's not easy to implement, that's why I didn't make this possible yet).

### mushroom blockstates

Enable this option:

{% code title="config.yml" %}
```yaml
  disable-REAL: true
```
{% endcode %}

### fire.json

Enable this option:

{% code title="config.yml" %}
```yaml
  disable-FIRE: true
```
{% endcode %}

### chorus_plant.json

Enable this option:

{% code title="config.yml" %}
```yaml
  disable-REAL_TRANSPARENT: true
```
{% endcode %}

### tripwire.json

Enable this option:

{% code title="config.yml" %}
```yaml
  disable-REAL_WIRE: true
```
{% endcode %}