---
title: OpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Crea un nuovo batch di file di archiviazione vettoriale in modo asincrono
type: docs
weight: 120
url: /it/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## Metodo OpenAIClient.CreateVectorStoreFileBatchAsync

Crea un nuovo batch di file di archiviazione vettoriale in modo asincrono.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale dove verrà creato il batch di file. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | L'oggetto di richiesta contenente i dettagli per la creazione del batch di file. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione del batch di file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'archivio vettoriale è nullo o vuoto. |

### Vedi anche

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* classe [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)