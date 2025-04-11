---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FitRExplicitDestination-Klasse. Stellt ein explizites Ziel dar, das die Seite mit ihren Inhalten so stark vergrößert anzeigt, dass sie vollständig in das durch die Koordinaten links, unten, rechts und oben angegebene Rechteck im Fenster sowohl horizontal als auch vertikal passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, verwenden Sie den kleineren der beiden und zentrieren Sie das Rechteck im Fenster in der anderen Dimension. Ein Nullwert für einen der Parameter kann zu unvorhersehbarem Verhalten führen.
type: docs
weight: 1780
url: /de/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination-Klasse

Stellt ein explizites Ziel dar, das die Seite mit ihren Inhalten so stark vergrößert anzeigt, dass sie vollständig in das durch die Koordinaten links, unten, rechts und oben angegebene Rechteck im Fenster sowohl horizontal als auch vertikal passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, verwenden Sie den kleineren der beiden und zentrieren Sie das Rechteck im Fenster in der anderen Dimension. Ein Nullwert für einen der Parameter kann zu unvorhersehbarem Verhalten führen.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | Erstellt ein entferntes explizites Ziel. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | Erstellt ein lokales explizites Ziel. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | Gibt die untere vertikale Koordinate des sichtbaren Rechtecks zurück. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | Gibt die linke horizontale Koordinate des sichtbaren Rechtecks zurück. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gibt das Zielseitenobjekt zurück. |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gibt die Zielseitennummer zurück. |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | Gibt die rechte horizontale Koordinate des sichtbaren Rechtecks zurück. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | Gibt die obere vertikale Koordinate des sichtbaren Rechtecks zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | Konvertiert den Objektzustand in einen String-Wert. Beispiel: "1 FitR 100 200 300 400". |

### Siehe auch

* Klasse [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)