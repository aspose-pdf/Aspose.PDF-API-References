---
title: "Klass Rectangle"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Rectangle-klass. Klassen representerar en rektangel"
type: docs
weight: 9900
url: /sv/net/aspose.pdf/rectangle/
---
## Rectangle class

Klassen representerar en rektangel.

```csharp
public sealed class Rectangle : ICloneable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Konstruktor för Rectangle. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Tom rektangel |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Initierar trivial rektangel, d.v.s. rektangel med noll position och storlek. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Höjd på rektangel. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Kontrollerar om rektangeln är tom. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Kontrollerar om rektangeln är en punkt, d.v.s. LLX är lika med URX och LLY är lika med URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Kontrollerar om rektangeln är trivial, d.v.s. har noll storlek och position. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | X-koordinat för nedre vänstra hörnet. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Y-koordinat för nedre vänstra hörnet. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | X-koordinat för övre högra hörnet. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Y-koordinat för övre högra hörnet. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Bredd på rektangel. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Initierar ny rektangel från given instans av System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Initierar ny rektangel från given instans av System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Försök att tolka strängen och extrahera rektangelkomponenterna llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Returnerar koordinaterna för rektangelns centrum. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Klonar Rectangle-objektet. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Bestämmer om given punkt ligger inom rektangeln. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Bestämmer om rektangeln innehåller en linje representerad av två punkter. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Bestämmer om den givna punkten finns inom rektangeln. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Kontrollera om rektanglar är lika, d.v.s. har samma position och storlekar. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Skär två rektanglar. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Bestämmer om denna rektangel skär en annan rektangel. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Slår ihop rektanglar. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Förskjuter rektangeln med de angivna delta. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Kontrollera om rektanglar är nästan lika, d.v.s. har nästan samma (upp till delta) position och storlekar. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Rotera rektangeln med den angivna vinkeln. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Rotera rektangeln med den angivna vinkeln. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Konverterar rektangel till en array av punkter ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Konverterar rektangel till en instans av System.Drawing.Rectangle. Flyttalspositioner och storlek trunkeras. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Hämtar rektangelns strängrepresentation. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


