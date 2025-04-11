---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-metod. Indikerar om det går att få mer text eller inte
type: docs
weight: 210
url: /sv/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## PdfExtractor.HasNextPageText metod

Indikerar om det går att få mer text eller inte.

```csharp
public bool HasNextPageText()
```

### Returvärde

Kan få mer text eller inte, true betyder att det går, eller false.

## Exempel

Exemplet visar användningen av `HasNextPageText`-egenskapen i ett textutvinningsscenario.

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

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)