---
title: "HeadingRecognitionStrategy Enum"
linktitle: "HeadingRecognitionStrategy"
articleTitle: "HeadingRecognitionStrategy"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.HeadingRecognitionStrategy enum. Represents types of header recognition strategies."
type: docs
weight: 1100
url: "/net/aspose.pdf/headingrecognitionstrategy/"
product_version: "26.9.0"
---
## HeadingRecognitionStrategy enumeration

Represents types of header recognition strategies.

```csharp
public enum HeadingRecognitionStrategy
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Outlines | `0` | Represents the header recognition strategy by means of outlines. |
| Heuristic | `1` | Represents the header recognition strategy by means of heuristics rules and font size statistic. |
| Auto | `2` | Provides an automatic header recognition strategy selection.
 This is the default option.
 If the document contains bookmarks, the <see cref="F:Aspose.Pdf.HeadingRecognitionStrategy.Outlines" /> strategy will be selected, otherwise <see cref="F:Aspose.Pdf.HeadingRecognitionStrategy.Heuristic" /> |
| None | `3` | Do not recognize headers.
 This option can be useful in complexly formatted documents. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

