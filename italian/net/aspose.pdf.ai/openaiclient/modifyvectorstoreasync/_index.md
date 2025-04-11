---
title: OpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Modifica un archivio vettoriale esistente in modo asincrono
type: docs
weight: 430
url: /it/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## Metodo OpenAIClient.ModifyVectorStoreAsync

Modifica un archivio vettoriale esistente in modo asincrono.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale da modificare. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | L'oggetto di richiesta contenente i dettagli della modifica. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla modifica dell'archivio vettoriale.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'archivio vettoriale è nullo o vuoto. |

### Vedi Anche

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)