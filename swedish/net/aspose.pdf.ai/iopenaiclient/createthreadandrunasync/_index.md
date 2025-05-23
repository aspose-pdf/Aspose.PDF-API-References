---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Skapar en tråd och en körning inom den asynkront
type: docs
weight: 60
url: /sv/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## IOpenAIClient.CreateThreadAndRunAsync metod

Skapar en tråd och en körning inom den asynkront.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Begärningsdetaljer för att skapa tråden och körningen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från skapandet av tråden och körningen.

### Se Även

* klass [RunResponse](../../runresponse/)
* klass [RunThreadCreateRequest](../../runthreadcreaterequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../../)