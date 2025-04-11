---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XYZExplicitDestination klass. Representerar en explicit destination som visar sidan med koordinaterna vänster, topp placerade i det övre vänstra hörnet av fönstret och innehållet på sidan förstorat med faktorn zoom. Ett nullvärde för någon av parametrarna vänster, topp eller zoom specificerar att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoomvärde på 0 har samma betydelse som ett nullvärde.
type: docs
weight: 2730
url: /sv/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination klass

Representerar en explicit destination som visar sidan med koordinaterna (vänster, topp) placerade i det övre vänstra hörnet av fönstret och innehållet på sidan förstorat med faktorn zoom. Ett nullvärde för någon av parametrarna vänster, topp eller zoom specificerar att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoomvärde på 0 har samma betydelse som ett nullvärde.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Skapar en fjärrexplicit destination. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Skapar en lokal explicit destination. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Hämtar vänster horisontell koordinat för det övre vänstra hörnet av fönstret. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Hämtar destinationssidans objekt |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Hämtar destinationssidans nummer |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Hämtar övre vertikal koordinat för det övre vänstra hörnet av fönstret. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Hämtar zoomfaktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Skapar destination till angiven plats på sidan med hänsyn till sidrotation om det behövs. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Skapar destination till angiven sida. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Skapar destination till det övre vänstra hörnet av den angivna sidan. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Konverterar objektets tillstånd till strängvärde. Exempel: "1 XYZ 100 200 3". |

## Exempel

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Se Även

* klass [ExplicitDestination](../explicitdestination/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)