---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.SideBySideComparisonOptions-Klasse. Stellt eine Optionsklasse zum Vergleichen von Dokumenten mit nebeneinander angezeigtem Output dar
type: docs
weight: 3290
url: /de/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## Klasse SideBySideComparisonOptions

Stellt eine Optionsklasse zum Vergleichen von Dokumenten mit nebeneinander angezeigtem Output dar.

```csharp
public class SideBySideComparisonOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Ruft die Eigenschaft ab und setzt sie, die bestimmt, ob zusätzliche Änderungsmarkierungen angezeigt werden. Wenn gesetzt, werden Änderungsmarkierungen angezeigt, die sich nicht auf der aktuellen Seite befinden, aber auf einer anderen Seite vorhanden sind. Wenn die Änderung zwischen Wörtern liegt, ist die Markierung möglicherweise nicht genau relativ zum Leerzeichen positioniert. Der Standardwert ist `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Ruft den Vergleichsbereich ab und setzt ihn. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit den Optionen [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) und [`ExcludeAreas2`](./excludeareas2/) gesetzt werden. |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Ruft den Vergleichsbereich ab und setzt ihn. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann nicht zusammen mit den Optionen [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) und [`ExcludeAreas2`](./excludeareas2/) gesetzt werden. |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Ruft einen Vergleichsmodus ab und setzt ihn. Der Standardwert ist !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Ruft die auszuschließenden Bereiche ab und setzt sie. Wird für die erste Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit [`ExcludeTables`](./excludetables/) gesetzt werden. Diese Option kann nicht zusammen mit der Option [`ComparisonArea1`](./comparisonarea1/) gesetzt werden. |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Ruft die auszuschließenden Bereiche ab und setzt sie. Wird für die zweite Seite oder das Dokument in der Vergleichsmethode verwendet. Diese Option kann zusammen mit [`ExcludeTables`](./excludetables/) gesetzt werden. Diese Option kann nicht zusammen mit der Option [`ComparisonArea2`](./comparisonarea2/) gesetzt werden. |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Ruft die Option ab und setzt sie, die bestimmt, ob Tabellen vom Vergleich ausgeschlossen werden. Diese Option kann nicht zusammen mit [`ComparisonArea1`](./comparisonarea1/) und [`ComparisonArea2`](./comparisonarea2/) gesetzt werden. Der Standardwert ist `false`. |

### Siehe auch

* Namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../)