---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CreateEmbeddingRequest. Rappresenta una richiesta per l'endpoint Crea Embeddings
type: docs
weight: 260
url: /it/net/aspose.pdf.ai/createembeddingrequest/
---
## Classe CreateEmbeddingRequest

Rappresenta una richiesta per l'endpoint Crea Embeddings.

```csharp
public class CreateEmbeddingRequest
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Ottiene o imposta il numero di dimensioni che le embeddings di output risultanti devono avere. Supportato solo nei modelli text-embedding-3 e successivi. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Ottiene o imposta il formato per restituire le embeddings. Può essere float o base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Ottiene o imposta il testo di input da incorporare, codificato come stringa o array di token. Per incorporare più input in una singola richiesta, passare un array di stringhe o un array di array di token. L'input non deve superare il numero massimo di token di input per il modello (8192 token per text-embedding-ada-002), non può essere una stringa vuota e qualsiasi array deve avere 2048 dimensioni o meno. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Ottiene o imposta il modello per generare l'embedding. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Ottiene o imposta un identificatore unico che rappresenta il tuo utente finale, che può aiutare OpenAI a monitorare e rilevare abusi. |

### Vedi Anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)