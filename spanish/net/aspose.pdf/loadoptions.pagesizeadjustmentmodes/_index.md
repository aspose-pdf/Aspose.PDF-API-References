---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Enum LoadOptionsPageSizeAdjustmentModes de Aspose.Pdf. ATENCIÓN La función está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED revelado para el documento de muestra. Representa el modo de uso del tamaño de página durante la conversión. Formatos como HTML, EPUB, etc., generalmente tienen un diseño flotante, por lo que permite ajustar el tamaño de página requerido. Pero a veces el contenido tiene posiciones o tamaños horizontales específicos que no permiten colocar el contenido en el tamaño de página requerido. En tal caso, podemos definir qué se debe hacer en este caso, es decir, cuando el tamaño del contenido no se ajusta al tamaño de página inicial requerido del documento PDF resultante.
type: docs
weight: 6140
url: /es/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## Enumeración LoadOptions.PageSizeAdjustmentModes

¡ATENCIÓN! La función está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED revelado para el documento de muestra. Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.), generalmente tienen un diseño flotante, por lo que permite ajustar el tamaño de página requerido. Pero a veces el contenido tiene posiciones o tamaños horizontales específicos que no permiten colocar el contenido en el tamaño de página requerido. En tal caso, podemos definir qué se debe hacer en este caso (es decir, cuando el tamaño del contenido no se ajusta al tamaño de página inicial requerido del documento PDF resultante).

```csharp
public enum PageSizeAdjustmentModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | En este modo, las páginas resultantes tendrán el tamaño de página requerido definido en LoadOptions, sin importar si el contenido después de la conversión sale de los límites de la página o no. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Este modo define el siguiente comportamiento: después de obtener el resultado de la conversión y detectar que algún contenido ha sido truncado, se amplía el ancho del puerto para ajustar el contenido y se repite la conversión. Este modo permite obtener menos páginas en el resultado en tal caso, pero requiere un renderizado repetido (y, por lo tanto, más tiempo de procesamiento). |

### Ver También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)