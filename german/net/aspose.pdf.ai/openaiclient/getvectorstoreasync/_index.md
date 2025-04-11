---
title: OpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Ruft Details eines bestimmten Vektor-Speichers asynchron ab
type: docs
weight: 330
url: /de/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## OpenAIClient.GetVectorStoreAsync-Methode

Ruft Details eines bestimmten Vektor-Speichers asynchron ab.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektor-Speichers, der abgerufen werden soll. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Details des Vektor-Speichers.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektor-Speicher-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreResponse](../../vectorstoreresponse/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)