---
title: OpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Kündigt einen bestimmten Vektorstore-Dateibatch asynchron.
type: docs
weight: 20
url: /de/net/aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/
---
## OpenAIClient.CancelVectorStoreFileBatchAsync-Methode

Kündigt einen bestimmten Vektorstore-Dateibatch asynchron an.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektorstores, der den zu kündigenden Dateibatch enthält. |
| fileBatchId | String | Die ID des zu kündigenden Dateibatches. |
| cancellationToken | Nullable`1 | Ein Token zum Kündigen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort auf die Kündigung des Dateibatches.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorstore-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorstore-Dateibatch-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)