---
title: "Document.TaggedContent"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document-egenskap. Hämtar åtkomst till TaggedPdf-innehåll."
type: docs
weight: 540
url: /sv/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

Hämtar åtkomst till TaggedPdf-innehåll.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Exempel

Exemplet visar hur man använder taggat innehåll för att skapa ett nytt dokument med rubrik, stycken och bilder.

```csharp
// Skapa nytt dokument
Document document = new Document();

// Hämta det taggade innehållet
ITaggedContent taggedContent = document.TaggedContent;

// Ange språk för dokumentet
taggedContent.SetLanguage("en-US");

// Ange titel för PDF-dokument
taggedContent.SetTitle("Example document");

// Skapa och lägga till avsnitt
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Skapa rubrik
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Skapa stycke
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Skapa illustration
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Spara dokument
document.Save("example.pdf");
```

### Se även

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


