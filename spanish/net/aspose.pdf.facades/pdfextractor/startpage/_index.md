---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfExtractor. Obtiene o establece la página de inicio en el rango de páginas donde se realizará la operación de extracción
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/pdfextractor/startpage/
---
## Propiedad PdfExtractor.StartPage

Obtiene o establece la página de inicio en el rango de páginas donde se realizará la operación de extracción.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)