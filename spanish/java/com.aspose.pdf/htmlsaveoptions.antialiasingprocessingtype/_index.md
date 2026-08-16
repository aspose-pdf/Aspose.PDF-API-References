---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Este enum describe posibles medidas de antialiasing durante la conversión"
type: docs
weight: 2000
url: /es/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Este enum describe posibles medidas de antialiasing durante la conversión

## Campos

| Campo | Descripción |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | no se utiliza procesamiento de antialiasing especial. Esta es una opción óptima para la gran mayoría de los documentos y no requiere tiempo adicional durante la conversión. |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | En tal caso, el convertidor intenta detectar áreas con elementos gráficos de fondo adyacentes y corregir el HTML resultante de manera adecuada. Esta opción permite mejorar el resultado de la exportación para documentos que contienen fondos construidos a partir de varios elementos gráficos adyacentes (para este tipo de documentos, los renderizadores PDF, p. ej., Acrobat Reader, suelen suavizar los bordes de los elementos durante el renderizado. Con esta opción, el convertidor imita ese comportamiento de los renderizadores PDF). Esta opción permite mejorar el diseño del resultado de la exportación para algunos documentos específicos (que utilizan fondos compuestos), pero requiere tiempo adicional para el procesamiento (usualmente alrededor del 10‑15 % de tiempo adicional). Por lo tanto, el uso de este modo en casos generales no se recomienda. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

no se utiliza procesamiento de antialiasing especial. Esta es una opción óptima para la gran mayoría de los documentos y no requiere tiempo adicional durante la conversión.

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

En tal caso, el convertidor intenta detectar áreas con elementos gráficos de fondo adyacentes y corregir el HTML resultante de manera adecuada. Esta opción permite mejorar el resultado de la exportación para documentos que contienen fondos construidos a partir de varios elementos gráficos adyacentes (para este tipo de documentos, los renderizadores PDF, p. ej., Acrobat Reader, suelen suavizar los bordes de los elementos durante el renderizado. Con esta opción, el convertidor imita ese comportamiento de los renderizadores PDF). Esta opción permite mejorar el diseño del resultado de la exportación para algunos documentos específicos (que utilizan fondos compuestos), pero requiere tiempo adicional para el procesamiento (usualmente alrededor del 10‑15 % de tiempo adicional). Por lo tanto, el uso de este modo en casos generales no se recomienda.
