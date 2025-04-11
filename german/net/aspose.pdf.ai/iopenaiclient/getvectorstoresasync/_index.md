---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Ruft eine Liste von Vektor-Speichern asynchron ab
type: docs
weight: 350
url: /de/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync-Methode

Ruft eine Liste von Vektor-Speichern asynchron ab.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Optionale Abfrageparameter zum Filtern der Liste von Vektor-Speichern. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält eine Liste von Vektor-Speichern.

### Siehe auch

* Klasse [VectorStoreListResponse](../../vectorstorelistresponse/)
* Klasse [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)