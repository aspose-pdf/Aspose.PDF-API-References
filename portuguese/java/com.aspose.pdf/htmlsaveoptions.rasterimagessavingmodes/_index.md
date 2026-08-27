---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Referência da API Aspose.PDF para Java"
description: "Um PDF convertido pode conter imagens raster (.png, *.jpeg etc.). Este enum define os métodos de como as imagens raster podem ser tratadas durante a conversão de PDF para HTML."
type: docs
weight: 2140
url: /pt/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

Um PDF convertido pode conter imagens raster (.png, *.jpeg etc.). Este enum define os métodos de como as imagens raster podem ser tratadas durante a conversão de PDF para HTML.

## Campos

| Campo | Descrição |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Será gerado um grande arquivo PNG de fundo para cada página de resultado. As imagens raster serão incorporadas nesse arquivo e renderizadas como regiões dessa imagem. Nenhum arquivo PNG externo será gerado para cada imagem, apenas um arquivo PNG por página estará presente no conjunto de arquivos resultantes da conversão. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | Imagens raster distintas serão separadas como arquivos PNG, mas serão referenciadas por meio de imagens SVG de contorno, ou seja, será gerado um arquivo PNG e um SVG para cada imagem raster, e cada um desses SVGs conterá links para o arquivo PNG correspondente. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | Para cada arquivo raster distinto será gerado uma imagem SVG de contorno, e a imagem raster será incorporada como strings codificadas em Base64 nesse SVG. |
| [DontSave](#DontSave) | Não salvar imagens para Layout Fixo |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

Será gerado um grande arquivo PNG de fundo para cada página de resultado. As imagens raster serão incorporadas nesse arquivo e renderizadas como regiões dessa imagem. Nenhum arquivo PNG externo será gerado para cada imagem, apenas um arquivo PNG por página estará presente no conjunto de arquivos resultantes da conversão.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

Imagens raster distintas serão separadas como arquivos PNG, mas serão referenciadas por meio de imagens SVG de contorno, ou seja, será gerado um arquivo PNG e um SVG para cada imagem raster, e cada um desses SVGs conterá links para o arquivo PNG correspondente.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

Para cada arquivo raster distinto será gerado uma imagem SVG de contorno, e a imagem raster será incorporada como strings codificadas em Base64 nesse SVG.

### DontSave {#DontSave}
```
public static final int DontSave
```

Não salvar imagens para Layout Fixo
