---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes. O PDF convertido pode conter imagens rasterizadas.png .jpeg etc. Este enum define métodos de como as imagens rasterizadas podem ser tratadas durante a conversão de PDF para HTML
type: docs
weight: 5720
url: /pt/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## Enumeração HtmlSaveOptions.RasterImagesSavingModes

O PDF convertido pode conter imagens rasterizadas(.png, *.jpeg etc.) Este enum define métodos de como as imagens rasterizadas podem ser tratadas durante a conversão de PDF para HTML

```csharp
public enum RasterImagesSavingModes
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | para cada arquivo raster distinto será gerada uma imagem SVG envoltória, e a imagem raster será incorporada como strings codificadas em Base64 nessa imagem SVG |
| AsExternalPngFilesReferencedViaSvg | `1` | imagens raster distintas serão separadas como arquivos PNG, mas serão referenciadas através de imagens SVG envoltórias, ou seja, será gerado um arquivo PNG e um SVG para cada imagem raster, e cada um desses SVGs conterá links para o arquivo PNG relevante |
| AsEmbeddedPartsOfPngPageBackground | `2` | Será gerado um grande arquivo de fundo PNG para cada página de resultado. As imagens rasterizadas serão incorporadas nesse arquivo e renderizadas como regiões dessa imagem. Nenhum arquivo PNG externo para cada imagem será gerado, apenas um arquivo PNG por página estará presente no conjunto de arquivos resultantes da conversão. |
| DontSave | `3` | Não salvar imagens para Layout Fixo |

### Veja Também

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)