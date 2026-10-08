---
title: "ChunkingOptions.OverlapSize"
linktitle: "OverlapSize"
articleTitle: "OverlapSize"
second_title: "Aspose.PDF for .NET API Reference"
description: "ChunkingOptions property. Gets or sets the number of tokens to overlap between consecutive chunks."
type: docs
weight: 40
url: "/net/aspose.pdf.ai/chunkingoptions/overlapsize/"
product_version: "26.9"
---
## ChunkingOptions.OverlapSize property

Gets or sets the number of tokens to overlap between consecutive chunks.

```csharp
public int OverlapSize { get; set; }
```

### Property Value

The overlap size in tokens. Must be non-negative and less than
 [`MaxChunkSize`](../maxchunksize/). Default is [`DefaultOverlapSize`](../defaultoverlapsize/).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when the value is negative. |

### See Also

* class [ChunkingOptions](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

