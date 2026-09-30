---
title: "DocumentChunk Class"
linktitle: "DocumentChunk"
articleTitle: "DocumentChunk"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.DocumentChunk class. Represents a single chunk of content extracted from a document."
type: docs
weight: 320
url: "/net/aspose.pdf.ai/documentchunk/"
keywords: "DocumentChunk, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## DocumentChunk class

Represents a single chunk of content extracted from a document.

```csharp
public sealed class DocumentChunk
```

## Constructors

| Name | Description |
| --- | --- |
| [DocumentChunk](./documentchunk/)(string, string, int, string) | Initializes a new instance of the [`DocumentChunk`](../../aspose.pdf.ai/documentchunk/) class. |

## Properties

| Name | Description |
| --- | --- |
| [Content](./content/) { get; } | Gets the text content of the chunk. |
| [Context](./context/) { get; } | Gets the structural context of this chunk, typically the header path indicating where this chunk appears in the document hierarchy. |
| [Embedding](./embedding/) { get; set; } | Gets or sets the embedding vector for this chunk. |
| [Id](./id/) { get; } | Gets the unique identifier of the chunk. |
| [Index](./index/) { get; } | Gets the zero-based index of the chunk within the document. |
| [Metadata](./metadata/) { get; } | Gets the metadata associated with this chunk. |

## Methods

| Name | Description |
| --- | --- |
| static [GetVectorDefinition](./getvectordefinition/)(int) | Returns a `VectorStoreCollectionDefinition` describing the schema of [`DocumentChunk`](../../aspose.pdf.ai/documentchunk/) for use with a vector store collection. |

## Remarks

Document chunks are the fundamental units used for AI processing,
 embedding generation, and vector indexing operations.

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

