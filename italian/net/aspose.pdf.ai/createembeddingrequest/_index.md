---
title: "Classe CreateEmbeddingRequest"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.CreateEmbeddingRequest. Rappresenta una richiesta per il endpoint Create Embeddings"
type: docs
weight: 270
url: /it/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

Rappresenta una richiesta per il endpoint Create Embeddings.

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
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Ottiene o imposta il numero di dimensioni che gli embedding di output risultanti devono avere. Supportato solo nei modelli text-embedding-3 e successivi. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Ottiene o imposta il formato in cui restituire gli embedding. Può essere float o base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Ottiene o imposta il testo di input da incorporare, codificato come stringa o array di token. Per incorporare più input in una singola richiesta, passa un array di stringhe o un array di array di token. L'input non deve superare il numero massimo di token di input per il modello (8192 token per text-embedding-ada-002), non può essere una stringa vuota e qualsiasi array deve avere al massimo 2048 dimensioni. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Ottiene o imposta il modello per cui generare l'embedding. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Ottiene o imposta un identificatore univoco che rappresenta il tuo utente finale, il quale può aiutare OpenAI a monitorare e rilevare abusi. |

### Vedi anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


