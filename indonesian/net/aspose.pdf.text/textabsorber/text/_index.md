---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: Properti TextAbsorber. Mendapatkan teks yang diekstrak yang diekstrak oleh TextAbsorber pada dokumen atau halaman PDF
type: docs
weight: 50
url: /id/net/aspose.pdf.text/textabsorber/text/
---
## Properti TextAbsorber.Text

Mendapatkan teks yang diekstrak yang diekstrak oleh [`TextAbsorber`](../) pada dokumen atau halaman PDF.

```csharp
public virtual string Text { get; }
```

## Contoh

Contoh ini menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Lihat Juga

* kelas [TextAbsorber](../)
* ruang nama [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)