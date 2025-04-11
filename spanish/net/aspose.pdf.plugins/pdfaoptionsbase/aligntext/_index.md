---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: Propiedad PdfAOptionsBase. Obtiene o establece un valor que indica si son necesarios medios adicionales para preservar la alineación del texto durante el proceso de conversión a PDF/A
type: docs
weight: 10
url: /es/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## Propiedad PdfAOptionsBase.AlignText

Obtiene o establece un valor que indica si son necesarios medios adicionales para preservar la alineación del texto durante el proceso de conversión a PDF/A.

```csharp
public bool AlignText { get; set; }
```

### Valor de la Propiedad

`true` si la alineación del texto cambia y son necesarias acciones adicionales para restaurarla; de lo contrario, `false`.

## Observaciones

Cuando se establece en `true`, el proceso de conversión intentará restaurar los límites del segmento de texto original. Para la mayoría de los documentos, no es necesario cambiar esta propiedad del valor predeterminado `false`, ya que la alineación del texto no cambia durante el proceso de conversión predeterminado.

### Véase También

* clase [PdfAOptionsBase](../)
* espacio de nombres [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../../)