---
title: "ComparisonOptions Class"
linktitle: "ComparisonOptions"
articleTitle: "ComparisonOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.ComparisonOptions class. Represents a PDF document comparison options class."
type: docs
weight: 30
url: "/net/aspose.pdf.comparison/comparisonoptions/"
keywords: "ComparisonOptions, Aspose.Pdf.Comparison, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ComparisonOptions class

Represents a PDF document comparison options class.

```csharp
public class ComparisonOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ComparisonOptions](./comparisonoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [EditOperationsOrder](./editoperationsorder/) { get; set; } | Gets and sets the edit operations order. |
| [ExcludeAreas1](./excludeareas1/) { get; set; } | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with `ExcludeTables`. This option can't be setted along with `ExtractionArea` option. |
| [ExcludeAreas2](./excludeareas2/) { get; set; } | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with `ExcludeTables`. This option can't be setted along with `ExtractionArea` option. |
| [ExcludeTables](./excludetables/) { get; set; } | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with `ExtractionArea` option. The default value is `false`. |
| [ExtractionArea](./extractionarea/) { get; set; } | Get and set the rectangular area in which the text of pages will be compared. This option can't be setted along with `ExcludeTables`, `ExcludeAreas1` and `ExcludeAreas2` options. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)

