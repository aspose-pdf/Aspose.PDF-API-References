---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt ein explizites Ziel dar, das die Seite mit den Koordinaten (links, oben) an der oberen linken Ecke des Fensters anzeigt und den Seiteninhalt um den Zoom‑Faktor vergrößert. Ein Nullwert für einen der Parameter links, oben oder zoom gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird. Ein Zoom‑Wert von 0 hat dieselbe Bedeutung wie ein Nullwert."
type: docs
weight: 880
url: /de/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Stellt ein explizites Ziel dar, das die Seite mit den Koordinaten (links, oben) an der oberen linken Ecke des Fensters anzeigt und den Seiteninhalt um den Zoom‑Faktor vergrößert. Ein Nullwert für einen der Parameter links, oben oder zoom gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird. Ein Zoom‑Wert von 0 hat dieselbe Bedeutung wie ein Nullwert.

Der Typ XYZExplicitDestination stellt die folgenden Member bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | Initialisiert eine neue Instanz der Klasse XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | Initialisiert eine neue Instanz der Klasse XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | Initialisiert eine neue Instanz der Klasse XYZExplicitDestination |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| page | Liefert das Zielseitenobjekt |
| page_number | Liefert die Zielseitennummer |
| left | Ruft die linke horizontale Koordinate der oberen linken Ecke des Fensters ab. |
| top | Ruft die obere vertikale Koordinate der oberen linken Ecke des Fensters ab. |
| zoom | Ruft den Zoom‑Faktor ab. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Erstellt ein Ziel an der angegebenen Position der Seite und berücksichtigt dabei die Seitendrehung, falls erforderlich. |
| create_destination(page, type, values) | Erstellt Instanzen von abgeleiteten Klassen von ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Erstellt Instanzen von abgeleiteten Klassen von ExplicitDestination. |
| create_destination(page_number, type, values) | Erstellt Instanzen von abgeleiteten Klassen von ExplicitDestination. |
| create_destination_to_upper_left_corner(page, zoom) | Erstellt ein Ziel zur oberen linken Ecke der angegebenen Seite. |
| create_destination_to_upper_left_corner(page) | Erstellt ein Ziel zur oberen linken Ecke der angegebenen Seite. |
| to_string() | Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 XYZ 100 200 3". |

### Siehe auch

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

