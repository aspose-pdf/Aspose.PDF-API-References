---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en explicit destination som visar sidan med koordinaterna (vänster, överkant) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorade med zoom‑faktorn. Ett null‑värde för någon av parametrarna vänster, överkant eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoom‑värde på 0 har samma betydelse som ett null‑värde."
type: docs
weight: 880
url: /sv/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Representerar en explicit destination som visar sidan med koordinaterna (vänster, överkant) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorade med zoom‑faktorn. Ett null‑värde för någon av parametrarna vänster, överkant eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoom‑värde på 0 har samma betydelse som ett null‑värde.

Typen XYZExplicitDestination exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | Initierar en ny instans av klassen XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | Initierar en ny instans av klassen XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | Initierar en ny instans av klassen XYZExplicitDestination |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| sida | Hämtar destinationssidans objekt |
| page_number | Hämtar destinationssidans sidnummer |
| left | Hämtar vänster horisontell koordinat för fönstrets övre vänstra hörn. |
| top | Hämtar övre vertikala koordinaten för fönstrets övre vänstra hörn. |
| zoom | Hämtar zoomfaktor. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Skapa destination till angiven plats på sidan med hänsyn till sidrotation om det behövs. |
| create_destination(page, type, values) | Skapar instanser av underklasser till ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Skapar instanser av underklasser till ExplicitDestination. |
| create_destination(page_number, type, values) | Skapar instanser av underklasser till ExplicitDestination. |
| create_destination_to_upper_left_corner(page, zoom) | Skapa destination till övre vänstra hörnet på den angivna sidan. |
| create_destination_to_upper_left_corner(page) | Skapa destination till övre vänstra hörnet på den angivna sidan. |
| to_string() | Konverterar objektets tillstånd till ett strängvärde. Exempel: \"1 XYZ 100 200 3\". |

### Se även

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

