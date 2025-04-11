---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonOptions klass. Representerar en klass för alternativ för PDF-dokumentjämförelse
type: docs
weight: 3150
url: /sv/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions klass

Representerar en klass för alternativ för PDF-dokumentjämförelse.

```csharp
public class ComparisonOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Hämtar och sätter ordningen för redigeringsoperationer. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Hämtar och sätter de uteslutna områdena. Används för den första sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med [`ExcludeTables`](./excludetables/). Detta alternativ kan inte ställas in tillsammans med [`ExtractionArea`](./extractionarea/) alternativet. |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Hämtar och sätter de uteslutna områdena. Används för den andra sidan eller dokumentet i jämförelsemetoden. Detta alternativ kan ställas in tillsammans med [`ExcludeTables`](./excludetables/). Detta alternativ kan inte ställas in tillsammans med [`ExtractionArea`](./extractionarea/) alternativet. |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Hämtar och sätter alternativet som avgör om tabeller utesluts från jämförelsen. Detta alternativ kan inte ställas in tillsammans med [`ExtractionArea`](./extractionarea/) alternativet. Standardvärdet är `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Hämtar och sätter det rektangulära området där texten på sidorna kommer att jämföras. Detta alternativ kan inte ställas in tillsammans med [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) och [`ExcludeAreas2`](./excludeareas2/) alternativen. |

### Se Även

* namnrymd [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* sammansättning [Aspose.PDF](../../)