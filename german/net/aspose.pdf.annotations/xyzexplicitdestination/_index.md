---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XYZExplicitDestination-Klasse. Stellt ein explizites Ziel dar, das die Seite mit den Koordinaten links oben an der oberen linken Ecke des Fensters anzeigt und den Inhalt der Seite um den Faktor Zoom vergrößert. Ein Nullwert für einen der Parameter links, oben oder Zoom gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. Ein Zoomwert von 0 hat die gleiche Bedeutung wie ein Nullwert.
type: docs
weight: 2730
url: /de/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination-Klasse

Stellt ein explizites Ziel dar, das die Seite mit den Koordinaten (links, oben) an der oberen linken Ecke des Fensters anzeigt und den Inhalt der Seite um den Faktor Zoom vergrößert. Ein Nullwert für einen der Parameter links, oben oder Zoom gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. Ein Zoomwert von 0 hat die gleiche Bedeutung wie ein Nullwert.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Erstellt ein entferntes explizites Ziel. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Erstellt ein lokales explizites Ziel. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Gibt die linke horizontale Koordinate der oberen linken Ecke des Fensters zurück. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gibt das Zielseitenobjekt zurück |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gibt die Zielseitennummer zurück |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Gibt die obere vertikale Koordinate der oberen linken Ecke des Fensters zurück. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Gibt den Zoomfaktor zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Erstellt ein Ziel an der angegebenen Stelle der Seite unter Berücksichtigung der Seitenrotation, falls erforderlich. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Erstellt ein Ziel zur angegebenen Seite. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Erstellt ein Ziel zur oberen linken Ecke der angegebenen Seite. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Konvertiert den Objektzustand in einen Stringwert. Beispiel: "1 XYZ 100 200 3". |

## Beispiele

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Siehe auch

* Klasse [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)