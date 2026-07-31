---
title: "OpenAIClient.CreateVectorStoreFileBatchAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Crea un nuovo batch di file di archivio vettoriale in modo asincrono"
type: docs
weight: 120
url: /it/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## OpenAIClient.CreateVectorStoreFileBatchAsync method

Crea un nuovo batch di file di archivio vettoriale in modo asincrono.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale in cui verrà creato il batch di file. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | L'oggetto di richiesta contenente i dettagli per creare il batch di file. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione del batch di file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del vector store è nullo o vuoto. |

### Vedi anche

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


