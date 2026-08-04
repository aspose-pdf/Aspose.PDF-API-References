---
title: "Rechteck"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse stellt ein Rechteck dar."
type: docs
weight: 1320
url: /de/python-net/aspose.pdf/rectangle/
---

## Rectangle class

Klasse stellt ein Rechteck dar.

Der Typ Rectangle stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Initialisiert eine neue Instanz der Klasse Rectangle |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| breite | Breite des Rechtecks. |
| höhe | Höhe des Rechtecks. |
| llx | X-Koordinate der unteren linken Ecke. |
| lly | Y-Koordinate der unteren linken Ecke. |
| urx | X-Koordinate der oberen rechten Ecke. |
| ury | Y-Koordinate der oberen rechten Ecke. |
| trivial | Initialisiert ein triviales Rechteck, d. h. ein Rechteck mit null Position und Größe. |
| is_trivial | Prüft, ob das Rechteck trivial ist, d. h. null Größe und Position hat. |
| is_empty | Prüft, ob das Rechteck leer ist. |
| is_point | Prüft, ob das Rechteck ein Punkt ist, d. h. LLX gleich URX und LLY gleich URY ist. |
| leer | Leeres Rechteck |
## Methoden
| Name | Beschreibung |
| :- | :- |
| rotate(angle) | Rotiert das Rechteck um den angegebenen Winkel. |
| rotate(angle) | Rotiert das Rechteck um den angegebenen Winkel. |
| to_rect() | Konvertiert das Rechteck in eine Instanz von System.Drawing.Rectangle. Gleitkomma-Positionen und -Größen werden abgeschnitten. |
| from_rect(src) | Initialisiert ein neues Rechteck aus einer gegebenen Instanz von System.Drawing.Rectangle. |
| parse(value) | Versucht, die Zeichenkette zu analysieren und daraus die Rechteckkomponenten llx, lly, urx, ury zu extrahieren. |
| equals(other) | Überprüfen, ob Rechtecke gleich sind, d. h. dieselbe Position und Größe haben. |
| near_equals(other, delta) | Überprüfen, ob Rechtecke nahezu gleich sind, d. h. nahezu dieselbe (bis zu delta) Position und Größe haben. |
| intersect(other_rect) | Schneidet Rechtecke. |
| join(other_rect) | Verbindet Rechtecke. |
| is_intersect(other_rect) | Bestimmt, ob dieses Rechteck mit einem anderen Rechteck schneidet. |
| contains(point) | Bestimmt, ob ein gegebener Punkt innerhalb des Rechtecks liegt. |
| center() | Gibt die Koordinaten des Zentrums des Rechtecks zurück. |
| clone() | Klonen des Rectangle-Objekts. |
| to_points() | Konvertiert das Rechteck in ein Array von Punkten ("QuadPoints"). |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

