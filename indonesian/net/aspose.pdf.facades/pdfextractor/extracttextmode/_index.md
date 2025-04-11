---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: Properti PdfExtractor. Mengatur mode untuk hasil ekstraksi teks
type: docs
weight: 40
url: /id/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## Properti PdfExtractor.ExtractTextMode

Mengatur mode untuk hasil ekstraksi teks.

```csharp
public int ExtractTextMode { get; set; }
```

### Nilai Properti

0 adalah mode teks murni dan 1 adalah mode urutan mentah. Default adalah 0.

## Contoh

Contoh ini menunjukkan penggunaan properti `ExtractTextMode` dalam skenario ekstraksi teks.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Lihat Juga

* kelas [PdfExtractor](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)