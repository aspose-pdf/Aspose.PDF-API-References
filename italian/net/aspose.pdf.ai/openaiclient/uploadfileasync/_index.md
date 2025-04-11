---
title: OpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Carica un file in modo asincrono sul server OpenAI
type: docs
weight: 450
url: /it/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## Metodo OpenAIClient.UploadFileAsync

Carica un file in modo asincrono sul server OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| purpose | String | Lo scopo del caricamento del file, tipicamente descrivendo come verrà utilizzato il file. |
| fileName | String | Il nome del file da caricare. |
| fileBytes | Byte[] | L'array di byte contenente i dati del file. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dal caricamento del file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando lo scopo del file è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando il nome del file è nullo o vuoto. |

### Vedi Anche

* classe [FileResponse](../../fileresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)