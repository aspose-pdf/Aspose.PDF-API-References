---
title: "OpenAIClient.WaitForVectorStoreFileToCompleteAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OpenAIClient‑metod. Väntar på att en specifik vektorlagerfil ska slutföras asynkront"
type: docs
weight: 500
url: /sv/net/aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/
---
## OpenAIClient.WaitForVectorStoreFileToCompleteAsync method

Väntar asynkront på att en specifik vektorlagerfil ska slutföras.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vektorlager som innehåller filen. |
| fileId | String | ID‑t för filen som ska övervakas tills den är slutförd. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller filens slutgiltiga status.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Kastas när fil‑ID är null eller tomt. |

### Se även

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


