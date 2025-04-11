---
title: IOpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea un nuovo file di archiviazione vettoriale in modo asincrono
type: docs
weight: 110
url: /it/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## Metodo IOpenAIClient.CreateVectorStoreFileAsync

Crea un nuovo file di archiviazione vettoriale in modo asincrono.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale in cui verrà creato il file. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | L'oggetto di richiesta contenente i dettagli per la creazione del file. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione del file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'archivio vettoriale è nullo o vuoto. |

### Vedi anche

* classe [VectorStoreFileResponse](../../vectorstorefileresponse/)
* classe [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)