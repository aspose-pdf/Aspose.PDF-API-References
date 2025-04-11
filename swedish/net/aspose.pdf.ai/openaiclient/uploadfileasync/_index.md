---
title: OpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Laddar upp en fil asynkront till OpenAI-servern
type: docs
weight: 450
url: /sv/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## OpenAIClient.UploadFileAsync metod

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

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när filens syfte är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när filnamnet är null eller tomt. |

### Se Även

* klass [FileResponse](../../fileresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)