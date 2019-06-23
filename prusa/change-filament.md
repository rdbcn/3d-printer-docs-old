---
layout: default
title: Change the filament
parent: Prusa
nav_order: 2
---

# Change the filament
1. Home the hotend
2. Centre the hotend
3. Heat the hotend to the coorect temperature for the filament
4. Unload the old filament:
    1. Using OctoPrint
        1. Under the **Control** tab, ether the length in mm to retract
        2. Click retract
    2. Using the printer firmware:
        1. Click the wheel
        2. Select unload filament
        3. Click the wheel
5. Load the new filament:
    1. Using OctoPrint
        1. Under the **Control** tab, enter the length in mm to extrude.
            {% include tip.html content="100mm-120mm is usually sufficient" %}
        2. Click extrude
            {% include tip.html content="If the colour is not clear, keep extruding by small amounts until the colour is clear" %}
    2. Using the printer firmware:
        1. Click the wheel
        2. Select Load Filament
        3. Follow the instructions
6. Done
