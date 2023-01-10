---
title: HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for Java API Reference
description: Converted PDF can contain raster images.png .jpeg etc.
type: docs
weight: 24
url: /java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends System.Enum
```

Converted PDF can contain raster images(.png, \*.jpeg etc.) This enum defines methods of how raster images can be handled during conversion of PDF to HTML
## Fields

| Field | Description |
| --- | --- |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | for each distinct raster file will be generated wrapper SVG image, and raster image will be embedded as Base64 encoded strings into that SVG image |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | distinct raster images will be put apart as PNG files but will be referenced through wrapping SVG images, i.e. will be generated one PNG file and one SVG for each raster image, and each of such SVGs will contain links to relevant PNG file |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Will be generated one big PNG background file for each result page. |
### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```


for each distinct raster file will be generated wrapper SVG image, and raster image will be embedded as Base64 encoded strings into that SVG image

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```


distinct raster images will be put apart as PNG files but will be referenced through wrapping SVG images, i.e. will be generated one PNG file and one SVG for each raster image, and each of such SVGs will contain links to relevant PNG file

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```


Will be generated one big PNG background file for each result page. Raster images will be embedded into that file and rendered as regions of that image. No external PNG files for each image will be generated, only one PNG file per page will be present in conversion result set of files.

