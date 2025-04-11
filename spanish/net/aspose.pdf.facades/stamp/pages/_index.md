---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de Stamp. Obtiene o establece un arreglo con los números de páginas que se verán afectadas por el sello. Si Pages es null, todas las páginas del documento se ven afectadas.
type: docs
weight: 60
url: /es/net/aspose.pdf.facades/stamp/pages/
---
## Propiedad Stamp.Pages

Obtiene o establece un arreglo con los números de páginas que se verán afectadas por el sello. Si Pages = null, todas las páginas del documento se ven afectadas.

```csharp
public int[] Pages { get; set; }
```

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ver También

* clase [Stamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)