---
title: IOpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Tar bort en fil inom en vektorbutik asynkront
type: docs
weight: 180
url: /sv/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/
---
## IOpenAIClient.DeleteVectorStoreFileAsync metod

Tar bort en fil inom en vektorbutik asynkront.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID:t för vektorbutiken som innehåller filen som ska tas bort. |
| fileId | Sträng | ID:t för filen som ska tas bort. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller statusen för borttagningsoperationen.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutikens ID är null eller tomt. |
| [AIClientException](../../aiclientexception/) | Utlöses när filens ID är null eller tomt. |

### Se Även

* klass [DeleteStatusResponse](../../deletestatusresponse/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)