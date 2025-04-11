---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Indica se é possível obter mais textos ou não
type: docs
weight: 210
url: /pt/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## Método PdfExtractor.HasNextPageText

Indica se é possível obter mais textos ou não.

```csharp
public bool HasNextPageText()
```

### Valor de Retorno

Se é possível obter mais textos ou não, verdadeiro significa que sim, ou falso.

## Exemplos

O exemplo demonstra o uso da propriedade `HasNextPageText` em um cenário de extração de texto.

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

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)