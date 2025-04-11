---
title: OpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Recupera i dettagli di uno specifico store vettoriale in modo asincrono
type: docs
weight: 330
url: /it/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## Metodo OpenAIClient.GetVectorStoreAsync

Recupera i dettagli di uno specifico store vettoriale in modo asincrono.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dello store vettoriale da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli dello store vettoriale.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dello store vettoriale è nullo o vuoto. |

### Vedi Anche

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)