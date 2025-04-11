---
title: IOpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Löscht einen Vektorstore asynchron
type: docs
weight: 170
url: /de/net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## IOpenAIClient.DeleteVectorStoreAsync-Methode

Löscht einen Vektorstore asynchron.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des zu löschenden Vektorstores. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält den Status der Löschoperation.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorstore-ID null oder leer ist. |

### Siehe auch

* Klasse [DeleteStatusResponse](../../deletestatusresponse/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)