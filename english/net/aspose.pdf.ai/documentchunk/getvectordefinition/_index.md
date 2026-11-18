---
title: DocumentChunk.GetVectorDefinition
second_title: Aspose.PDF for .NET API Reference
description: DocumentChunk method. Returns a VectorStoreCollectionDefinition describing the schema of DocumentChunk for use with a vector store collection
type: docs
weight: 80
url: /net/aspose.pdf.ai/documentchunk/getvectordefinition/
---
## DocumentChunk.GetVectorDefinition method

Returns a VectorStoreCollectionDefinition describing the schema of [`DocumentChunk`](../) for use with a vector store collection.

```csharp
public static VectorStoreCollectionDefinition GetVectorDefinition(int dimensions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dimensions | Int32 | The number of dimensions of the embedding vector produced by the embedding model. |

### Return Value

A VectorStoreCollectionDefinition that maps all relevant [`DocumentChunk`](../) properties to their vector store roles.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when *dimensions* is less than or equal to zero. |

### See Also

* class [DocumentChunk](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


