---
title: "IOpenAIClient.CreateVectorStoreFileBatchAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IOpenAIClient metod. Skapar en ny batch av vektorlagringsfiler asynkront"
type: docs
weight: 120
url: /sv/net/aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/
---
## IOpenAIClient.CreateVectorStoreFileBatchAsync method

Skapar en ny batch av vektorlagerfiler asynkront.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorStoreId | String | ID:t för vektorbutiken där filbatchen kommer att skapas. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | Begäranobjektet som innehåller detaljer för att skapa filbatchen. |
| cancellationToken | Nullable`1 | En token för att avbryta operationen. |

### Returvärde

En uppgift som representerar den asynkrona operationen. Uppgiftsresultatet innehåller svaret från skapandet av filbatchen.

### Undantag

| undantag | villkor |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Kastas när vektorlager-ID är null eller tomt. |

### Se även

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


