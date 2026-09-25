---
title: "DocumentChunk.DocumentChunk"
linktitle: "DocumentChunk"
articleTitle: "DocumentChunk"
second_title: "Aspose.PDF for .NET API Reference"
description: "DocumentChunk constructor. Initializes a new instance of the DocumentChunk class."
type: docs
weight: 10
url: "/net/aspose.pdf.ai/documentchunk/documentchunk/"
product_version: "26.9.0"
---
## DocumentChunk(string, string, int, string) {#constructor}

Initializes a new instance of the [`DocumentChunk`](../../../aspose.pdf.ai/documentchunk/) class.

```csharp
public DocumentChunk(string id, string content, int index, string context)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | string | The unique identifier of the chunk. |
| content | string | The text content of the chunk. |
| index | int | The zero-based index of the chunk within the document. |
| context | string | The structural context of the chunk (e.g. header path), or null if not available. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *id* or *content* is null. |
| ArgumentOutOfRangeException | Thrown when *index* is negative. |

### See Also

* class [DocumentChunk](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

