---
title: Document.TaggedContent
second_title: Aspose.PDF for .NET API Reference
description: Dokumenteigenschaft. Ermöglicht den Zugriff auf TaggedPdf-Inhalt
type: docs
weight: 520
url: /de/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent-Eigenschaft

Ermöglicht den Zugriff auf TaggedPdf-Inhalt.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Beispiele

Das Beispiel zeigt, wie man getaggten Inhalt verwendet, um ein neues Dokument mit Kopfzeile, Absätzen und Bildern zu erstellen.

```csharp
// Create new document
Document document = new Document();

// Get the tagged content
ITaggedContent taggedContent = document.TaggedContent;

// Set language for document
taggedContent.SetLanguage("en-US");

// Set title for PDF document
taggedContent.SetTitle("Example document");

// Creating and adding Section
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Create Header
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Create paragraph
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Create illustration
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Save document
document.Save("example.pdf");
```

### Siehe auch

* Schnittstelle [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)