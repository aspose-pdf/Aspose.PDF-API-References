---
title: "TextAbsorber.ExtractionOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextAbsorber. Mendapatkan atau mengatur opsi ekstraksi teks."
type: docs
weight: 30
url: /id/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

Mendapatkan atau mengatur opsi ekstraksi teks.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Catatan

Memungkinkan untuk mendefinisikan mode pemformatan teks [`TextExtractionOptions`](../../textextractionoptions/) selama ekstraksi. Mode default adalah Pure.

## Contoh

Contoh ini menunjukkan cara mengatur mode pemformatan teks Pure dan melakukan ekstraksi teks.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek TextAbsorber untuk mengekstrak teks dengan pemformatan
TextAbsorber absorber = new TextAbsorber();

// atur mode pemformatan teks pure
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// terima absorber untuk semua halaman dokumen
doc.Pages.Accept(absorber);

// dapatkan teks yang diekstrak
string extractedText = absorber.Text;
```

### Lihat Juga

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


