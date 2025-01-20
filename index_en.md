---
layout: splash
# classes: wide
title: "Surface AI"
header:
  overlay_image: /assets/images/Stockimage.jpg
  overlay_filter: rgba(100, 100, 100, 0.5)
  caption: "Photo: Girts Ragelis/Shutterstock"
excerpt: "Automatic Prediction of Road Surface Type and Quality using Open Data and Machine Learning <br> <br> 
Duration: November 2023 - December 2024"
---

Automatic determination of road surface type and quality is essential for various applications in the transport sector, including route planning. However, there is a scarcity of publicly available datasets on road surface type and quality in a standardized format. Typically, such datasets rely on manual analysis and involve substantial effort. Municipalities, in particular, could benefit from these datasets by using them for effective urban planning. 

# The Project 
The mFund project, SurfaceAI, funded by the German Federal Ministry for Digital and Transport Affairs, aims to address this gap. Open geodata and street images are leveraged to train a machine learning model capable of automatically and precisely categorizing road surfaces and quality in images. The resulting information is converted into georeferenced datasets at street level, which will be made publicly accessible.

# News

**26.02.2025 9am-10am: official final project meeting (online and in German)**. Please request the participation link via surface&#x2011;ai@htw&#x2011;berlin.de 

**29.10.2024:** presentation of our [**short paper**](https://dl.acm.org/doi/10.1145/3681780.3697277) at the [**UrbanAI Workshop of the SIGSPATIAL conference**](https://urbanai.ornl.gov/urbanai2024/)

**22.6.2024 5pm-12am: "Lange Nacht der Wissenschaften" (Long Night of Science)** at the HTW Berlin, Campus Wilhelminenhof, Gebäude C, Raum 604 [program details](https://events.htw-berlin.de/hochschule/lange-nacht-der-wissenschaften/)

**19.6.2024: Presentation (in English) at the "Informatiktag" (computer science day) HTW Berlin** [program details](https://events.htw-berlin.de/karriere/informatiktag/)

**4.6.2024: Publication of the SurfaceAI dataset** [StreetSurfaceVis (doi: 10.5281/zenodo.11449976)](https://zenodo.org/records/11449977)


**20.3.2024: FOSSGIS 2024** [Presentation of the project at the FOSSGIS conference](https://pretalx.com/fossgis2024/talk/MHTEAN/)

**10.1.2024 2pm-3pm: official Project Kickoff (online and in German)**
[Participation via Zoom](https://htw-berlin.zoom-x.de/j/63436322281?pwd=cE5iWm1DbmJ1TzFwdWNmTDNEdW93QT09)

# Releases
- The first version of our [**program code**](https://github.com/SurfaceAI/road_network_classification) with the complete pipeline for enriching entire road networks with road surface and quality information is finished and can be downloaded on Github.

- Paper: Alexandra Kapp, Edith Hoffmann, Esther Weigmann, and Helena Mihaljević. 2024. [**SurfaceAI: Automated creation of cohesive road surface quality datasets based on open street-level imagery.**](https://doi.org/10.1145/3681780.3697277) In Proceedings of the 2nd ACM SIGSPATIAL International Workshop on Advances in Urban-AI (UrbanAI '24). Association for Computing Machinery, New York, NY, USA, 54–57.

- Paper: Alexandra Kapp, Edith Hoffmann, Esther Weigmann, and Helena Mihaljević. 2025. [**StreetSurfaceVis: a dataset of crowdsourced street-level imagery annotated by road surface type and quality.**](https://doi.org/10.1038/s41597-024-04295-9) Sci Data 12, 92 (2025).

- Dataset [**StreetSurfaceVis**](https://zenodo.org/records/11449977) consisting of street-level images from Germany with labels on the type and quality of the road surface

# Possible Applications and Associated Project Partners
The project is supported by various organisations that enable the development of use cases and promote networking within the community. 

These include:
- The route planning and navigation provider [**Komoot**](https://www.komoot.de/),  
- The consulting firm [**Plan4Better**](https://plan4better.de/), which supports local authorities in the development of mobility concepts and has developed the GOAT web tool for accessibility analyses in areas such as walking and cycling,
- The [**CityLAB Berlin**](https://citylab-berlin.org/de/start/) technology foundation, which works at the interface between civil society and administration to promote urban development that is geared towards the common good, and
- The start-up [**FixMyCity**](https://www.fixmycity.de/), which uses digital tools to support cities and local authorities in the transport transition, in particular bicycle traffic planning. 

Two specific application scenarios for the use of the automatically generated road condition data are already being considered. On the one hand, the data can be used directly for route calculation in navigation tools; on the other hand, it can be used for urban planning purposes by analysing and developing efficient and sustainable (bicycle) transport concepts at municipal level.

# Team

{% for member in site.data.team_en %}
  {% include team.html member=member %}
{% endfor %}

# Contact
Please feel free to contact us if you have any questions, suggestions or requests for collaboration: ***surface&#x2011;ai@htw&#x2011;berlin.de***

&nbsp;

---

<!-- <font size="5"> Ein Projekt der </font> -->
A project by

![HTW_Logo](/assets/images/S04_HTW_Berlin_Logo_pos_FARBIG_RGB.jpg){: .align-left width="172px"}
![mFUND_Logo](/assets/images/mFUND_Logo_Mobilitaet_RGB.png){: .align-right width="100px" style="margin-top: 100px; margin-left: 50px"}
<!-- BMDV_Logo height="175px" was ignored -->
![BMDV_Logo](/assets/images/BMDV_Fz_2021_Web_Farbe_de.gif){: .align-right style="height: 175px"}
