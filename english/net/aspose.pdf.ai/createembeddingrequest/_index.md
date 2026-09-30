---
title: "CreateEmbeddingRequest Class"
linktitle: "CreateEmbeddingRequest"
articleTitle: "CreateEmbeddingRequest"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.CreateEmbeddingRequest class. Represents a request for the Create Embeddings endpoint."
type: docs
weight: 250
url: "/net/aspose.pdf.ai/createembeddingrequest/"
keywords: "CreateEmbeddingRequest, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CreateEmbeddingRequest class

Represents a request for the Create Embeddings endpoint.

```csharp
public class CreateEmbeddingRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [CreateEmbeddingRequest](./createembeddingrequest/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Dimensions](./dimensions/) { get; set; } | Gets or sets the number of dimensions the resulting output embeddings should have. Only supported in text-embedding-3 and later models. |
| [EncodingFormat](./encodingformat/) { get; set; } | Gets or sets the format to return the embeddings in. Can be either float or base64. |
| [Input](./input/) { get; set; } | Gets or sets input text to embed, encoded as a string or array of tokens. To embed multiple inputs in a single request, pass an array of strings or array of token arrays. The input must not exceed the max input tokens for the model (8192 tokens for text-embedding-ada-002), cannot be an empty string, and any array must be 2048 dimensions or less. |
| [Model](./model/) { get; set; } | Gets or sets the model to generate the embedding for. |
| [User](./user/) { get; set; } | Gets or sets a unique identifier representing your end-user, which can help OpenAI to monitor and detect abuse. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

