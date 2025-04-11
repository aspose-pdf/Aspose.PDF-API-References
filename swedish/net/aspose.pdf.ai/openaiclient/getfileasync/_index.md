---
title: OpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Hämtar detaljer om en specifik fil asynkront
type: docs
weight: 220
url: /sv/net/aspose.pdf.ai/openaiclient/getfileasync/
---
## OpenAIClient.GetFileAsync metod

Hämtar detaljer om en specifik fil asynkront.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileId | Sträng | ID:t för filen som ska hämtas. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller detaljerna om filen.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när fil-ID:t är null eller tomt. |

### Se Även

* klass [FileResponse](../../fileresponse/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)