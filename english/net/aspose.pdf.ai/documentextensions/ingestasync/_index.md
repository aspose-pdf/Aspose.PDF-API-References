---
title: "DocumentExtensions.IngestAsync"
linktitle: "IngestAsync"
articleTitle: "IngestAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "DocumentExtensions method."
type: docs
weight: 20
url: "/net/aspose.pdf.ai/documentextensions/ingestasync/"
product_version: "26.9.0"
---
## DocumentExtensions.IngestAsync method



```csharp
public static Task IngestAsync(this Document document, ChunkingOptions options, string sourceId, 
    IEmbeddingGenerator<string, Embedding<float>> embeddingGenerator, 
    VectorStoreCollection<string, DocumentChunk> vectorCollection, 
    MarkdownSaveOptions markdownSaveOptions = null, CancellationToken cancellationToken = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document |  |
| options | ChunkingOptions |  |
| sourceId | String |  |
| embeddingGenerator | IEmbeddingGenerator`2 |  |
| vectorCollection | VectorStoreCollection`2 |  |
| markdownSaveOptions | MarkdownSaveOptions |  |
| cancellationToken | CancellationToken |  |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ChunkingOptions](../../../aspose.pdf.ai/chunkingoptions/)
* class [MarkdownSaveOptions](../../../aspose.pdf/markdownsaveoptions/)
* class [DocumentExtensions](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

