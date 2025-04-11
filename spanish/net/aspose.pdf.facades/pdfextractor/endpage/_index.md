---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfExtractor. Obtiene o establece la página final en el rango de páginas donde se realizará la operación de extracción
type: docs
weight: 20
url: /es/net/aspose.pdf.facades/pdfextractor/endpage/
---
## Propiedad PdfExtractor.EndPage

Obtiene o establece la página final en el rango de páginas donde se realizará la operación de extracción.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)