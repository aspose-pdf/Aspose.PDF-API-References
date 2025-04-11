---
title: OpenAIClient.GetVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Ruft Details einer bestimmten Datei innerhalb eines Vektor-Speichers asynchron ab
type: docs
weight: 340
url: /de/net/aspose.pdf.ai/openaiclient/getvectorstorefileasync/
---
## OpenAIClient.GetVectorStoreFileAsync-Methode

Ruft Details einer bestimmten Datei innerhalb eines Vektor-Speichers asynchron ab.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektor-Speichers, der die Datei enthält. |
| fileId | String | Die ID der abzurufenden Datei. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Details der Datei.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektor-Speicher-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Datei-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreFileResponse](../../vectorstorefileresponse/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)