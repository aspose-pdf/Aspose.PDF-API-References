---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Indica si se pueden obtener más textos o no
type: docs
weight: 210
url: /es/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## Método PdfExtractor.HasNextPageText

Indica si se pueden obtener más textos o no.

```csharp
public bool HasNextPageText()
```

### Valor de Retorno

Se pueden obtener más textos o no, verdadero significa que se puede, o falso.

## Ejemplos

El ejemplo demuestra el uso de la propiedad `HasNextPageText` en un escenario de extracción de texto.

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

### Véase También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)