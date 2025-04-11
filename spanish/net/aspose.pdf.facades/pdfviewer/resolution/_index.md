---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfViewer. Obtiene o establece la resolución durante la visualización y la impresión. Cuanto mayor sea la resolución, más lenta será la velocidad. El valor predeterminado es 150.
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/pdfviewer/resolution/
---
## Propiedad PdfViewer.Resolution

Obtiene o establece la resolución durante la visualización y la impresión. Cuanto mayor sea la resolución, más lenta será la velocidad. El valor predeterminado es 150.

```csharp
public int Resolution { get; set; }
```

## Observaciones

Esta propiedad cambia la resolución de la imagen en los flujos de conversión de página a imagen: cuando [`PrintAsImage`](../printasimage/) se establece en `true`, o cuando se llama al método [`DecodePage`](../decodepage/) o [`DecodeAllPages`](../decodeallpages/). Para establecer una resolución de impresora para la impresión directa a una impresora, use la propiedad [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) en la clase [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Véase también

* clase [PdfViewer](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)