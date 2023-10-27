---
created: 2023-07-07 11:29
banner: "![[home-1.jpg]]"
banner_y: 0.32
banner_locked: true
---
![[numenera-logo.png]]
They say there have been eight worlds before ours. Eight times the people of this Earth, over vast millennia, built their civilizations, reaching heights we cannot even fully imagine now. They spoke to the stars, reshaped the creatures of the world, and mastered form and essence. They built cities and machines that have since crumbled to dust, leaving only their barest remnants.

This is the Ninth World. The people of the prior worlds are gone—scattered, disappeared, or transcended. But their works remain, in the places and devices that still contain some germ of their original function. The ignorant call these magic, but the wise know that these are our legacy. They are our future. They are the Numenera.

# Characters
```page-gallery
filter: false
orientation: square
columns: 3
fields:
- file.name
views:
- name: Characters
  from: '-"_templates"'
  where: 'contains(file.tags, "character") and !contains(file.tags, "archived")'
```

# Scenes
```page-gallery
filter: false
orientation: square
columns: 3
fields:
- file.name
views:
- name: Characters
  from: '-"_templates"'
  where: 'contains(file.tags, "scene") and !contains(file.tags, "archived")'
```
```button
name Create new scene
type command
action Quickadd: New Scene
```
^button-new-scene

# Characters
```button
name Create new character
type command
action Quickadd: New Character
```
^button-new-character
```dataview
List 
From -"_templates"
Where contains(file.tags, "character")
Sort file.name
```

# Maps
```button
name Create new map
type command
action Quickadd: New Map
```
^button-new-map
```dataview
List 
From -"_templates"
Where contains(file.tags, "map")
Sort file.name
```

# Creatures
```button
name Create new creature
type command
action Quickadd: New Creature
```
^button-new-creature
```dataview
List
From -"_templates"
Where contains(file.tags, "creature") 
Sort file.name
```

# Setting
```button
name Create new setting detail
type command
action Quickadd: New Setting
```
^button-new-setting
```dataview
List 
From -"_templates"
Where contains(file.tags, "setting")
Sort file.name
```

# Places
```button
name Create new place
type command
action Quickadd: New Place
```
^button-new-place
```dataview
List 
From -"_templates"
Where contains(file.tags, "place")
Sort file.name
```

# Mechanics
```dataview
List
From -"_templates"
Where contains(file.tags, "mechanics") 
Sort file.name
```