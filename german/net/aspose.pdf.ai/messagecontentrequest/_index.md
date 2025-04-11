---
title: Class MessageContentRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.MessageContentRequest-Klasse. Der Inhalt der Nachricht in einem Array von Text und/oder Bildern
type: docs
weight: 780
url: /de/net/aspose.pdf.ai/messagecontentrequest/
---
## Klasse MessageContentRequest

Der Inhalt der Nachricht in einem Array von Text und/oder Bildern.

```csharp
public class MessageContentRequest : MessageContentBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MessageContentRequest](messagecontentrequest/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ImageFile](../../aspose.pdf.ai/messagecontentbase/imagefile/) { get; set; } | Ruft eine Bilddatei im Inhalt einer Nachricht ab oder legt sie fest. |
| [ImageUrl](../../aspose.pdf.ai/messagecontentbase/imageurl/) { get; set; } | Ruft eine Bild-URL im Inhalt einer Nachricht ab oder legt sie fest. |
| [MessageContentType](../../aspose.pdf.ai/messagecontentbase/messagecontenttype/) { get; set; } | Ruft den Typ des Inhalts ab oder legt ihn fest. |
| [Text](../../aspose.pdf.ai/messagecontentrequest/text/) { get; set; } | Ruft den Textinhalt ab oder legt ihn fest, der Teil einer Nachricht ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateImageFileContent](../../aspose.pdf.ai/messagecontentrequest/createimagefilecontent/)(string, string) | Erstellt einen Bilddateiinhalt für eine Nachricht. |
| static [CreateImageUrlContent](../../aspose.pdf.ai/messagecontentrequest/createimageurlcontent/)(string, string) | Erstellt einen Bild-URL-Inhalt für eine Nachricht. |
| static [CreateTextContent](../../aspose.pdf.ai/messagecontentrequest/createtextcontent/)(string) | Erstellt einen Textinhalt für eine Nachricht. |

### Siehe auch

* Klasse [MessageContentBase](../messagecontentbase/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)