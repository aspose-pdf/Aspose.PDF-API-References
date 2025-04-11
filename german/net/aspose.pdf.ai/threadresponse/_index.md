---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadResponse-Klasse. Stellt einen Thread dar, der Nachrichten enthält
type: docs
weight: 1180
url: /de/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse-Klasse

Stellt einen Thread dar, der Nachrichten enthält.

```csharp
public class ThreadResponse : BaseResponse
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ThreadResponse](threadresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Thread erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder legt sie fest. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder legt ihn fest. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder legt sie fest. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder legt sie fest. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder legt ihn fest. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Ruft den Bezeichner ab oder legt ihn fest, der in API-Endpunkten referenziert werden kann. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Ruft ein Set von 16 Schlüssel-Wert-Paaren ab oder legt es fest, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer Thread ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Ruft ein Set von Ressourcen ab oder legt es fest, die den Werkzeugen des Assistenten in diesem Thread zur Verfügung gestellt werden. Die Ressourcen sind spezifisch für den Typ des Werkzeugs. Zum Beispiel benötigt das Werkzeug code_interpreter eine Liste von Datei-IDs, während das Werkzeug file_search eine Liste von Vektor-Store-IDs benötigt. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)