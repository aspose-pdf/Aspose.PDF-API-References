---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfFileStamp. Obtiene o establece el número inicial para la primera página en el archivo de entrada. Las siguientes páginas se numerarán a partir de este valor. Por ejemplo, si StartingNumber se establece en 100, las páginas del documento tendrán los números 100, 101, 102
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## Propiedad PdfFileStamp.StartingNumber

Obtiene o establece el número inicial para la primera página en el archivo de entrada. Las siguientes páginas se numerarán a partir de este valor. Por ejemplo, si StartingNumber se establece en 100, las páginas del documento tendrán los números 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)