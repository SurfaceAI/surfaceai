---
layout: splash
# classes: wide
title: "Surface AI"
header:
  overlay_image: /assets/images/Stockimage.jpg
  overlay_filter: rgba(100, 100, 100, 0.5)
  caption: "Foto: Girts Ragelis/Shutterstock"
excerpt: "Automatisierte Bestimmung von Straßenbeschaffenheit durch Open Data und Machine Learning <br> <br> 
Laufzeit: November 2023 – Februar 2025"
---

<!-- Laufzeit: November 2023 – Dezember 2024
{: .text-center} -->

Die automatische Bestimmung von Straßenbelag und -qualität ist für diverse Anwendungen im Verkehrsbereich, wie z.B. Routenplanung, von entscheidender Bedeutung. Es gibt jedoch nur wenige öffentlich zugängliche Datensätze zu Straßenbelag und -qualität in einem einheitlichen Format, da die Erstellung meist auf manueller Analyse beruht und einen erheblichen Aufwand erfordert. Insbesondere Kommunen können von solchen Datensätzen profitieren und sie für die Stadtplanung nutzen.

# Das Projekt 
Das vom Bundesministerium für Digitales und Verkehr geförderte mFund Projekt SurfaceAI  soll diese Lücke schließen. Dazu wird mithilfe öffentlicher Geodaten und Straßenbildern ein Machine Learning Modell trainiert, das in der Lage ist, Straßenoberflächen und -qualität auf Bildern automatisiert und präzise einzustufen. Die generierten Informationen werden anschließend in georeferenzierte Datensätze auf Straßenebene umgewandelt, die öffentlich zugänglich sind.

# Aktuelles

**26.02.2025 9:00-10:00: offizielles Projekt-Abschlusstreffen (online)**. Teilnahme-Link bitte anfragen über surface&#x2011;ai@htw&#x2011;berlin.de 

**16.01.2025:** Veröffentlichung unseres Papers [**StreetSurfaceVis: a dataset of crowdsourced street-level imagery annotated by road surface type and quality**](https://doi.org/10.1038/s41597-024-04295-9) in **Scientific Data**

**29.10.2024:** Präsentation unseres [**short papers**](https://dl.acm.org/doi/10.1145/3681780.3697277) auf dem [**UrbanAI Workshop der SIGSPATIAL Conference**](https://urbanai.ornl.gov/urbanai2024/)

**22.6.2024 17.00-24.00: Lange Nacht der Wissenschaften** an der HTW Berlin, Campus Wilhelminenhof, Gebäude C, Raum 604 [Programmdetails](https://events.htw-berlin.de/hochschule/lange-nacht-der-wissenschaften/)

**19.6.2024 13.00-18.00: Vortrag auf dem Informatiktag HTW Berlin** [Programmdetails](https://events.htw-berlin.de/karriere/informatiktag/)

**4.6.2024: Veröffentlichung des SurfaceAI Datensatzes** [StreetSurfaceVis (doi: 10.5281/zenodo.11449976)](https://zenodo.org/records/11449977)


**20.3.2024: FOSSGIS 2024** [Präsentation des Projekts auf der FOSSGIS Konferenz](https://pretalx.com/fossgis2024/talk/MHTEAN/)

**10.1.2024 14.00-15.00: offizieller Projekt-Kickoff (online)**
[Teilnahme über Zoom](https://htw-berlin.zoom-x.de/j/63436322281?pwd=cE5iWm1DbmJ1TzFwdWNmTDNEdW93QT09)

# Veröffentlichungen
- Die erste Version unseres [**Programm-Codes**](https://github.com/SurfaceAI/road_network_classification) mit der vollständigen Pipeline zur Anreicherung ganzer Straßennetze mit den Informationen zu Straßenbelag und -qualität ist fertiggestellt und kann auf Github heruntergeladen werden.

- Die mit dem SurfaceAI Modell erzeugten **kommunalen Datensätze** der Städte/Stadtteile München, Berlin-Neukölln, Osnabrück und Dresden sind in der [Mobilithek](https://mobilithek.info/offers/804060514242924544) verfügbar.

- Paper: Alexandra Kapp, Edith Hoffmann, Esther Weigmann, and Helena Mihaljević. 2024. [**SurfaceAI: Automated creation of cohesive road surface quality datasets based on open street-level imagery.**](https://doi.org/10.1145/3681780.3697277) In Proceedings of the 2nd ACM SIGSPATIAL International Workshop on Advances in Urban-AI (UrbanAI '24). Association for Computing Machinery, New York, NY, USA, 54–57.

- Paper: Alexandra Kapp, Edith Hoffmann, Esther Weigmann, and Helena Mihaljević. 2025. [**StreetSurfaceVis: a dataset of crowdsourced street-level imagery annotated by road surface type and quality.**](https://doi.org/10.1038/s41597-024-04295-9) Sci Data 12, 92 (2025).

- Datensatz [**StreetSurfaceVis**](https://zenodo.org/records/11449977) bestehend aus Straßenbildern aus Deutschland mit Beschriftungen zu Art und Qualität der Straßenoberfläche

# Anwendungsmöglichkeiten und assoziierte Projektpartner
Das Projekt wird von verschiedenen Organisationen unterstützt, die die Ausarbeitung von Anwendungsbeispielen ermöglichen und die Vernetzung innerhalb der Community fördern. 

Dazu gehören:
- der Routenplanungs- und Navigationsanbieter [**Komoot**](https://www.komoot.de/),  
- die Beratungsfirma [**Plan4Better**](https://plan4better.de/), die Kommunen bei der Entwicklung von Mobilitätskonzepten unterstützt und das Webtool GOAT für Erreichbarkeitsanalysen u.a. im Fuß- und Radverkehr entwickelt hat,
- die Technologiestiftung [**CityLAB Berlin**](https://citylab-berlin.org/de/start/), die sich an der Schnittstelle zwischen Zivilgesellschaft und Verwaltung für eine gemeinwohlorientierte Stadtentwicklung einsetzt, und
- das Start-Up [**FixMyCity**](https://www.fixmycity.de/), das Städte und Kommunen bei der Verkehrswende, insbesondere der Fahrradverkehrsplanung, durch digital Tools unterstützt. 

Zwei konkrete Anwendungsbereiche für die Nutzung der automatisch generierten Straßenbeschaffenheitsdaten sind bereits angedacht. Zum einen können die Daten direkt in die Routenberechnung von Navigationstools einfließen, zum anderen der Analyse und Planung im Bereich der (Rad-)Verkehrsplanung auf kommunaler Ebene dienen.

# Team

{% for member in site.data.team %}
  {% include team.html member=member %}
{% endfor %}

# Kontakt
<!-- &#x2011; non-break hyphen character -->
Wir freuen uns über Fragen, Anregungen und Kooperationsmöglichkeiten: ***surface&#x2011;ai@htw&#x2011;berlin.de***

&nbsp;

---

<!-- <font size="5"> Ein Projekt der </font> -->
Ein Projekt der

![HTW_Logo](/assets/images/S04_HTW_Berlin_Logo_pos_FARBIG_RGB.jpg){: .align-left width="172px"}
![mFUND_Logo](/assets/images/mFUND_Logo_Mobilitaet_RGB.png){: .align-right width="100px" style="margin-top: 100px; margin-left: 50px"}
<!-- BMDV_Logo height="175px" was ignored -->
![BMDV_Logo](/assets/images/BMDV_Fz_2021_Web_Farbe_de.gif){: .align-right style="height: 175px"}
