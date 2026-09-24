---
title: "CreateEmbeddingRequest.Input"
linktitle: "Input"
articleTitle: "Input"
second_title: "Aspose.PDF for .NET"
description: "Gets or sets input text to embed, encoded as a string or array of tokens. To embed multiple inputs in a single request, pass an array of strings or array of ..."
type: docs
weight: 20
url: "/net/aspose.pdf.ai/createembeddingrequest/input/"
product_version: "26.9.0"
---
## CreateEmbeddingRequest.Input property

Gets or sets input text to embed, encoded as a string or array of tokens. To embed multiple inputs in a single request,
 pass an array of strings or array of token arrays. The input must not exceed the max input tokens
 for the model (8192 tokens for text-embedding-ada-002), cannot be an empty string, and any array must be 2048 dimensions or less.

```csharp
public string Input { get; set; }
```

### Property Value

string

### See Also

* class [CreateEmbeddingRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

