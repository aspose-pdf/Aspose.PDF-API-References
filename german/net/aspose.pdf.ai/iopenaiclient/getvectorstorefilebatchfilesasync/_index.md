---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Ruft eine Liste von Dateien innerhalb eines bestimmten Vektorstore-Dateibatches asynchron ab
type: docs
weight: 330
url: /de/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync-Methode

Ruft eine Liste von Dateien innerhalb eines bestimmten Vektorstore-Dateibatches asynchron ab.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektorstores, der den Dateibatch enthält. |
| fileBatchId | String | Die ID des Dateibatches, aus dem Dateien abgerufen werden sollen. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Optionale Abfrageparameter zur Filterung der Liste von Dateien. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält eine Liste von Dateien innerhalb des Dateibatches.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorstore-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die ID des Vektorstore-Dateibatches null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* Klasse [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)