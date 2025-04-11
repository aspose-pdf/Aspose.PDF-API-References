---
title: OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Erstellt einen neuen Vektorstore und wartet, bis er asynchron abgeschlossen ist
type: docs
weight: 90
url: /de/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync-Methode

Erstellt einen neuen Vektorstore und wartet, bis er asynchron abgeschlossen ist.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Das Anforderungsobjekt, das Details zum Erstellen des Vektorstores enthält. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Erstellung des Vektorstores nach Abschluss.

### Siehe auch

* Klasse [VectorStoreResponse](../../vectorstoreresponse/)
* Klasse [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)