---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Properti TextAbsorber. Mengambil atau mengatur opsi ekstraksi teks
type: docs
weight: 30
url: /id/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## Properti TextAbsorber.OpsiEkstraksi

Mengambil atau mengatur opsi ekstraksi teks.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Catatan

Memungkinkan untuk mendefinisikan mode pemformatan teks [`TextExtractionOptions`](../../textextractionoptions/) selama ekstraksi. Mode default adalah Pure

## Contoh

Contoh ini menunjukkan cara mengatur mode pemformatan teks Pure dan melakukan ekstraksi teks.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### Lihat Juga

* kelas [TextExtractionOptions](../../textextractionoptions/)
* kelas [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)