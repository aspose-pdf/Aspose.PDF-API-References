---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfAOptionsBase. Obtiene o establece la versión del estándar PDF/A que se utilizará para la validación o conversión
type: docs
weight: 110
url: /es/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## Propiedad PdfAOptionsBase.PdfAVersion

Obtiene o establece la versión del estándar PDF/A que se utilizará para la validación o conversión.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Valor de la Propiedad

La versión del estándar PDF/A. Esto puede ser uno de los valores de la enumeración [`PdfAStandardVersion`](../../pdfastandardversion/).

## Observaciones

La versión del estándar PDF/A se utiliza para determinar el nivel de cumplimiento para la validación y conversión de PDF/A. Si la versión se establece en Auto, el sistema determinará automáticamente la versión estándar PDF/A apropiada para la validación basada en los metadatos del documento. Para el proceso de conversión a PDF/A, Auto predetermina la versión estándar PDF/A-1b.

### Véase También

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)