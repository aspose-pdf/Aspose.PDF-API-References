---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Rectangle-Klasse. Klasse repräsentiert Rechteck
type: docs
weight: 9750
url: /de/net/aspose.pdf/rectangle/
---
## Rechteck-Klasse

Klasse repräsentiert Rechteck.

```csharp
public sealed class Rectangle : ICloneable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Konstruktor von Rechteck. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Leeres Rechteck |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Initialisiert triviales Rechteck, d.h. Rechteck mit null Position und Größe. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Höhe des Rechtecks. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Überprüft, ob das Rechteck leer ist. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Überprüft, ob das Rechteck ein Punkt ist, d.h. LLX gleich URX und LLY gleich URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Überprüft, ob das Rechteck trivial ist, d.h. null Größe und Position hat. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | X-Koordinate der unteren linken Ecke. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Y-Koordinate der unteren linken Ecke. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | X-Koordinate der oberen rechten Ecke. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Y-Koordinate der oberen rechten Ecke. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Breite des Rechtecks. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Initialisiert ein neues Rechteck aus der gegebenen Instanz von System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Initialisiert ein neues Rechteck aus der gegebenen Instanz von System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Versucht, den String zu parsen und die Rechteckkomponenten llx, lly, urx, ury daraus zu extrahieren. |
| [Center](../../aspose.pdf/rectangle/center/)() | Gibt die Koordinaten des Zentrums des Rechtecks zurück. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Klont das Rechteck-Objekt. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Bestimmt, ob der gegebene Punkt innerhalb des Rechtecks liegt. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Bestimmt, ob das Rechteck eine Linie enthält, die durch zwei Punkte dargestellt wird. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Bestimmt, ob der gegebene Punkt im Rechteck enthalten ist. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Überprüft, ob die Rechtecke gleich sind, d.h. die gleiche Position und Größe haben. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Schneidet zwei Rechtecke. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Bestimmt, ob dieses Rechteck mit einem anderen Rechteck schneidet. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Verbindet Rechtecke. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Verschiebt das Rechteck um die angegebenen Deltas. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Überprüft, ob die Rechtecke nahezu gleich sind, d.h. nahezu die gleiche (bis zu Delta) Position und Größe haben. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Dreht das Rechteck um den angegebenen Winkel. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Dreht das Rechteck um den angegebenen Winkel. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Konvertiert das Rechteck in ein Array von Punkten ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Konvertiert das Rechteck in eine Instanz von System.Drawing.Rectangle. Gleitkomma-Positionen und -Größen werden abgeschnitten. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Gibt die String-Darstellung des Rechtecks zurück. |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)