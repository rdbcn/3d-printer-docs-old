---
layout: default
title: Step-by-step Guide
parent: Prusa
nav_order: 2
---

# Step-by-step 3D printing
This section will take you through the complete process of downloading an object to 3D printing it.
1. Download or export the object that you want to print in STL format.
2. Open Slic3r
3. Drag the STL file into the main area.
4. Orient your object by right clicking on it and using the rotate options
5. Select the desired level of detail (layer height)
6. Select the type of filament to be printed on

    For ABS: Prusa ABS 1.75mm

    For PLA: Prusa PLA 1.75mm

    ![Slic3r Print Settings]({{ site.baseurl }}/images/silc3r-printsettings.png)
7. Optionally enable a brim or supports. Refer to relevant sections:
8. Click send to printer
9. Open OctoPrint
10. Find the gcode file in the **Files** window

    ![OctoPrint files]({{ site.baseurl }}/images/octoprint-files.png)

    {% include info.html content="The gcode file name is based on the STL file name." %}
11. Ensure that the bed of the printer is clear and ready for printing.
12. Ensure that the coorect type of filament and a sufficient ammount to complete the print is loaded.
13. Click Print