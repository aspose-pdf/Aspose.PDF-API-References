---
title: IOpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodo. Recupera dettagli di un file specifico in modo asincrono.
type: docs
weight: 210
url: /it/net/aspose.pdf.ai/iopenaiclient/getfileasync/
---
## Metodo IOpenAIClient.GetFileAsync

Recupera i dettagli di un file specifico in modo asincrono.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileId | String | L'ID del file da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del file è nullo o vuoto. |

### Vedi Anche

* classe [FileResponse](../../fileresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)