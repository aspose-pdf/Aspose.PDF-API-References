---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateChatCompletionChunkResponse-Klasse. Stellt einen gestreamten Chunk einer Chat-Vervollständigungsantwort dar, die vom Modell basierend auf der bereitgestellten Eingabe zurückgegeben wird.
type: docs
weight: 250
url: /de/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## Klasse CreateChatCompletionChunkResponse

Stellt einen gestreamten Chunk einer Chat-Vervollständigungsantwort dar, die vom Modell basierend auf der bereitgestellten Eingabe zurückgegeben wird.

```csharp
public class CreateChatCompletionChunkResponse
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Ruft eine Liste von Chat-Vervollständigungsoptionen ab oder legt sie fest. Kann mehr als ein Element enthalten, wenn n größer als 1 ist. Kann auch leer sein für den letzten Chunk, wenn Sie stream_options: {"include_usage": true} festlegen. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann die Chat-Vervollständigung erstellt wurde. Jeder Chunk hat denselben Zeitstempel. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Ruft eine eindeutige Kennung für die Chat-Vervollständigung ab oder legt sie fest. Jeder Chunk hat dieselbe ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Ruft das Modell ab oder legt es fest, um die Vervollständigung zu generieren. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer chat.completion.chunk ist. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Ruft den Fingerabdruck ab oder legt ihn fest, der die Backend-Konfiguration darstellt, mit der das Modell läuft. Kann in Verbindung mit dem Seed-Anforderungsparameter verwendet werden, um zu verstehen, wann Backend-Änderungen vorgenommen wurden, die die Determinismus beeinflussen könnten. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Ruft ein optionales Feld ab oder legt es fest, das nur vorhanden ist, wenn Sie stream_options: {"include_usage": true} in Ihrer Anfrage festlegen. Wenn vorhanden, enthält es einen Nullwert, außer für den letzten Chunk, der die Token-Nutzungsstatistiken für die gesamte Anfrage enthält. |

### Siehe auch

* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)