---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsRasterImagesSavingModes de Aspose.Pdf. El PDF convertido puede contener imágenes rasterizadas .png .jpeg etc. Este enum define métodos de cómo se pueden manejar las imágenes rasterizadas durante la conversión de PDF a HTML
type: docs
weight: 5720
url: /es/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## Enumeración HtmlSaveOptions.RasterImagesSavingModes

El PDF convertido puede contener imágenes rasterizadas (.png, *.jpeg etc.) Este enum define métodos de cómo se pueden manejar las imágenes rasterizadas durante la conversión de PDF a HTML

```csharp
public enum RasterImagesSavingModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | para cada archivo raster distinto se generará una imagen SVG envolvente, y la imagen raster se incrustará como cadenas codificadas en Base64 dentro de esa imagen SVG |
| AsExternalPngFilesReferencedViaSvg | `1` | las imágenes raster distintas se separarán como archivos PNG pero se referenciarán a través de imágenes SVG envolventes, es decir, se generará un archivo PNG y un SVG para cada imagen raster, y cada uno de esos SVG contendrá enlaces al archivo PNG relevante |
| AsEmbeddedPartsOfPngPageBackground | `2` | Se generará un gran archivo de fondo PNG para cada página de resultado. Las imágenes raster se incrustarán en ese archivo y se renderizarán como regiones de esa imagen. No se generarán archivos PNG externos para cada imagen, solo habrá un archivo PNG por página en el conjunto de archivos resultantes de la conversión. |
| DontSave | `3` | No guardar imágenes para diseño fijo |

### Véase también

* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)