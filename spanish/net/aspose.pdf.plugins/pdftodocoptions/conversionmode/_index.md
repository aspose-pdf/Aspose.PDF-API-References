---
title: PdfToDocOptions.ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Propiedad PdfToDocOptions. Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto
type: docs
weight: 20
url: /es/net/aspose.pdf.plugins/pdftodocoptions/conversionmode/
---
## Propiedad PdfToDocOptions.ConversionMode

Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto.

```csharp
public ConversionMode ConversionMode { get; set; }
```

## Observaciones

Utilice el modo TextBox cuando el documento resultante no se va a editar mucho más. Los cuadros de texto son fáciles de modificar cuando no hay mucho que hacer.

Utilice el modo Flow cuando el documento de salida necesita más edición. Los párrafos y líneas de texto en el modo flow permiten una fácil modificación del texto, pero los objetos de formato no compatibles se verán peor que en el modo TextBox.

### Véase también

* enum [ConversionMode](../../conversionmode/)
* class [PdfToDocOptions](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)