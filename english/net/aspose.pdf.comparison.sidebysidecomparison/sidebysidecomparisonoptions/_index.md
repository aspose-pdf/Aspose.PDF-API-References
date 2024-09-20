---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.SideBySideComparison.SideBySideComparisonOptions class. Represents an options class for comparing documents with sidebyside output
type: docs
weight: 1890
url: /net/aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

Represents an options class for comparing documents with side-by-side output.

```csharp
public class SideBySideComparisonOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Get and set the property that determines whether additional change markers are displayed. If set, displays change marks that are not on the current page but are present on another page. If the change lacates between words, the mark may not be positioned exactly relative to the whitespace character. The default value is `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Get and set the comparison area. Used for the first page or document in the comparison method. This option can't be setted along with [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) and [`ExcludeAreas2`](./excludeareas2/) options. |
| [ComparisonArea2](../../aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Get and set the comparison area. Used for the second page or document in the comparison method. This option can't be setted along with [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) and [`ExcludeAreas2`](./excludeareas2/) options. |
| [ComparisonMode](../../aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Gets and sets a comparison mode. The default value is IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with [`ExcludeTables`](./excludetables/). This option can't be setted along with [`ComparisonArea1`](./comparisonarea1/) option. |
| [ExcludeAreas2](../../aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with [`ExcludeTables`](./excludetables/). This option can't be setted along with [`ComparisonArea2`](./comparisonarea2/) option. |
| [ExcludeTables](../../aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with [`ComparisonArea1`](./comparisonarea1/) and [`ComparisonArea2`](./comparisonarea2/). The default value is `false`. |

### See Also

* namespace [Aspose.Pdf.Comparison.SideBySideComparison](../../aspose.pdf.comparison.sidebysidecomparison/)
* assembly [Aspose.PDF](../../)


