---
title: OpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-metod. Skapar en ny vektorbutiksfil asynkront
type: docs
weight: 110
url: /sv/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## OpenAIClient.CreateVectorStoreFileAsync metod

Skapar en ny vektorbutiksfil asynkront.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | Sträng | ID för vektorbutiken där filen kommer att skapas. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Begärningsobjektet som innehåller detaljer för att skapa filen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från filskapandet.

### Undantag

| undantag | tillstånd |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Utlöses när vektorbutiks-ID:t är null eller tomt. |

### Se Även

* klass [VectorStoreFileResponse](../../vectorstorefileresponse/)
* klass [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* klass [OpenAIClient](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)