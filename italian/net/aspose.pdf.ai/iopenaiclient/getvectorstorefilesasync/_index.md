---
title: "IOpenAIClient.GetVectorStoreFilesAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "IOpenAIClient metodo. Recupera un elenco di file all'interno di un archivio vettoriale specifico in modo asincrono"
type: docs
weight: 340
url: /it/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## IOpenAIClient.GetVectorStoreFilesAsync method

Recupera un elenco di file all'interno di un archivio vettoriale specifico in modo asincrono.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale contenente i file. |
| queryParameters | VectorStoreFileListQueryParameters | Parametri di query opzionali per filtrare l'elenco dei file. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene un elenco di file all'interno dell'archivio vettoriale.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del vector store è nullo o vuoto. |

### Vedi anche

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


