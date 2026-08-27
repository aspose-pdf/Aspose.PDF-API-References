---
title: "PdfExtractor.HasNextPageText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor‑metod. Anger om fler texter kan hämtas eller inte"
type: docs
weight: 210
url: /sv/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## PdfExtractor.HasNextPageText method

Indikerar om fler texter kan hämtas eller inte.

```csharp
public bool HasNextPageText()
```

### Returvärde

Kan hämta fler texter eller inte, sant betyder kan, falskt betyder kan inte.

## Exempel

Exemplet demonstrerar hur egenskapen `HasNextPageText` används i ett textutvinningsscenario.

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

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


