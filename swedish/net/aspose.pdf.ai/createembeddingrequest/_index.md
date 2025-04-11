---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateEmbeddingRequest klass. Representerar en begäran för Create Embeddings slutpunkt
type: docs
weight: 260
url: /sv/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest klass

Representerar en begäran för Create Embeddings slutpunkt.

```csharp
public class CreateEmbeddingRequest
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Hämtar eller ställer in antalet dimensioner som de resulterande utdataembeddings ska ha. Endast stöd för text-embedding-3 och senare modeller. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Hämtar eller ställer in formatet för att returnera embeddings i. Kan vara antingen float eller base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Hämtar eller ställer in inmatningstext att bädda in, kodad som en sträng eller array av tokens. För att bädda in flera inmatningar i en enda begäran, skicka en array av strängar eller array av token-arrayer. Inmatningen får inte överskrida max inmatningstokens för modellen (8192 tokens för text-embedding-ada-002), får inte vara en tom sträng, och någon array måste vara 2048 dimensioner eller mindre. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Hämtar eller ställer in modellen för att generera embedding för. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Hämtar eller ställer in en unik identifierare som representerar din slutanvändare, vilket kan hjälpa OpenAI att övervaka och upptäcka missbruk. |

### Se Även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)