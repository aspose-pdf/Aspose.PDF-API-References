---
title: IOpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Ruft eine Liste von Dateien asynchron basierend auf dem angegebenen Zweck ab
type: docs
weight: 220
url: /de/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## IOpenAIClient.GetFilesAsync-Methode

Ruft eine Liste von Dateien asynchron basierend auf dem angegebenen Zweck ab.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| purpose | String | Optional. Der Zweck der abzurufenden Dateien. Wenn null, werden Dateien für alle Zwecke abgerufen. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält eine Liste von Dateien.

### Siehe auch

* Klasse [FileListResponse](../../filelistresponse/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)