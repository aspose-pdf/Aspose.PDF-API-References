---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. Converted PDF can contain raster images.png .jpeg etc. This enum defines methods of how raster images can be handled during conversion of PDF to HTML
type: docs
weight: 5850
url: /net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Converted PDF can contain raster images(.png, *.jpeg etc.) This enum defines methods of how raster images can be handled during conversion of PDF to HTML

```csharp
public enum RasterImagesSavingModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | for each distinct raster file will be generated wrapper SVG image, and raster image will be embedded as Base64 encoded strings into that SVG image |
| AsExternalPngFilesReferencedViaSvg | `1` | distinct raster images will be put apart as PNG files but will be referenced through wrapping SVG images, i.e. will be generated one PNG file and one SVG for each raster image, and each of such SVGs will contain links to relevant PNG file |
| AsEmbeddedPartsOfPngPageBackground | `2` | Will be generated one big PNG background file for each result page. Raster images will be embedded into that file and rendered as regions of that image. No external PNG files for each image will be generated, only one PNG file per page will be present in conversion result set of files. |
| DontSave | `3` | Do not save images for Fixed Layout |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


