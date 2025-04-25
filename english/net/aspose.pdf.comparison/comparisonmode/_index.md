---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonMode enum. The comparison mode enumeration
type: docs
weight: 3240
url: /net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enumeration

The comparison mode enumeration.

```csharp
public enum ComparisonMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Normal | `0` | Normal mode. Only spaces within text fragments are taken into account (depending on the way the document is generated.) |
| IgnoreSpaces | `1` | All spaces are ignored. Changes are sought only in words. |
| ParseSpaces | `2` | The mode is similar to normal, but attempts to account for visual spacing between text fragments based on distance. Recognizing the number of spaces between fragments may not be accurate because this greatly depends on how the documents are generated. If documents are created by different generators, there may be inaccuracies in comparing spaces between text fragments. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


