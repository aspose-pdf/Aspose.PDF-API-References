---
title: "TextAbsorber.Text"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextAbsorber. Mendapatkan teks yang diekstrak oleh TextAbsorber pada dokumen PDF atau halaman."
type: docs
weight: 50
url: /id/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

Mendapatkan teks yang diekstrak oleh [`TextAbsorber`](../) pada dokumen PDF atau halaman.

```csharp
public virtual string Text { get; }
```

## Contoh

Contoh ini menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek TextAbsorber untuk mengekstrak teks
TextAbsorber absorber = new TextAbsorber();

// terima absorber untuk semua halaman dokumen
doc.Pages.Accept(absorber);

// dapatkan teks yang diekstrak
string extractedText = absorber.Text;

```

### Lihat Juga

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


