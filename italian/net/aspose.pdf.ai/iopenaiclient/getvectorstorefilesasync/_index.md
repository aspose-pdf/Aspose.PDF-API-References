---
title: IOpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera un elenco di file all'interno di uno specifico archivio vettoriale in modo asincrono
type: docs
weight: 340
url: /it/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## Metodo IOpenAIClient.GetVectorStoreFilesAsync

Recupera un elenco di file all'interno di uno specifico archivio vettoriale in modo asincrono.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale contenente i file. |
| queryParameters | VectorStoreFileListQueryParameters | Parametri di query facoltativi per filtrare l'elenco dei file. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene un elenco di file all'interno dell'archivio vettoriale.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'archivio vettoriale è nullo o vuoto. |

### Vedi Anche

* classe [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* classe [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)