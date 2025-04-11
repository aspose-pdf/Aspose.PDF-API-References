---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfExtractor. Establece el modo para el resultado de extracción de textos
type: docs
weight: 40
url: /es/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## Propiedad PdfExtractor.ExtractTextMode

Establece el modo para el resultado de extracción de texto.

```csharp
public int ExtractTextMode { get; set; }
```

### Valor de la Propiedad

0 es modo de texto puro y 1 es modo de ordenación cruda. El valor predeterminado es 0.

## Ejemplos

El ejemplo demuestra el uso de la propiedad `ExtractTextMode` en un escenario de extracción de texto.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)