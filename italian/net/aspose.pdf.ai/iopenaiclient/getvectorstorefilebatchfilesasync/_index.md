---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodo. Recupera una lista di file all'interno di un batch specifico del file del vector store in modo asincrono.
type: docs
weight: 330
url: /it/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## Metodo IOpenAIClient.GetVectorStoreFileBatchFilesAsync

Recupera un elenco di file all'interno di un batch di file di archiviazione vettoriale specifico in modo asincrono.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale contenente il batch di file. |
| fileBatchId | String | L'ID del batch di file da cui recuperare i file. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Parametri di query facoltativi per filtrare l'elenco dei file. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene un elenco di file all'interno del batch di file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'archivio vettoriale è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del batch di file dell'archivio vettoriale è nullo o vuoto. |

### Vedi anche

* classe [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* classe [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)