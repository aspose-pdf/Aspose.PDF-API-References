---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Rectangle klass. Klassen representerar rektangel
type: docs
weight: 9750
url: /sv/net/aspose.pdf/rectangle/
---
## Rectangle klass

Klassen representerar rektangel.

```csharp
public sealed class Rectangle : ICloneable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Konstruktör för Rectangle. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Tom rektangel |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Initierar trivial rektangel, dvs. rektangel med noll position och storlek. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Höjd av rektangel. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Kontrollerar om rektangeln är tom. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Kontrollerar om rektangeln är en punkt, dvs. LLX är lika med URX och LLY är lika med URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Kontrollerar om rektangeln är trivial, dvs. har noll storlek och position. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | X-koordinat för nedre vänstra hörnet. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Y-koordinat för nedre vänstra hörnet. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | X-koordinat för övre högra hörnet. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Y-koordinat för övre högra hörnet. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Bredd av rektangel. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Initierar ny rektangel från given instans av System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Initierar ny rektangel från given instans av System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Försöker att parsa sträng och extrahera rektangelkomponenter llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Returnerar koordinaterna för rektangelns centrum. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Klonar Rectangle-objektet. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Bestämmer om given punkt ligger inom rektangeln. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Bestämmer om rektangeln innehåller en linje representerad av två punkter. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Bestämmer om den givna punkten finns inom rektangeln. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Kontrollerar om rektanglarna är lika, dvs. har samma position och storlekar. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Skär rektanglar. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Bestämmer om denna rektangel skär en annan rektangel. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Förenar rektanglar. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Flyttar rektangeln med angivna deltas. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Kontrollerar om rektanglarna är nästan lika, dvs. har nästan samma (upp till delta) position och storlekar. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Rotera rektangeln med angiven vinkel. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Rotera rektangeln med angiven vinkel. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Konverterar rektangeln till en array av punkter ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Konverterar rektangeln till instans av System.Drawing.Rectangle. Flyttal positioner och storlek trunkeras. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Får rektangelns strängrepresentation. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)