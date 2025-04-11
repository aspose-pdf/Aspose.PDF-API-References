---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfPageEditor. Obtiene o establece el coeficiente de zoom. El valor 1.0 corresponde al 100%. El valor predeterminado es 1.0. El siguiente ejemplo demuestra cómo cambiar el zoom de las páginas del documento.
type: docs
weight: 110
url: /es/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## Propiedad PdfPageEditor.Zoom

Obtiene o establece el coeficiente de zoom. El valor 1.0 corresponde al 100%. El valor predeterminado es 1.0. El siguiente ejemplo demuestra cómo cambiar el zoom de las páginas del documento.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### Ver También

* clase [PdfPageEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)