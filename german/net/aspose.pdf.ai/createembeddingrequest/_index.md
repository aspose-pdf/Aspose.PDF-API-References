---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateEmbeddingRequest-Klasse. Stellt eine Anfrage für den Create Embeddings-Endpunkt dar
type: docs
weight: 260
url: /de/net/aspose.pdf.ai/createembeddingrequest/
---
## Klasse CreateEmbeddingRequest

Stellt eine Anfrage für den Create Embeddings-Endpunkt dar.

```csharp
public class CreateEmbeddingRequest
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Ruft die Anzahl der Dimensionen ab oder legt sie fest, die die resultierenden Ausgabeeinbettungen haben sollen. Nur in text-embedding-3 und späteren Modellen unterstützt. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Ruft das Format ab oder legt es fest, in dem die Einbettungen zurückgegeben werden sollen. Kann entweder float oder base64 sein. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Ruft den Eingabetext ab oder legt ihn fest, der eingebettet werden soll, kodiert als Zeichenfolge oder Array von Token. Um mehrere Eingaben in einer einzigen Anfrage einzubetten, übergeben Sie ein Array von Zeichenfolgen oder ein Array von Token-Arrays. Die Eingabe darf die maximalen Eingabetoken für das Modell (8192 Token für text-embedding-ada-002) nicht überschreiten, darf keine leere Zeichenfolge sein und jedes Array muss 2048 Dimensionen oder weniger haben. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Ruft das Modell ab oder legt es fest, für das die Einbettung generiert werden soll. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Ruft eine eindeutige Kennung ab oder legt sie fest, die Ihren Endbenutzer darstellt und OpenAI helfen kann, Missbrauch zu überwachen und zu erkennen. |

### Siehe auch

* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)