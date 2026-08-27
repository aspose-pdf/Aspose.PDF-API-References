---
title: "Klass XYZExplicitDestination"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.XYZExplicitDestination‑klass. Representerar en explicit destination som visar sidan med koordinaterna vänster‑övre placerade i fönstrets övre vänstra hörn och sidans innehåll förstorad med zoom‑faktorn. Ett null‑värde för någon av parametrarna vänster, övre eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoom‑värde på 0 har samma betydelse som ett null‑värde."
type: docs
weight: 2830
url: /sv/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

Representerar en explicit destination som visar sidan med koordinaterna (vänster, topp) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorade med zoom‑faktorn. Ett null‑värde för någon av parametrarna vänster, topp eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoom‑värde på 0 har samma betydelse som ett null‑värde.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Skapar fjärrexplicit destination. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Skapar lokal explicit destination. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Hämtar horisontell koordinat (vänster) för fönstrets övre vänstra hörn. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Hämtar destinationssidans objekt |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Hämtar destinationssidans sidnummer |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Hämtar vertikal koordinat (övre) för fönstrets övre vänstra hörn. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Hämtar zoom‑faktor. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Skapa destination till angiven plats på sidan med hänsyn till sidrotation om det behövs. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Skapa destination till angiven sida. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Skapa destination till övre vänstra hörnet på den angivna sidan. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 XYZ 100 200 3". |

## Exempel

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Se även

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


