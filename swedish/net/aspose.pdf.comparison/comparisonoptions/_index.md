---
title: "Klass ComparisonOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Comparison.ComparisonOptions-klass. Representerar en PDF-dokumentjämförelsealternativklass."
type: docs
weight: 3260
url: /sv/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class

Representerar en klass för PDF-dokumentjämförelsealternativ.

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
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Hämtar och anger ordningen för redigeringsoperationer. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med [`ExcludeTables`](./excludetables/). Detta alternativ kan inte ställas in tillsammans med [`ExtractionArea`](./extractionarea/) alternativet. |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan ställas in tillsammans med [`ExcludeTables`](./excludetables/). Detta alternativ kan inte ställas in tillsammans med [`ExtractionArea`](./extractionarea/) alternativet. |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte ställas in tillsammans med [`ExtractionArea`](./extractionarea/) alternativet. Standardvärdet är `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Hämta och ange det rektangulära området där sidornas text kommer att jämföras. Detta alternativ kan inte ställas in tillsammans med [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) och [`ExcludeAreas2`](./excludeareas2/) alternativen. |

### Se även

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


