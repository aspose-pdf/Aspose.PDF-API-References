---
title: "Aspose::Pdf::Text::TextEditOptions::ClippingPathsProcessingMode enumeración"
linktitle: "ClippingPathsProcessingMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextEditOptions::ClippingPathsProcessingMode enum. Modos de procesamiento de rutas de recorte en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.pdf.text/texteditoptions/clippingpathsprocessingmode/
---
## ClippingPathsProcessingMode enum


Modos de procesamiento de rutas de recorte.

```cpp
enum class ClippingPathsProcessingMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| KeepIntact | 0 | Mantiene las rutas de recorte del diseño de página original. (Predeterminado) |
| Expand | 1 | La ruta de recorte original se ampliará en caso de que el texto editado requiera más espacio. |
| Eliminar | 2 | La ruta de recorte original se eliminará en caso de que el texto editado requiera más espacio. Precaución: Debido a que las rutas de recorte pueden interactuar entre sí, su eliminación puede provocar resultados inesperados en el diseño de la página. |

## Ver también

* Class [TextEditOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
