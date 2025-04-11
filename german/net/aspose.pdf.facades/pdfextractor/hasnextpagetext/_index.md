---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-Methode. Gibt an, ob weitere Texte abgerufen werden können oder nicht
type: docs
weight: 210
url: /de/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## PdfExtractor.HasNextPageText-Methode

Gibt an, ob weitere Texte abgerufen werden können oder nicht.

```csharp
public bool HasNextPageText()
```

### Rückgabewert

Kann weitere Texte abgerufen werden oder nicht, true bedeutet, dass es möglich ist, oder false.

## Beispiele

Das Beispiel demonstriert die Verwendung der `HasNextPageText`-Eigenschaft im Szenario der Textextraktion.

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

### Siehe auch

* Klasse [PdfExtractor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)