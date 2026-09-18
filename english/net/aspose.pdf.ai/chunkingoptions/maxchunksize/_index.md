---
title: ChunkingOptions.MaxChunkSize
second_title: Aspose.PDF for .NET API Reference
description: ChunkingOptions property. Gets or sets the maximum size of each chunk in tokens
type: docs
weight: 20
url: /net/aspose.pdf.ai/chunkingoptions/maxchunksize/
---
## ChunkingOptions.MaxChunkSize property

Gets or sets the maximum size of each chunk in tokens.

```csharp
public int MaxChunkSize { get; set; }
```

### Property Value

The maximum chunk size in tokens. Must be between [`MinimumChunkSize`](../minimumchunksize/) and [`MaximumChunkSize`](../maximumchunksize/). Default is [`DefaultMaxChunkSize`](../defaultmaxchunksize/).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when the value is less than [`MinimumChunkSize`](../minimumchunksize/) or greater than [`MaximumChunkSize`](../maximumchunksize/). |

### See Also

* class [ChunkingOptions](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


