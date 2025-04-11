---
title: Document.TaggedContent
second_title: Aspose.PDF for .NET API Reference
description: Properti dokumen. Mendapatkan akses ke konten TaggedPdf
type: docs
weight: 520
url: /id/net/aspose.pdf/document/taggedcontent/
---
## Properti Document.TaggedContent

Mendapatkan akses ke konten TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Contoh

Contoh ini menunjukkan cara menggunakan konten bertag untuk membuat dokumen baru dengan header, paragraf, dan gambar.

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

### Lihat Juga

* antarmuka [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* kelas [Document](../)
* ruang nama [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)