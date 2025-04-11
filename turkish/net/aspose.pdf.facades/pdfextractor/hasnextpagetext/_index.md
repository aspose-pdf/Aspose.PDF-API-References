---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor metodu. Daha fazla metin alınıp alınamayacağını belirtir
type: docs
weight: 210
url: /tr/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## PdfExtractor.HasNextPageText metodu

Daha fazla metin alınıp alınamayacağını belirtir.

```csharp
public bool HasNextPageText()
```

### Dönüş Değeri

Daha fazla metin alınıp alınamayacağını belirtir, true alabiliyor, false ise alamıyor.

## Örnekler

Örnek, `HasNextPageText` özelliğinin metin çıkarım senaryosundaki kullanımını göstermektedir.

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

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)