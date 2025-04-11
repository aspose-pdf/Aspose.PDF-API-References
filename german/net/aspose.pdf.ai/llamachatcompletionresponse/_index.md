---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaChatCompletionResponse-Klasse. Stellt eine Chat-Vervollständigungsantwort dar, die vom Modell basierend auf der bereitgestellten Eingabe zurückgegeben wird
type: docs
weight: 690
url: /de/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse-Klasse

Stellt eine Chat-Vervollständigungsantwort dar, die vom Modell basierend auf der bereitgestellten Eingabe zurückgegeben wird.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | Ruft eine Liste von Chat-Vervollständigungsoptionen ab oder legt sie fest. Kann mehr als eine sein, wenn n größer als 1 ist. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann die Chat-Vervollständigung erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder legt sie fest. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder legt ihn fest. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder legt sie fest. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder legt sie fest. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder legt ihn fest. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Ruft einen eindeutigen Bezeichner für die Chat-Vervollständigung ab oder legt ihn fest. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Ruft das Modell ab oder legt es fest, das für die Chat-Vervollständigung verwendet wird. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer chat.completion ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Ruft den Fingerabdruck ab oder legt ihn fest, der die Backend-Konfiguration darstellt, mit der das Modell läuft. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Ruft die Nutzungsstatistiken für die Vervollständigungsanfrage ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Gibt eine Zeichenfolgenrepräsentation der ersten Wahl zurück. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)