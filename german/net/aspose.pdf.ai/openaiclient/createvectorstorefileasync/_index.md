---
title: OpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Erstellt eine neue Vektorspeicherdatei asynchron
type: docs
weight: 110
url: /de/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## OpenAIClient.CreateVectorStoreFileAsync-Methode

Erstellt eine neue Vektorspeicherdatei asynchron.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektorspeichers, in dem die Datei erstellt wird. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Das Anforderungsobjekt, das Details zur Erstellung der Datei enthält. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort von der Dateierstellung.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorspeicher-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreFileResponse](../../vectorstorefileresponse/)
* Klasse [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)