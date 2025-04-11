---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient-Methode. Lädt eine Datei asynchron auf den OpenAI-Server hoch
type: docs
weight: 420
url: /de/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync-Methode

Lädt eine Datei asynchron auf den OpenAI-Server hoch.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| purpose | String | Der Zweck des Datei-Uploads, der typischerweise beschreibt, wie die Datei verwendet wird. |
| fileName | String | Der Name der hochzuladenden Datei. |
| fileBytes | Byte[] | Das Byte-Array, das die Dateidaten enthält. |
| cancellationToken | Nullable`1 | Ein Token zum Abbrechen der Operation. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Operation darstellt. Das Ergebnis der Aufgabe enthält die Antwort vom Datei-Upload.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn der Dateizweck null oder leer ist. |
| [AIClientException](../../aiclientexception/) | Wird ausgelöst, wenn der Dateiname null oder leer ist. |

### Siehe auch

* Klasse [FileResponse](../../fileresponse/)
* Schnittstelle [IOpenAIClient](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)