---
title: "Aspose::Pdf::LowCode::PdfToDocOptions::get_ConversionMode método"
linktitle: "get_ConversionMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::PdfToDocOptions::get_ConversionMode método. Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.lowcode/pdftodocoptions/get_conversionmode/
---
## PdfToDocOptions::get_ConversionMode method


Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto.

```cpp
Aspose::Pdf::LowCode::ConversionMode Aspose::Pdf::LowCode::PdfToDocOptions::get_ConversionMode() const
```

## Observaciones


Utilice el modo [ConversionMode::TextBox](../../conversionmode/) cuando el documento resultante no será editado intensamente. Los cuadros de texto son fáciles de modificar cuando no hay mucho que hacer.

Utilice el modo [ConversionMode::Flow](../../conversionmode/) cuando el documento de salida necesite una edición adicional. Los [Paragraphs](../../../aspose.pdf/paragraphs/) y las líneas de texto en el modo flujo permiten una fácil modificación del texto, pero los objetos de formato no compatibles se verán peor que en el modo [ConversionMode::TextBox](../../conversionmode/).
## Ver también

* Enum [ConversionMode](../../conversionmode/)
* Class [PdfToDocOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
