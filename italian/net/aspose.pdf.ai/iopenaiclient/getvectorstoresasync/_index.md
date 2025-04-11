---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera un elenco di negozi di vettori in modo asincrono
type: docs
weight: 350
url: /it/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## Metodo IOpenAIClient.GetVectorStoresAsync

Recupera un elenco di negozi di vettori in modo asincrono.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Parametri di query opzionali per filtrare l'elenco dei negozi di vettori. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene un elenco di negozi di vettori.

### Vedi Anche

* classe [VectorStoreListResponse](../../vectorstorelistresponse/)
* classe [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)