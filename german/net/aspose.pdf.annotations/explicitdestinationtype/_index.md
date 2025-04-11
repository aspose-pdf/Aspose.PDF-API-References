---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.ExplicitDestinationType Enum. Enumeriert die Typen von expliziten Zielen
type: docs
weight: 1690
url: /de/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType Aufzählung

Enumeriert die Typen von expliziten Zielen.

```csharp
public enum ExplicitDestinationType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| XYZ | `0` | Zeigt die Seite mit den Koordinaten (links, oben) an, die in der oberen linken Ecke des Fensters positioniert sind, und der Inhalt der Seite wird um den Faktor Zoom vergrößert. Ein Nullwert für einen der Parameter links, oben oder Zoom gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. Ein Zoomwert von 0 hat die gleiche Bedeutung wie ein Nullwert. |
| Fit | `1` | Zeigt die Seite an, deren Inhalt gerade so vergrößert wird, dass die gesamte Seite sowohl horizontal als auch vertikal im Fenster passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, verwenden Sie den kleineren der beiden und zentrieren Sie die Seite im anderen Maßstab innerhalb des Fensters. |
| FitH | `2` | Zeigt die Seite an, wobei die vertikale Koordinate oben am oberen Rand des Fensters positioniert ist und der Inhalt der Seite gerade so vergrößert wird, dass die gesamte Breite der Seite im Fenster passt. Ein Nullwert für oben gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. |
| FitV | `3` | Zeigt die Seite an, wobei die horizontale Koordinate links am linken Rand des Fensters positioniert ist und der Inhalt der Seite gerade so vergrößert wird, dass die gesamte Höhe der Seite im Fenster passt. Ein Nullwert für links gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. |
| FitR | `4` | Zeigt die Seite an, deren Inhalt gerade so vergrößert wird, dass das durch die Koordinaten links, unten, rechts und oben angegebene Rechteck vollständig sowohl horizontal als auch vertikal im Fenster passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, verwenden Sie den kleineren der beiden und zentrieren Sie das Rechteck im anderen Maßstab innerhalb des Fensters. Ein Nullwert für einen der Parameter kann zu unvorhersehbarem Verhalten führen. |
| FitB | `5` | Zeigt die Seite an, deren Inhalt gerade so vergrößert wird, dass die gesamte Begrenzungsbox vollständig sowohl horizontal als auch vertikal im Fenster passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, verwenden Sie den kleineren der beiden und zentrieren Sie die Begrenzungsbox im anderen Maßstab innerhalb des Fensters. |
| FitBH | `6` | Zeigt die Seite an, wobei die vertikale Koordinate oben am oberen Rand des Fensters positioniert ist und der Inhalt der Seite gerade so vergrößert wird, dass die gesamte Breite seiner Begrenzungsbox im Fenster passt. Ein Nullwert für oben gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. |
| FitBV | `7` | Zeigt die Seite an, wobei die horizontale Koordinate links am linken Rand des Fensters positioniert ist und der Inhalt der Seite gerade so vergrößert wird, dass die gesamte Höhe seiner Begrenzungsbox im Fenster passt. Ein Nullwert für links gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten werden soll. |

### Siehe auch

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)