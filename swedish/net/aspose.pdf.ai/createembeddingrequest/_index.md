---
title: "Klass CreateEmbeddingRequest"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.CreateEmbeddingRequest-klass. Representerar en begäran för Create Embeddings-slutpunkten"
type: docs
weight: 270
url: /sv/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

Representerar en begäran för slutpunkten Create Embeddings.

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
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Hämtar eller anger antalet dimensioner som de resulterande output-embeddingarna ska ha. Stöds endast i text-embedding-3 och senare modeller. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Hämtar eller anger formatet som embeddingarna ska returneras i. Kan vara antingen float eller base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Hämtar eller anger inmatningstext att embedda, kodad som en sträng eller array av token. För att embedda flera inmatningar i en enda begäran, skicka en array av strängar eller en array av token-arrayer. Inmatningen får inte överskrida det maximala antalet token för modellen (8192 token för text-embedding-ada-002), får inte vara en tom sträng, och varje array får ha högst 2048 dimensioner. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Hämtar eller anger modellen för att generera embeddingarna. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Hämtar eller anger en unik identifierare som representerar din slutanvändare, vilket kan hjälpa OpenAI att övervaka och upptäcka missbruk. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


