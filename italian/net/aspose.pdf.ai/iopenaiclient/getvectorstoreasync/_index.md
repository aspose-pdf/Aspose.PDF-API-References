---
title: IOpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera i dettagli di uno specifico store di vettori in modo asincrono
type: docs
weight: 300
url: /it/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## Metodo IOpenAIClient.GetVectorStoreAsync

Recupera i dettagli di uno specifico store di vettori in modo asincrono.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dello store di vettori da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli dello store di vettori.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dello store di vettori è nullo o vuoto. |

### Vedi Anche

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)