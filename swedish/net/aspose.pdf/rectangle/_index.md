---
title: Rectangle
second_title: Aspose.PDF för .NET API Referens
description: Klass representerar rektangel.
type: docs
weight: 6190
url: /sv/net/aspose.pdf/rectangle/
---
## Rectangle class

Klass representerar rektangel.

```csharp
public sealed class Rectangle : ICloneable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Rectangle](rectangle)(double, double, double, double) | Konstruktör av rektangel. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Trivial](../../aspose.pdf/rectangle/trivial) { get; } | Initierar trivial rektangel dvs rektangel med nollposition och storlek. |
| [Height](../../aspose.pdf/rectangle/height) { get; } | Rektangelns höjd. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty) { get; } | Kontrollerar om rektangeln är tom. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint) { get; } | Kontrollerar om rektangel är punkt, dvs. LLX är lika med URX och LLY är lika med URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial) { get; } | Kontrollerar om rektangeln är trivial dvs har noll storlek och position. |
| [LLX](../../aspose.pdf/rectangle/llx) { get; set; } | X-koordinat för nedre - vänstra hörnet. |
| [LLY](../../aspose.pdf/rectangle/lly) { get; set; } | Y - koordinat för nedre vänstra hörnet. |
| [URX](../../aspose.pdf/rectangle/urx) { get; set; } | X - koordinat för det övre högra hörnet. |
| [URY](../../aspose.pdf/rectangle/ury) { get; set; } | Y - koordinat för övre högra hörnet. |
| [Width](../../aspose.pdf/rectangle/width) { get; } | Bredd på rektangeln. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect)(Rectangle) | Initierar ny rektangel från given instans av System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse)(string) | Försök att analysera sträng och extrahera från den rektangelkomponenter llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center)() | Returnerar koordinater för rektangelns centrum. |
| [Clone](../../aspose.pdf/rectangle/clone)() | Klonar Rectangle-objektet. |
| [Contains](../../aspose.pdf/rectangle/contains)(Point) | Avgör om en given punkt är inuti rektangeln. |
| [Equals](../../aspose.pdf/rectangle/equals#equals)(Rectangle) | Kontrollera om rektanglar är lika, dvs har samma position och storlekar. |
| [Intersect](../../aspose.pdf/rectangle/intersect)(Rectangle) | Skär till rektanglar. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect)(Rectangle) | Bestämmer om denna rektangel skär en annan rektangel. |
| [Join](../../aspose.pdf/rectangle/join)(Rectangle) | Sammanfogar rektanglar. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals)(Rectangle, double) | Kontrollera om rektanglar är nästan lika, dvs har nästan samma (upp till delta) position och storlekar. |
| [Rotate](../../aspose.pdf/rectangle/rotate#rotate_1)(int) | Rotera rektangeln med den angivna vinkeln. |
| [Rotate](../../aspose.pdf/rectangle/rotate#rotate)(Rotation) | Rotera rektangeln med den angivna vinkeln. |
| [ToPoints](../../aspose.pdf/rectangle/topoints)() | Konverterar rektangel till array av punkter ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect)() | Konverterar rektangel till instans av System.Drawing.Rectangle. Flyttalspositioner och storlek är trunkerade. |
| override [ToString](../../aspose.pdf/rectangle/tostring)() | Får representation av rektangelsträngar. |

## Fält

| namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty) | Tom rektangel |

### Se även

* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->