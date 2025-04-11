---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Laddar upp en fil asynkront till OpenAI-servern
type: docs
weight: 420
url: /sv/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync metod

Laddar upp en fil asynkront till OpenAI-servern.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| purpose | Sträng | Syftet med filuppladdningen, som vanligtvis beskriver hur filen kommer att användas. |
| fileName | Sträng | Namnet på filen som ska laddas upp. |
| fileBytes | Byte[] | Byte-array som innehåller filens data. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från filuppladdningen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när filens syfte är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när filnamnet är null eller tomt. |

### Se Även

* klass [FileResponse](../../fileresponse/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)