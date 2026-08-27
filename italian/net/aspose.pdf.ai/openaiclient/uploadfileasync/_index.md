---
title: "OpenAIClient.UploadFileAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Carica un file in modo asincrono sul server OpenAI"
type: docs
weight: 460
url: /it/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## OpenAIClient.UploadFileAsync method

Carica un file in modo asincrono sul server OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| purpose | String | Lo scopo del caricamento del file, tipicamente descrivendo come il file verrà utilizzato. |
| fileName | String | Il nome del file da caricare. |
| fileBytes | Byte[] | L'array di byte contenente i dati del file. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dal caricamento del file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando lo scopo del file è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generato quando il nome del file è nullo o vuoto. |

### Vedi anche

* class [FileResponse](../../fileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


