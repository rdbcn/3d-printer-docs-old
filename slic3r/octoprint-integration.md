---
layout: default
title: OctoPrint Integration
parent: Slic3r
nav_order: 4
---

# OctoPrint integration

Integrating slic3r with octoprint enables the Send to printer button to send gcode files directly to OctoPrint for printing.

1. Open OctoPrint
1. Copy the API key under **Settings > API Key**
2. In Slic3r, select the **Printer Settings** tab
3. Select the **OCTOPRINT** profile

    ![OctoPrint profile]({{ site.baseurl }}/images/slic3r-octoprintprofile.png)

    {% include info.html content="
If the Octoprint profile doesn't exist (new Slic3r installation) select the <strong>Original Prusa i3 MK2</strong> profile. This will edit the stock profile with OctoPrint settings." %}
4. Enter the hostname `j3d-prusa.vsb.bc.ca` under **Host or IP**
5. Enter the API key copied earlier
6. Click the ![Save icon]({{ site.baseurl }}/images/slic3r-saveicon.png)
7. If the OCTOPRINT profile didin't previously exist, append `octoprint` to the profile name. Otherwise, skip this step. 
8. Click **OK**