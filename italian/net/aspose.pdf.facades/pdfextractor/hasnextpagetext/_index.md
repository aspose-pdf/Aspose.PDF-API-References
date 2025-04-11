---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfExtractor. Indica che se possono ottenere ulteriori testi o meno.
type: docs
weight: 210
url: /it/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## Metodo PdfExtractor.HasNextPageText

Indica se è possibile ottenere più testi o meno.

```csharp
public bool HasNextPageText()
```

### Valore di Ritorno

È possibile ottenere più testi o meno, true significa che è possibile, o false.

## Esempi

L'esempio dimostra l'uso della proprietà `HasNextPageText` nello scenario di estrazione del testo.

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

### Vedi Anche

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)