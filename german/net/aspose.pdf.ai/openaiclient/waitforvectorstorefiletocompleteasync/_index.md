---
title: OpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient-Methode. Wartet darauf, dass eine bestimmte Vektorspeicherdatei asynchron abgeschlossen wird
type: docs
weight: 490
url: /de/net/aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/
---
## OpenAIClient.WaitForVectorStoreFileToCompleteAsync-Methode

Wartet darauf, dass eine bestimmte Vektorspeicherdatei asynchron abgeschlossen wird.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorStoreId | String | Die ID des Vektorspeichers, der die Datei enthält. |
| fileId | String | Die ID der Datei, die bis zum Abschluss überwacht werden soll. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält den endgültigen Status der Datei.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Vektorspeicher-ID null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn die Datei-ID null oder leer ist. |

### Siehe auch

* Klasse [VectorStoreFileResponse](../../vectorstorefileresponse/)
* Klasse [OpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)