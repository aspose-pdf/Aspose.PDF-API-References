---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum DocSaveOptionsRecognitionMode de Aspose.Pdf. Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto
type: docs
weight: 3770
url: /es/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## Enumeración DocSaveOptions.RecognitionMode

Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto.

```csharp
public enum RecognitionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Textbox | `0` | Este modo es rápido y bueno para preservar al máximo la apariencia original del archivo PDF, pero la editabilidad del documento resultante podría ser limitada. |
| Flow | `1` | Modo de reconocimiento completo, el motor realiza agrupamiento y análisis multinivel para restaurar la intención original del autor del documento y producir un documento maximamente editable. La desventaja es que el documento de salida podría verse diferente del archivo PDF original. |
| EnhancedFlow | `2` | Un modo Flow alternativo que admite el reconocimiento de tablas. |

## Observaciones

Utilice el modo Textbox cuando el documento resultante no vaya a ser editado en gran medida posteriormente. Los cuadros de texto son fáciles de modificar cuando no hay mucho que hacer.

Utilice el modo Flow cuando el documento de salida necesite más edición. Los párrafos y líneas de texto en el modo flow permiten una fácil modificación del texto, pero los objetos de formato no soportados se verán peor que en el modo Textbox.

### Véase también

* clase [DocSaveOptions](../docsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)