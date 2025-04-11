---
title: IOpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Modifiziert einen vorhandenen Vektorstore asynchron
type: docs
weight: 400
url: /de/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## IOpenAIClient.ModifyVectorStoreAsync-Methode

Modifiziert einen vorhandenen Vektorstore asynchron.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des zu modifizierenden Vektorstores. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | Das Anforderungsobjekt, das die Änderungsdetails enthält. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Vektorstore-Modifikation.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorstore-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreResponse](../../vectorstoreresponse/)
* Klasse [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)