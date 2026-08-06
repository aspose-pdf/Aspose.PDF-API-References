---
title: "Rektangel"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen representerar en rektangel."
type: docs
weight: 1320
url: /sv/python-net/aspose.pdf/rectangle/
---

## Rectangle class

Klassen representerar en rektangel.

Rektangeltypen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Initierar en ny instans av klassen Rectangle |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| bredd | Rektangelns bredd. |
| höjd | Rektangelns höjd. |
| llx | X-koordinat för nedre vänstra hörnet. |
| lly | Y-koordinat för nedre vänstra hörnet. |
| urx | X-koordinat för övre högra hörnet. |
| ury | Y-koordinat för övre högra hörnet. |
| trivial | Initierar en trivial rektangel, d.v.s. en rektangel med noll position och storlek. |
| is_trivial | Kontrollerar om rektangeln är trivial, d.v.s. har noll storlek och position. |
| is_empty | Kontrollerar om rektangeln är tom. |
| is_point | Kontrollerar om rektangeln är en punkt, d.v.s. LLX är lika med URX och LLY är lika med URY. |
| empty | Tom rektangel |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| rotate(angle) | Rotera rektangeln med den angivna vinkeln. |
| rotate(angle) | Rotera rektangeln med den angivna vinkeln. |
| to_rect() | Konverterar rektangeln till en instans av System.Drawing.Rectangle. Flyttalspositioner och -storlek trunkeras. |
| from_rect(src) | Initierar en ny rektangel från den givna instansen av System.Drawing.Rectangle. |
| parse(value) | Försök att tolka strängen och extrahera rektangelkomponenterna llx, lly, urx, ury från den. |
| equals(other) | Kontrollera om rektanglar är lika, d.v.s. har samma position och storlekar. |
| near_equals(other, delta) | Kontrollera om rektanglar är nästan lika, d.v.s. har nästan samma (upp till delta) position och storlekar. |
| intersect(other_rect) | Skär med rektanglar. |
| join(other_rect) | Slår ihop rektanglar. |
| is_intersect(other_rect) | Bestämmer om denna rektangel skär med en annan rektangel. |
| contains(point) | Bestämmer om given punkt ligger inom rektangeln. |
| center() | Returnerar koordinaterna för rektangelns centrum. |
| clone() | Klonar Rectangle-objektet. |
| to_points() | Konverterar rektangeln till en array av punkter ("QuadPoints"). |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

