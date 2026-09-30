---
title: "SideBySideComparisonOptions Class"
linktitle: "SideBySideComparisonOptions"
articleTitle: "SideBySideComparisonOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.SideBySideComparisonOptions class. Represents an options class for comparing documents with side-by-side output."
type: docs
weight: 180
url: "/net/aspose.pdf.comparison/sidebysidecomparisonoptions/"
keywords: "SideBySideComparisonOptions, Aspose.Pdf.Comparison, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SideBySideComparisonOptions class

Represents an options class for comparing documents with side-by-side output.

```csharp
public class SideBySideComparisonOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SideBySideComparisonOptions](./sidebysidecomparisonoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AdditionalChangeMarks](./additionalchangemarks/) { get; set; } | Get and set the property that determines whether additional change markers are displayed. If set, displays change marks that are not on the current page but are present on another page. If the change lacates between words, the mark may not be positioned exactly relative to the whitespace character. The default value is `false`. |
| [ComparisonArea1](./comparisonarea1/) { get; set; } | Get and set the comparison area. Used for the first page or document in the comparison method. This option can't be setted along with `ExcludeTables`, `ExcludeAreas1` and `ExcludeAreas2` options. |
| [ComparisonArea2](./comparisonarea2/) { get; set; } | Get and set the comparison area. Used for the second page or document in the comparison method. This option can't be setted along with `ExcludeTables`, `ExcludeAreas1` and `ExcludeAreas2` options. |
| [ComparisonMode](./comparisonmode/) { get; set; } | Gets and sets a comparison mode. The default value is `IgnoreSpaces`. |
| [DeleteColor](./deletecolor/) { get; set; } | Gets or sets the color used to mark deleted content during a side-by-side comparison. This property defines the visual representation for deletions in the comparison result. |
| [ExcludeAreas1](./excludeareas1/) { get; set; } | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with `ExcludeTables`. This option can't be setted along with `ComparisonArea1` option. |
| [ExcludeAreas2](./excludeareas2/) { get; set; } | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with `ExcludeTables`. This option can't be setted along with `ComparisonArea2` option. |
| [ExcludeTables](./excludetables/) { get; set; } | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with `ComparisonArea1` and `ComparisonArea2`. The default value is `false`. |
| [InsertColor](./insertcolor/) { get; set; } | Gets or sets the color used to mark inserted content during a side-by-side comparison. This property defines the visual representation for insertion in the comparison result. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)

