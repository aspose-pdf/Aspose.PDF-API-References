---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonOptions class. Represents a PDF document comparison options class
type: docs
weight: 1720
url: /net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class

Represents a PDF document comparison options class.

```csharp
public class ComparisonOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Gets and sets the edit operations order. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Get and set the exclude areas. Used for the first page or document in the comparison method. This option can be setted along with [`ExcludeTables`](./excludetables/). This option can't be setted along with [`ExtractionArea`](./extractionarea/) option. |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Get and set the exclude areas. Used for the second page or document in the comparison method. This option can be setted along with [`ExcludeTables`](./excludetables/). This option can't be setted along with [`ExtractionArea`](./extractionarea/) option. |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Get and set the option that determines whether tables are excluded from comparison. This option cannot be set together with [`ExtractionArea`](./extractionarea/) option. The default value is `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Get and set the rectangular area in which the text of pages will be compared. This option can't be setted along with [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) and [`ExcludeAreas2`](./excludeareas2/) options. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


