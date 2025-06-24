# Welcome to my Web Mapping Portfolio!
Hi, I'm Charles.
This is a very basic first page for my website, which I will be building as part of the GIS course.
Here are a few things I might include later:
* Links to my web mapping projects
* Information about my skills and experience
* A way to contact me
**Stay tuned for updates!**


---
layout: default
title: ArcGIS Embedded Map
---

<!-- Load the ArcGIS embeddable components -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script>

<!-- Display the embedded ArcGIS map -->
<arcgis-embedded-map
  style="height:600px;width:700px;"
  item-id="abdeba1fb1ff4e56b5e72c1cb1cbc062"
  theme="dark"
  heading-enabled
  legend-enabled
  portal-url="https://sdsugeo.maps.arcgis.com">
</arcgis-embedded-map>


---
layout: default
title: Embedded Map
---

<!-- ArcGIS Script to load embeddable components -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script>

<!-- ArcGIS Embedded Map Component -->
<arcgis-embedded-map
  style="height:600px; width:700px;"
  item-id="abdeba1fb1ff4e56b5e72c1cb1cbc062"
  theme="dark"
  heading-enabled
  legend-enabled
  portal-url="https://sdsugeo.maps.arcgis.com">
</arcgis-embedded-map>

