---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateEmbeddingRequest class. Represents a request for the Create Embeddings endpoint
type: docs
weight: 270
url: /net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

Represents a request for the Create Embeddings endpoint.

```csharp
public class CreateEmbeddingRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Gets or sets the number of dimensions the resulting output embeddings should have. Only supported in text-embedding-3 and later models. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Gets or sets the format to return the embeddings in. Can be either float or base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Gets or sets input text to embed, encoded as a string or array of tokens. To embed multiple inputs in a single request, pass an array of strings or array of token arrays. The input must not exceed the max input tokens for the model (8192 tokens for text-embedding-ada-002), cannot be an empty string, and any array must be 2048 dimensions or less. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Gets or sets the model to generate the embedding for. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Gets or sets a unique identifier representing your end-user, which can help OpenAI to monitor and detect abuse. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


