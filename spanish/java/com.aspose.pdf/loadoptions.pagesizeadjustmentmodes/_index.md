---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "¡ATENCIÓN! La función está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED revelado para el documento de ejemplo. Representa el modo de uso del tamaño de página."
type: docs
weight: 2810
url: /es/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

¡ATENCIÓN! La característica está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo. Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.), suelen tener un diseño flotante, por lo que permite ajustar el tamaño de página requerido. Pero a veces el contenido especifica posiciones horizontales o un tamaño que no permite colocar el contenido en el tamaño de página requerido. En tal caso podemos definir qué debe hacerse (es decir, cuando el tamaño del contenido no encaja en el tamaño de página inicial requerido del documento PDF resultante).

## Campos

| Campo | Descripción |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Este modo define el siguiente comportamiento: después de obtener el resultado de la conversión y detectar el hecho de que parte del contenido ha sido truncado, el ancho de la vista del puerto se amplía para ajustarse al contenido y la conversión se repite. Este modo permite obtener menos páginas en el resultado en tal caso, pero requiere renderizado repetido (y, por lo tanto, más tiempo de procesamiento). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | En este modo, las páginas resultantes tendrán el tamaño de página requerido definido en LoadOptions, sin importar si el contenido después de la conversión se sale de los límites de la página o no. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Este modo define el siguiente comportamiento: después de obtener el resultado de la conversión y detectar el hecho de que parte del contenido ha sido truncado, el ancho de la vista del puerto se amplía para ajustarse al contenido y la conversión se repite. Este modo permite obtener menos páginas en el resultado en tal caso, pero requiere renderizado repetido (y, por lo tanto, más tiempo de procesamiento).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

En este modo, las páginas resultantes tendrán el tamaño de página requerido definido en LoadOptions, sin importar si el contenido después de la conversión se sale de los límites de la página o no.
