---
title: "Aspose::Pdf::DocSaveOptions::RecognitionMode enum"
linktitle: "RecognitionMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DocSaveOptions::RecognitionMode enum. Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto en C++."
type: docs
weight: 2700
url: /es/cpp/aspose.pdf/docsaveoptions/recognitionmode/
---
## RecognitionMode enum


Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto.

```cpp
enum class RecognitionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Textbox | 0 | Este modo es rápido y bueno para preservar al máximo el aspecto original del archivo PDF, pero la editabilidad del documento resultante podría ser limitada. |
| Flow | 1 | Modo de reconocimiento completo, el motor realiza agrupación y análisis multinivel para restaurar la intención del autor del documento original y producir un documento lo máximo posible editable. La desventaja es que el documento de salida podría verse diferente del archivo PDF original. |
| EnhancedFlow | 2 | Un modo alternativo [Flow](../../../aspose.pdf.flow/) que soporta el reconocimiento de tablas. |

## Observaciones


Utilice el modo [RecognitionMode::Textbox](./) cuando el documento resultante no vaya a ser editado intensamente. Los cuadros de texto son fáciles de modificar cuando no hay mucho que hacer.

Utilice el modo [RecognitionMode::Flow](./) cuando el documento de salida necesite una edición adicional. [Paragraphs](../../paragraphs/) y texlines en el modo flujo permiten una fácil modificación del texto, pero los objetos de formato no compatibles se verán peor que en el modo [RecognitionMode::Textbox](./).
## Ver también

* Class [DocSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
