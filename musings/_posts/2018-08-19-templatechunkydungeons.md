---
title: "TemplateChunkyDungeons.py"
date: 2018-08-19
---

[TemplateChunkyDungeons.py (GitHub)](https://github.com/nmmarzano/TemplateChunkyDungeons.py)

Another implementation of a procedural dungeon generation scheme... This is sure taking more time, but it offers a ton more control over the final results.

The idea is to generate a grid of smaller dungeon chunks, select a start and end positions that must always be connected, and then build the dungeon from pre-made chunk templates based on how they're connected, with some space for customization and randomization.
