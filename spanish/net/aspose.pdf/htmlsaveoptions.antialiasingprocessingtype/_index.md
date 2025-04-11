---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsAntialiasingProcessingType de Aspose.Pdf. Este enum describe las posibles medidas de antialiasing durante la conversión
type: docs
weight: 5570
url: /es/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## Enumeración HtmlSaveOptions.AntialiasingProcessingType

Este enum describe las posibles medidas de antialiasing durante la conversión

```csharp
public enum AntialiasingProcessingType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | no se utiliza procesamiento especial de antialiasing. Esta es una opción óptima para la abrumadora mayoría de los documentos y no requiere tiempo adicional durante la conversión |
| TryCorrectResultHtml | `1` | En tal caso, el convertidor intenta detectar lugares con elementos gráficos de fondo adyacentes y corregir el HTML resultante de manera relevante. Esta opción permite mejorar el resultado de la exportación para documentos que contienen fondos construidos a partir de varios elementos gráficos adyacentes (para este tipo de documentos, los renderizadores de PDF, por ejemplo, Acrobat Reader, generalmente intentan suavizar los límites de los elementos durante el renderizado. Con esta opción, el convertidor imita ese comportamiento de los renderizadores de PDF. Esta opción permite mejorar el diseño del resultado de la exportación para algunos documentos específicos (que utilizan tales fondos compuestos), pero requiere tiempo adicional para el procesamiento (generalmente alrededor del 10-15% de tiempo adicional). Por lo tanto, el uso de este modo en general no se recomienda. |

### Véase también

* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)