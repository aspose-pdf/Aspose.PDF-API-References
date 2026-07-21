---
title: "Aspose::Pdf::HtmlSaveOptions::AntialiasingProcessingType enum"
linktitle: "AntialiasingProcessingType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::AntialiasingProcessingType enum. Este enum describe las posibles medidas de antialiasing durante la conversión en C++."
type: docs
weight: 5100
url: /es/cpp/aspose.pdf/htmlsaveoptions/antialiasingprocessingtype/
---
## AntialiasingProcessingType enum


Este enum describe posibles medidas de antialiasing durante la conversión.

```cpp
enum class AntialiasingProcessingType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NoAdditionalProcessing | 0 | no se está utilizando ningún procesamiento especial de antialiasing. Esta es una opción óptima para la gran mayoría de documentos y no requiere tiempo adicional durante la conversión. |
| TryCorrectResultHtml | 1 | En ese caso, el convertidor intenta detectar áreas con elementos gráficos de fondo adyacentes y corregir el HTML resultante de manera adecuada. Esta opción permite mejorar el resultado de la exportación para documentos que contienen fondos construidos a partir de varios elementos gráficos adyacentes (para este tipo de documentos, los renderizadores PDF, por ejemplo Acrobat Reader, suelen suavizar los bordes de los elementos durante el renderizado). Con esta opción el convertidor imita ese comportamiento de los renderizadores PDF. Esta opción permite mejorar el diseño del resultado de la exportación para algunos documentos específicos (que utilizan fondos compuestos), pero requiere tiempo adicional para el procesamiento (normalmente alrededor del 10‑15 % de tiempo extra). Por lo tanto, el uso de este modo en casos generales no se recomienda. |

## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
