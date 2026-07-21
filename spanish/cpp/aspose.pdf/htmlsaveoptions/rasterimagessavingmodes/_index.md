---
title: "Enumeración Aspose::Pdf::HtmlSaveOptions::RasterImagesSavingModes"
linktitle: "RasterImagesSavingModes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enumeración Aspose::Pdf::HtmlSaveOptions::RasterImagesSavingModes. El PDF convertido puede contener imágenes raster (.png, *.jpeg, etc.). Esta enumeración define los métodos de cómo se pueden manejar las imágenes raster durante la conversión de PDF a HTML en C++."
type: docs
weight: 5900
url: /es/cpp/aspose.pdf/htmlsaveoptions/rasterimagessavingmodes/
---
## RasterImagesSavingModes enum


El PDF convertido puede contener imágenes raster (.png, *.jpeg, etc.). Este enum define los métodos de cómo pueden manejarse las imágenes raster durante la conversión de PDF a HTML.

```cpp
enum class RasterImagesSavingModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | 0 | Para cada archivo raster distinto se generará una imagen SVG contenedora, y la imagen raster se incrustará como cadenas codificadas en Base64 dentro de esa imagen SVG. |
| AsExternalPngFilesReferencedViaSvg | 1 | Las imágenes raster distintas se separarán como archivos PNG pero se referenciarán a través de imágenes SVG contenedoras, es decir, se generará un archivo PNG y un SVG para cada imagen raster, y cada uno de esos SVG contendrá enlaces al archivo PNG correspondiente. |
| AsEmbeddedPartsOfPngPageBackground | 2 | Se generará un gran archivo PNG de fondo para cada página de resultados. Las imágenes raster se incrustarán en ese archivo y se renderizarán como regiones de la imagen. No se generarán archivos PNG externos para cada imagen; solo habrá un archivo PNG por página presente en el conjunto de archivos resultantes de la conversión. |
| DontSave | 3 | No guardar imágenes para diseño fijo. |

## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
