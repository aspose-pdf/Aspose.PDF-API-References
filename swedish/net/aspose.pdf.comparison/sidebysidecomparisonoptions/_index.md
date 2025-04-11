---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.SideBySideComparisonOptions klass. Representerar en alternativklass för att jämföra dokument med sid-vid-sid-utdata
type: docs
weight: 3290
url: /sv/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions klass

Representerar en alternativklass för att jämföra dokument med sid-vid-sid-utdata.

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
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Hämta och ställ in egenskapen som avgör om ytterligare ändringsmarkeringar visas. Om den är inställd, visar ändringsmarkeringar som inte finns på den aktuella sidan men som finns på en annan sida. Om ändringen ligger mellan ord, kan markeringen kanske inte vara exakt positionerad i förhållande till mellanslagstecknet. Standardvärdet är `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Hämta och ställ in jämförelseområdet. Används för den första sidan eller dokumentet i jämförelsemetoden. Det här alternativet kan inte ställas in tillsammans med [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) och [`ExcludeAreas2`](./excludeareas2/) alternativ. |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Hämta och ställ in jämförelseområdet. Används för den andra sidan eller dokumentet i jämförelsemetoden. Det här alternativet kan inte ställas in tillsammans med [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) och [`ExcludeAreas2`](./excludeareas2/) alternativ. |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Hämtar och ställer in en jämförelsemetod. Standardvärdet är !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Hämta och ställ in de uteslutna områdena. Används för den första sidan eller dokumentet i jämförelsemetoden. Det här alternativet kan ställas in tillsammans med [`ExcludeTables`](./excludetables/). Det här alternativet kan inte ställas in tillsammans med [`ComparisonArea1`](./comparisonarea1/) alternativ. |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Hämta och ställ in de uteslutna områdena. Används för den andra sidan eller dokumentet i jämförelsemetoden. Det här alternativet kan ställas in tillsammans med [`ExcludeTables`](./excludetables/). Det här alternativet kan inte ställas in tillsammans med [`ComparisonArea2`](./comparisonarea2/) alternativ. |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Hämta och ställ in alternativet som avgör om tabeller utesluts från jämförelsen. Det här alternativet kan inte ställas in tillsammans med [`ComparisonArea1`](./comparisonarea1/) och [`ComparisonArea2`](./comparisonarea2/). Standardvärdet är `false`. |

### Se Även

* namnrymd [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* sammansättning [Aspose.PDF](../../)