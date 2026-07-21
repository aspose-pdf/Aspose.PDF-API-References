---
title: "Aspose::Pdf::LoadOptions::PageSizeAdjustmentModes enum"
linktitle: "PageSizeAdjustmentModes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LoadOptions::PageSizeAdjustmentModes enum. ¡ATENCIÓN! La funcionalidad está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf/loadoptions/pagesizeadjustmentmodes/
---
## PageSizeAdjustmentModes enum


¡ATENCIÓN! La funcionalidad está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo.

```cpp
enum class PageSizeAdjustmentModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | 0 | En este modo, las páginas resultantes tendrán el tamaño de página requerido definido en [LoadOptions](../), sin importar si el contenido después de la conversión se sale de los límites de la página o no. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | 1 | Este modo define dicho comportamiento: después de obtener el resultado de la conversión y detectar que parte del contenido ha sido truncado, el ancho del portview se amplía para ajustarse al contenido y la conversión se repite. Este modo permite obtener menos páginas en el resultado en ese caso, pero requiere renderizado repetido (y, por lo tanto, más tiempo de procesamiento). |

## Observaciones


Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.) suelen tener un diseño fluido, por lo que permiten ajustar el tamaño de página requerido. Pero a veces el contenido especifica posiciones horizontales o un tamaño que no permite colocar el contenido dentro del tamaño de página requerido. En ese caso podemos definir qué se debe hacer (por ejemplo, cuando el tamaño del contenido no cabe en el tamaño de página inicial requerido del documento PDF resultante).
## Ver también

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
