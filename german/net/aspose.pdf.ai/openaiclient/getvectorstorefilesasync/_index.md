---
title: OpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Ruft eine Liste von Dateien innerhalb eines bestimmten Vektor-Speichers asynchron ab
type: docs
weight: 370
url: /de/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/
---
## OpenAIClient.GetVectorStoreFilesAsync-Methode

Ruft eine Liste von Dateien innerhalb eines bestimmten Vektor-Speichers asynchron ab.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektor-Speichers, der die Dateien enthält. |
| queryParameters | VectorStoreFileListQueryParameters | Optionale Abfrageparameter zur Filterung der Liste von Dateien. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält eine Liste von Dateien innerhalb des Vektor-Speichers.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektor-Speicher-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* Klasse [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)