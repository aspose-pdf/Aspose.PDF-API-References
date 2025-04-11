---
title: IOpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-metod. Skapar en ny fullföljd asynkront
type: docs
weight: 40
url: /sv/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## IOpenAIClient.CreateCompletionAsync metod

Skapar en ny fullföljd asynkront.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | Begärningsobjektet som innehåller detaljer för att skapa fullföljden. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från skapandet av fullföljden.

### Se Även

* klass [CompletionResponse](../../completionresponse/)
* klass [CompletionCreateRequest](../../completioncreaterequest/)
* gränssnitt [IOpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)