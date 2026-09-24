---
title: "DocumentChunk.Embedding"
linktitle: "Embedding"
articleTitle: "Embedding"
second_title: "Aspose.PDF for .NET"
description: "Gets or sets the embedding vector for this chunk."
type: docs
weight: 70
url: "/net/aspose.pdf.ai/documentchunk/embedding/"
product_version: "26.9.0"
---
## DocumentChunk.Embedding property

Gets or sets the embedding vector for this chunk.

This property intentionally has no `[VectorStoreVector]` attribute because
 the number of dimensions depends on the embedding model chosen at runtime and
 cannot be declared at compile time. Use `GetVectorDefinition` to
 obtain a `VectorStoreCollectionDefinition` that correctly registers
 this property as the vector field with the appropriate dimension count.

```csharp
public Nullable<ReadOnlyMemory<float>> Embedding { get; set; }
```

### Property Value

Nullable<ReadOnlyMemory<float>>

### See Also

* class [DocumentChunk](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

