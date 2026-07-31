---
title: "PdfExtractor.ExtractTextMode"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti PdfExtractor. Menetapkan mode untuk hasil ekstraksi teks."
type: docs
weight: 40
url: /id/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

Mengatur mode untuk hasil ekstraksi teks.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


