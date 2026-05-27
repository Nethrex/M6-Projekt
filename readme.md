# EV Route Planner

Velkommen til vores repository for **EV Route Planner** – en simpel og funktionel ruteplanlægger til elbiler, udviklet i forbindelse med vores M6-eksamensprojekt (*Design af IT-baserede systemer*) på IT-Ledelse ved Aalborg Universitet.

## Om projektet
Formålet med denne webapplikation er at hjælpe elbilister med at planlægge køreture og synliggøre relevante ladestop undervejs. 

Systemet er opbygget som, en webbaseret løsning uden egen server eller database. Alt logik afvikles direkte i brugerens browser via JavaScript, som orkestrerer data på tværs af en række eksterne API'er:
* **Nominatim (OpenStreetMap):** Geokoder adresser og bynavne til præcise GPS-koordinater.
* **OSRM (Open Source Routing Machine):** Beregner køreruten og genererer den polyline, der tegnes på kortet.
* **OpenChargeMap API:** Fremsøger reelle ladestationer langs ruten med fokus på hurtigladere (>50kW).
* **Leaflet.js:** Håndterer det interaktive, visuelle kort samt placering af start-, slut- og lademarkører.

## Dokumentation og systemdesign
Da dette projekt primært vægter design, styring og udviklingsproces, har vi samlet al vores uddybende dokumentation ét centralt sted. 

Du kan finde vores systemarkitektur, API-beskrivelser samt vores to UML-diagrammer (**Sekvensdiagrammet** for den eksterne kommunikation og vores **Aktivitetsdiagram** for programflowet) lige her:

**[Se den fulde dokumentation i TECHNICAL_DOCUMENTATION.md](TECHNICAL_DOCUMENTATION.md)**
