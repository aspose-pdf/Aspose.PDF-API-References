---
title: "Klass SideBySideComparisonOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Comparison.SideBySideComparisonOptions-klass. Representerar en alternativklass för att jämföra dokument med sida‑vid‑sida‑utdata."
type: docs
weight: 3400
url: /sv/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

Representerar en alternativklass för att jämföra dokument med sida‑vid‑sida‑utdata.

```csharp
public class SideBySideComparisonOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Hämta och ange egenskapen som bestämmer om ytterligare ändringsmarkörer visas. Om den är satt visas ändringsmarkörer som inte finns på den aktuella sidan men som finns på en annan sida. Om ändringen ligger mellan ord kan markören eventuellt inte placeras exakt i förhållande till blankstegstecknet. Standardvärdet är `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Hämta och ange jämförelseområdet. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte anges tillsammans med [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) och [`ExcludeAreas2`](./excludeareas2/) alternativ. |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Hämta och ange jämförelseområdet. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan inte anges tillsammans med [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) och [`ExcludeAreas2`](./excludeareas2/) alternativ. |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Hämtar och anger ett jämförelseläge. Standardvärdet är !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Hämta och ange exkluderingsområdena. Används för den första sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan anges tillsammans med [`ExcludeTables`](./excludetables/). Detta alternativ kan inte anges tillsammans med [`ComparisonArea1`](./comparisonarea1/) alternativet. |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Hämta och ange exkluderingsområdena. Används för den andra sidan eller dokumentet i jämförelsesmetoden. Detta alternativ kan anges tillsammans med [`ExcludeTables`](./excludetables/). Detta alternativ kan inte anges tillsammans med [`ComparisonArea2`](./comparisonarea2/) alternativet. |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Hämta och ange alternativet som bestämmer om tabeller exkluderas från jämförelsen. Detta alternativ kan inte anges tillsammans med [`ComparisonArea1`](./comparisonarea1/) och [`ComparisonArea2`](./comparisonarea2/). Standardvärdet är `false`. |

### Se även

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


