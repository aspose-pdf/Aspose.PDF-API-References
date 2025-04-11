---
title: IOpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Erstellt eine neue Vektorstore-Datei asynchron
type: docs
weight: 110
url: /de/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## IOpenAIClient.CreateVectorStoreFileAsync-Methode

Erstellt eine neue Vektorstore-Datei asynchron.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektorstores, in dem die Datei erstellt wird. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Das Anforderungsobjekt, das Details zur Erstellung der Datei enthält. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Dateierstellung.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorstore-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreFileResponse](../../vectorstorefileresponse/)
* Klasse [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)