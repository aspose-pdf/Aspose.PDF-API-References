---
title: "IOpenAIClient.CreateVectorStoreFileAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Skapar en ny vektorlagringsfil asynkront"
type: docs
weight: 110
url: /sv/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## IOpenAIClient.CreateVectorStoreFileAsync method

Skapar en ny vektorlagerfil asynkront.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID för vektorlager där filen kommer att skapas. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Begäranobjektet som innehåller detaljer för att skapa filen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från filskapandet.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |

### Se även

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


