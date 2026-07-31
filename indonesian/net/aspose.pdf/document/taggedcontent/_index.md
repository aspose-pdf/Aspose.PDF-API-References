---
title: "Document.TaggedContent"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Document properti. Mendapatkan akses ke konten TaggedPdf."
type: docs
weight: 540
url: /id/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

Mendapatkan akses ke konten TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Contoh

Contoh ini menunjukkan cara menggunakan konten bertag untuk membuat dokumen baru dengan header, paragraf, dan gambar.

```csharp
// Buat dokumen baru
Document document = new Document();

// Dapatkan konten yang ditandai
ITaggedContent taggedContent = document.TaggedContent;

// Atur bahasa untuk dokumen
taggedContent.SetLanguage("en-US");

// Atur judul untuk dokumen PDF
taggedContent.SetTitle("Example document");

// Membuat dan menambahkan Section
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Buat Header
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Buat paragraf
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Buat ilustrasi
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Simpan dokumen
document.Save("example.pdf");
```

### Lihat Juga

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


