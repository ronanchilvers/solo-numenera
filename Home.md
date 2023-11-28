---
created: 2023-07-07 11:29
banner: "![[home-2.jpg]]"
banner_y: 0.46667
banner_lock: true
---
![[numenera-logo-goldfoil.png]]
They say there have been eight worlds before ours. Eight times the people of this Earth, over vast millennia, built their civilizations, reaching heights we cannot even fully imagine now. They spoke to the stars, reshaped the creatures of the world, and mastered form and essence. They built cities and machines that have since crumbled to dust, leaving only their barest remnants.

This is the Ninth World. The people of the prior worlds are gone - scattered, disappeared, or transcended. But their works remain, in the places and devices that still contain some germ of their original function. The ignorant call these magic, but the wise know that these are our legacy. They are our future. They are the Numenera.

`button-new-scene`

```page-gallery
filter: false
orientation: square 
columns: 3
fields:
- file.name
views:

- name: Scenes
  from: '-"_templates"'
  where: 'contains(file.tags, "scene") and !contains(file.tags, "archived")'

- name: Characters
  from: '"Game/Characters"'
  where: 'contains(file.tags, "character") and !contains(file.tags, "archived")'

- name: NPCs
  from: '-"_templates"'
  where: 'contains(file.tags, "npc") and !contains(file.tags, "archived")'

- name: Places
  from: '-"_templates"'
  where: 'contains(file.tags, "place") and !contains(file.tags, "archived")'

- name: Setting Details
  from: '-"_templates"'
  where: 'contains(file.tags, "setting") and !contains(file.tags, "archived")'

- name: Creatures
  from: '-"_templates"'
  where: 'contains(file.tags, "creature") and !contains(file.tags, "archived")'

- name: Maps
  from: '-"_templates"'
  where: 'contains(file.tags, "map") and !contains(file.tags, "archived")'
```

# Mechanics
```dataview
List
From -"_templates"
Where contains(file.tags, "mechanics") 
Sort file.name
```