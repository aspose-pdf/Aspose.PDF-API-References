---
title: "PdfExtractor.HasNextPageText"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfExtractor. Menunjukkan apakah dapat mengambil teks lebih lanjut atau tidak"
type: docs
weight: 210
url: /id/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## PdfExtractor.HasNextPageText method

Menunjukkan apakah dapat mengambil lebih banyak teks atau tidak.

```csharp
public bool HasNextPageText()
```

### Nilai Kembalian

Dapat mengambil lebih banyak teks atau tidak, true berarti dapat, atau false.

## Contoh

Contoh ini menunjukkan penggunaan properti `HasNextPageText` dalam skenario ekstraksi teks.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(TestPath + "Aspose.Pdf.Kit.Pdf")
extractor.ExtractText(Encoding.Unicode)
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### Lihat Juga

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


