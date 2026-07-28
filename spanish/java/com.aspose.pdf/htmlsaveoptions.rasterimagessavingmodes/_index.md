---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El PDF convertido puede contener imágenes raster (.png, *.jpeg, etc.). Este enum define los métodos de cómo pueden manejarse las imágenes raster durante la conversión de PDF a HTML."
type: docs
weight: 2140
url: /es/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

El PDF convertido puede contener imágenes raster (.png, *.jpeg, etc.). Este enum define los métodos de cómo pueden manejarse las imágenes raster durante la conversión de PDF a HTML.

## Campos

| Campo | Descripción |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Se generará un gran archivo PNG de fondo para cada página de resultados. Las imágenes raster se incrustarán en ese archivo y se renderizarán como regiones de esa imagen. No se generarán archivos PNG externos para cada imagen, solo habrá un archivo PNG por página presente en el conjunto de resultados de la conversión. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | Las imágenes raster distintas se separarán como archivos PNG pero se referenciarán mediante imágenes SVG envolventes, es decir, se generará un archivo PNG y un SVG para cada imagen raster, y cada uno de esos SVG contendrá enlaces al archivo PNG correspondiente. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | Para cada archivo raster distinto se generará una imagen SVG envolvente, y la imagen raster se incrustará como cadenas codificadas en Base64 dentro de esa imagen SVG. |
| [DontSave](#DontSave) | No guardar imágenes para diseño fijo |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

Se generará un gran archivo PNG de fondo para cada página de resultados. Las imágenes raster se incrustarán en ese archivo y se renderizarán como regiones de esa imagen. No se generarán archivos PNG externos para cada imagen, solo habrá un archivo PNG por página presente en el conjunto de resultados de la conversión.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

Las imágenes raster distintas se separarán como archivos PNG pero se referenciarán mediante imágenes SVG envolventes, es decir, se generará un archivo PNG y un SVG para cada imagen raster, y cada uno de esos SVG contendrá enlaces al archivo PNG correspondiente.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

Para cada archivo raster distinto se generará una imagen SVG envolvente, y la imagen raster se incrustará como cadenas codificadas en Base64 dentro de esa imagen SVG.

### DontSave {#DontSave}
```
public static final int DontSave
```

No guardar imágenes para diseño fijo
