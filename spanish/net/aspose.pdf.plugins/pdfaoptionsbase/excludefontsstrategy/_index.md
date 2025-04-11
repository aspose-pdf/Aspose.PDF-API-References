---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfAOptionsBase. Obtiene o establece la estrategia para eliminar fuentes para minimizar el tamaño del archivo de salida durante el proceso de conversión a PDF/A
type: docs
weight: 30
url: /es/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## Propiedad PdfAOptionsBase.ExcludeFontsStrategy

Obtiene o establece la estrategia para eliminar fuentes para minimizar el tamaño del archivo de salida durante el proceso de conversión a PDF/A.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Valor de la Propiedad

La estrategia para eliminar fuentes. Esto puede ser uno de los valores de la enumeración [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/). El valor predeterminado es la combinación de SubsetFonts y RemoveDuplicatedFonts.

## Comentarios

Esta propiedad te permite controlar cómo se manejan las fuentes durante el proceso de conversión. Puedes elegir eliminar fuentes duplicadas, eliminar fuentes similares con diferentes anchos, o subconjuntos de fuentes.

### Véase También

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)