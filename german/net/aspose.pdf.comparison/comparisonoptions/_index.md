---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonOptions-Klasse. Stellt eine Klasse für die Vergleichsoptionen von PDF-Dokumenten dar
type: docs
weight: 3150
url: /de/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions-Klasse

Stellt eine Klasse für die Vergleichsoptionen von PDF-Dokumenten dar.

```csharp
public class ComparisonOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Ruft die Reihenfolge der Bearbeitungsoperationen ab und legt sie fest. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Ruft die auszuschließenden Bereiche ab und legt sie fest. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit [`ExcludeTables`](./excludetables/) festgelegt werden. Diese Option kann nicht zusammen mit der [`ExtractionArea`](./extractionarea/) Option festgelegt werden. |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Ruft die auszuschließenden Bereiche ab und legt sie fest. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit [`ExcludeTables`](./excludetables/) festgelegt werden. Diese Option kann nicht zusammen mit der [`ExtractionArea`](./extractionarea/) Option festgelegt werden. |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Ruft die Option ab und legt sie fest, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit der [`ExtractionArea`](./extractionarea/) Option festgelegt werden. Der Standardwert ist `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Ruft den rechteckigen Bereich ab und legt ihn fest, in dem der Text der Seiten verglichen wird. Diese Option kann nicht zusammen mit den Optionen [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) und [`ExcludeAreas2`](./excludeareas2/) festgelegt werden. |

### Siehe Auch

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)