---
title: OpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Ruft eine Liste von Dateien innerhalb eines bestimmten Vektorstore-Dateibatchs asynchron ab
type: docs
weight: 360
url: /de/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/
---
## OpenAIClient.GetVectorStoreFileBatchFilesAsync-Methode

Ruft eine Liste von Dateien innerhalb eines bestimmten Vektorstore-Dateibatchs asynchron ab.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektorstores, der den Dateibatch enthält. |
| fileBatchId | String | Die ID des Dateibatchs, aus dem Dateien abgerufen werden sollen. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Optionale Abfrageparameter zur Filterung der Liste von Dateien. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält eine Liste von Dateien innerhalb des Dateibatchs.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorstore-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorstore-Dateibatch-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* Klasse [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)