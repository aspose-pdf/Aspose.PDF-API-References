---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionResponse-Klasse. Stellt eine Chat-Vervollständigungsantwort dar, die vom Modell basierend auf den bereitgestellten Eingaben zurückgegeben wird
type: docs
weight: 240
url: /de/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse-Klasse

Stellt eine Chat-Vervollständigungsantwort dar, die vom Modell basierend auf den bereitgestellten Eingaben zurückgegeben wird.

```csharp
public class CompletionResponse : BaseResponse
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CompletionResponse](completionresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Ruft eine Liste von Chat-Vervollständigungsoptionen ab oder legt sie fest. Kann mehr als eine sein, wenn n größer als 1 ist. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann die Chat-Vervollständigung erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder legt sie fest. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder legt ihn fest. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder legt sie fest. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder legt sie fest. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder legt ihn fest. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Ruft eine eindeutige Kennung für die Chat-Vervollständigung ab oder legt sie fest. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Ruft das Modell ab oder legt es fest, das für die Chat-Vervollständigung verwendet wird. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer chat.completion ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Ruft den Fingerabdruck ab oder legt ihn fest, der die Backend-Konfiguration darstellt, mit der das Modell läuft. Kann in Verbindung mit dem Seed-Anforderungsparameter verwendet werden, um zu verstehen, wann Backend-Änderungen vorgenommen wurden, die die Deterministik beeinflussen könnten. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Ruft die Nutzungsstatistiken für die Vervollständigungsanforderung ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Gibt den Inhalt der ersten Wahl als Zeichenfolge zurück. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)